- Preface: LINKS

Many people seem to have had trouble digging up the material I have referenced in my previous posts. Here is the list:

DDIA - https://dataintensive.net/buy.html
Grokking - https://www.educative.io/courses/grokking-the-system-design-interview
Nathan Bronson's Tao: https://www.usenix.org/conference/atc13/technical-sessions/presentation/bronson
Nishtala's memcache: https://www.usenix.org/conference/nsdi13/technical-sessions/presentation/nishtala
Kulkarni's Facebook live: https://www.youtube.com/watch?v=IO4teCbHvZw
Aroskar's Zuul push: https://www.youtube.com/watch?v=6w6E_B55p0E
NALSD on Google SRE book: https://sre.google/workbook/non-abstract-design/
Krikorian's timelines at scale: https://www.infoq.com/presentations/Twitter-Timeline-Scalability/
Cassandra's capacity planning guidelines by datastax: https://docs.datastax.com/en/dse-planning/doc/planning/capacityPlanning.html
Youtube guy: https://www.youtube.com/channel/UC9vLsnF6QPYuH51njmIooCQ

===== Extra mile stuff ====

Check Bronson's TAO pdf paper in same link as video
Check Nishtala's pdf paper in same link as video
Lamport's ordering paper: https://lamport.azurewebsites.net/pubs/time-clocks.pdf
Paxos (simpler version, not the greek parliament metaphor version): https://www.microsoft.com/en-us/research/publication/paxos-made-simple/
Raft: http://thesecretlivesofdata.com/raft/ and also http://kanaka.github.io/raft.js/
Dynamo: https://www.allthingsdistributed.com/2007/10/amazons_dynamo.html

-- end of Preface --

This part will focus on logistics and time management on the day of the interview. This stuff is less 'scientific' in nature. It's the way I did it and it served me quite well.

Let's suppose your interview starts at 11.00 and lasts 45 mins. Do NOT go in cold. Keep the hour before open. At 10.00 start a mock. Pick a question you're comfortable with. Work on it alone until 10.30. Everyone that has done a day of sport knows this - never go in with cold muscles. Same goes for the brain.

At 10.30 start double checking your setup. Do not underestimate this part. It is *your* responsibility to have a smooth setup from your side. I had a phone ready as a backup internet connection if my cable connection crapped on me. Stick to cable if possible and not Wifi. Check the camera and the angle and make sure it's pretty neutral with the background etc.

Don't wear fancy stuff. You're not getting married. Anything simple works, as long as it's not distracting. By 10.45 you should be done with this stuff. Between 10.45 and 11.00 do all the natural stuff, eat, drink (don't plan to do any drinking during interview - no distractions), pee, poo.

At 10:59 be ready near your desk. Take out your phone and start a timer that you'll be able to see throughout. Start it at 46 minutes and keep it running and visible. Don't get over-eager and join the call at 10:55. No one will give you points for being early. Join the call as soon as it clocks 11.00.

Now before I go into this, I have a hint. At this stage your mind gets some extra excitement and the body responds too. Do not let your mind race. Keep your mind in the exact middle. Don't pull it to tight and don't let it too loose. The body can react with some tension, it's ok. But keep the mind in the exact center. It will naturally start working faster when you get into the exercise but keep calm as you join.

The interviewer usually joins on time. Say 'Hi' and stay neutral. Don't get all smiley and over-friendly and 'OMG I'm talking to an L7' and all that crap. Keep it neutral. No one cares. As the discussion gets going aim for as short intro as possible. These are precious minutes. The sooner you start the real deal the better. It shouldn't last more than 5 minutes.

Once you hear the problem start asking clarifying questions. It should take 5 (10 max) minutes to clarify. As you take notes of the answers start thinking of calculations in the background. Once you have clarified the problem, start doing some back of the envelope calculations. Usually that can involve QPS, Storage, Ram etc. (see part 2). I tend to do back of the envelope calculations in two places: a) in the beginning to inform my high-level design. b) in the detail phase to size tiers. These initial calculations shouldn't take more than 5 minutes.

So until now you have 5 intro+5 clarification+5 calculations=15 minutes mark. This is when you do the high-level design. That should be around 10 minutes. By the 25 minute-mark you should be done with the High-level stuff.

As you are drawing the high-level design stuff, start a background thread in your head and start thinking about the -bound (see part 2) of different components. It can be done in parallel, don't freak out. We do that all the time, especially when you talk to that boring friend (shakes head pretending to listen).

After you're done with high level, you have a key checkpoint. Ideally you'll have the intuition to nail the component that need details the most. You can't go into details on all components. You have time only for 2-3. What you do here is you propose your plan to the interviewer. Say 'Now that we have an initial High-level draft in place I propose to get into the details of these components here as I find them to be most interesting to detail'. Then look at the interviewer for any clue. If you nail this is it's extra point. However they might want to hear about something else and might steer you elsewhere. Not the end of the world, but it's best if you nail it yourself.

Now the next 15 minutes need to be spent going deep in some component until you feel you covered that, then pull up, get into the next component to detail and go deep there too. As you go deep you might have to do some sizing calculations. They take 3-5 minutes at least so be selective, it's hard to do calculations for everything. Decide which component to detail with calculations, get validation from interviewer and get to it. In the end, pull up, look at the whole thing and make some potential overarching comments. Maybe observability, evolvability, infrastructure needs etc.

As I mentioned earlier, keep it neutral. No jokes, funny drawings and other crap like that.

So to recap:
5 - intro (keep it short, you'll need every minute you can get)
5 - clarifications on the question
5 - initial back of envelope calcs
10-high-level design
15-deep stuff+sizing calcs+closing overarching comments
5-questions from you (as long as you don't ask completely dumb questions, you should be fine)
---
45 minutes

Some interviewers will give you some extra minute but don't count on that. Prepare to be sharp on time.

That's it for Part 3. There will be a Part 4.
----

One last comment, I've received around 200+ private messages. I will eventually reply, please be patient. You can definitely PM me, just be conscious it might take a while to receive a reply. I have been on the other side of it so I know it can be frustrating when you receive no reply on a PM. But have some patience, the response to these posts has been overwhelming and I decided to spend most of my available time to write more content first, and respond to messages next. I think I'm helping more people this way.
