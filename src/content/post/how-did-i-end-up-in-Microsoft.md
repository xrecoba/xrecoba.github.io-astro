---
publishDate: 2022-05-30T00:00:00Z
title: How did I end up in Microsoft
excerpt: The story of my interview process with Microsoft on 2008 (as it was written in 2008).
image: ~/assets/images/blog/how-did-I-end-up-in-Microsoft/microsoft-logo.jpg
tags:
  - Microsoft
  - Personal story
  - Hiring
---

<i>
This long article is a translation of an errand I wrote on August 2008, just after arriving to Denmark called <a href="https://spamspamm.blogspot.com/2008/06/com-es-pot-anar-petar-tant-amunt.html">“Com es pot anar a petar tant amunt…”</a> which would mean something like “How can one end up so in the north”. Feel free to read the original if you understand catalan (I would say it's more expressive), but beware that there are some places where I disagree with my old me 😉.
</i>

<h1>How did I end up in Microsoft</h1>

<h2>Sending the CV(s)</h2>
It all started around October of 2007, there was an ad in a magazine called DotNetMania (a paper magazine about .Net which no longer exists) asking: "Do you want to work at Microsoft?" The requirements were to be an engineer (of any kind) and have 2 or 3 years of experience in C#. I met the requirements and wanted to work at Microsoft, so I went for it, <i>from lost to the river</i>. 

<img src="/assets/blog/how-did-I-end-up-in-Microsoft/Microsoft-job-offer.jpg"></img>


The ad did not give any clue as to what kind of work it was or where it was (it said a pretty generic Europe), so I sent my standard CV to a Spanish email address. A week later they answered my email telling me to send them my English version of the resume (as if I had an English version of it at that moment in time 😂).


I prepared and sent it and after like 2 or 3 months without news on their side, one day I received a rather long email telling me that I had been selected to do a phone interview with Redmond. I had to confirm them the the proposed  time slot was OK to me (and I was very lucky because they offered me a Friday at 10 pm, considering I worked full time and went to class after work because of the Master in SW engineering 4 days a week, they hit my sweet spot)

<h2>Phone interview</h2>
The famous call lasted about 45 minutes, I spoke with a very kind woman who asked me all sorts of varied questions:
<ul>
    <li>How to manage memory in C#: Here I did well, because I told her about managed memory, unmanaged, destroyers, finalizers and bullshit I had fresh at that time because I just got the 70 -536 and that I have now quite forgotten. After my initial reply, I asked her if I should continue or if it was enough, she laughed and told me that knowing that the memory was managed was enough🤭.
    </li>
    <li>
    “how to test a keyboard” (and this is a question I have repeated while interviewing testers). Yes, what would you do to test it ... press all the keys, drop it on the floor and see if it still works, plug it into different computers, etc ... whatever your imagination requires.
    </li>
    <li>The following one was a riddle: If we have three boxes, one with apples, one with pears and one with apples and pears. The signs that indicate the contents of each box are all messed up, and none it’s in the corresponding box. You can’t look at what is in each box but you can put your hand inside and take out a piece of fruit. How do you know what is really in each box by removing the minimum number of fruits?
    </li>
</ul>
And more questions that I don't remember now ... As a curiosity, I was lucky enough not to be asked about the method table of a class (I guess because I introduced myself as a C# programmer) which they did to other interviewed colleagues (who knew C ++).
At the end of the interview, of course, a round of feedback and questions. The woman told me that the job was gonna be in Redmond and that they would probably tell me something more soon. In her opinion I performed well.


And they didn't say anything until ... 3 or 4 months had gone by. I was pretty nervous during that period, I even sent them an email to see if they still remembered me and I continued to get Microsoft certifications as it was a promoted practice inside my company. After obtaining my last certification I sent them an email saying with my updated resumé and 15 days later I got an email explaining that I would soon receive an invitation to go to Copenhagen for a job interview. I was also told that the jobs would be for me to choose between SDE and SDET, which means Software Developer Engineer and Software Developer Engineer in Test, which in my head finally translated to a programmer and tester.

Apart from that, they gave me a lot of documentation (videos, books and links) that they recommended to prepare for the interview. This was very cool for me at that moment in time, a motivation rush, I eagerly devoured all that I could between that moment and the interview.

One week later I received the official interview invitation. It would be in Copenhagen on April 21st, after a few emails and formalities we agreed I would go there on the 20th (a Sunday), interview on Monday afternoon and return Tuesday morning to barna. All expenses were on by Ms (except for the 2 days off I would happily invest 🙃). I spent the rest of the month reading the recommended books like crazy.

Ironically, I thought that the only one of the two positions I had a chance for was as a programmer (which is what I had done all my life, the culture of testing in Catalonia ... was rather non-existent in my surroundings. At least I've never worked in a company that has a tester) and in the end I was hired as a tester 😁.

<h2>The in-person interview</h2>

The interview was... very strange according to my standards at that moment in time. Turns out that it was a week of interviews at Microsoft Development Center Copenhagen (MDCC). From Monday to Friday they interviewed 5 persons every morning and every afternoon (50 in total), of whom they intended to hire between 10 and 15. All these persons came there following the same process as I did, at least the ones I had the chance to speak with.

The interviews consisted of 5 interviewers, 3 of them working at MDCC, one in Redmond and one person from human resources (I never saw that woman again once there). Each of the interviewers was interviewed for about 50 minutes with each of the interviewees separately.

After each mini interview there were 2 meetings/breaks, one for the interviewers and one for the interviewees. Throughout this process you felt a bit like if you were inside the <a href="https://ca.wikipedia.org/wiki/El_m%C3%A8tode_Gr%C3%B6nholm">Mètode Gronholm</a>: Interviewers discussed things from the interviews and “played” (I’ll never know if this was on purpose) a little with you, referred to the content of previous interviews, you never knew if you were answering correctly, if they were teasing you or if you they were praising you (imagine the level of insecurity I had at the time). On top of that, the other interviewees were in a situation identical to mine, and during the breaks we were talking (obviously one of the topics of conversation was the interviews that had already been done) and as the interviews progressed they gave us more and more information. 

<h3>First interview</h3>
I started with an American who was a head of testing for I don't know what (surprise, he became my head of testing). He first asked me what the most difficult problem I had ever solved was. I was left blank (yes, I got off to a good start!) and told him I couldn’t tell him, but that if I wanted to I would tell him a problem I had never been able to solve. He told me he was fine and I explained to him that we had a localization problem with Win Form controls derived from controls ... well ... a problem we never were able to tackle and that we workaround with brute force.

He then told me to code a function that, given the time and minute of the day, would answer the degrees of the smallest angle that could be made between the hands of the clock. I did it, and once I finished he said to me with a very friendly tone "you have at least three mistakes in your code". I got frozen 🥶. After recovering from the surprise, I took a deep breath and luckily realized where the bugs were in my code and fixed them. After that, time ran out discussing how we would unit test the function and where to stop or not to stop testing (this final part was almost a learning session for me).

<h3>Second interview</h3>
The second interview was with a Ukrainian who worked as a Dynamics AX tester whom I found at work! In fact, on the 1st day I played foosball against him. He asked me about database things (and here I have to thank the master I had recently studied because thanks to Mr. Rafael Camps Carré I was able to answer something moderately decent when he asked me about the normalization of databases, which I had completely forgotten before starting the master's degree), he made me normalize a table in a database while discussing a problem for which he had not given me all the information, and finally he made me a logic test: Let's go from A to B at 100 Km/h and we return from B to A at 200 Km/h. What was the average speed of our trip? I solved it correctly on my second answer (so I was consistent with not having the right answer on the first attempt).

BTW, the database discussion had some crazy moments because in Spain postal codes can correspond to multiple towns (which doesn't happen in Denmark or Ukraine it seems). It took us a while to understand why were we modeling it differently 🤭.

<h3>Third interview</h3>
Next one was with a man in his forties who had been in the company for ages and had held all kinds of positions (it was really impressive). He began the interview by suggesting the following setup:

<ul> 
    <li>We have a testing environment and we are so good that we have never tested it.</li>
    <li>We have a new program and we are so good that we have never tried it.</li>
    <li>We have 1000 unit tests to run on the testing environment, against the program and we are so good that we have never tested them.</li>
    <li>It turns out that when we run the tests in the new environment, we lose 1000 MB</li>
</ul>

And then he asked: How would you find where the memory is lost?

It was a kind of logic game that I faced doing bolzano and breaking everything in half. I was making proposals (I would run 500 tests instead of 1000) and he would tell me what the consequences of the tests were (you lost 500 MB) until we realized that the test base class had a memory leak in the initializer (obviously he was inventing details as I approached it). That whole question was fun and engaging.

He then gave me a small testing master class and then asked me how I would test a DVD player using what I had learned in the class. We created a matrix with testing criterias on one axis and product features on the other and I filled the matrix doing my best.

Finally, I coded a function that converted a decimal number to binary (the language was optional, as usual I chose C #, of course).

<h3>Fourth interview</h3>
This one was a DISASTER with capital letters 💥. It was done to me by an Indian (and I struggled a lot to understand him) who didn’t look me in the face, didn’t answer my questions, and kept typing on the laptop while he was ignoring me. On top of that he just asked me how I would test an environment where there was a picking, packing, a CRM and a Ledger account (¿?). I didn’t know what an account ledger was and I asked him 4 times until I got fed up with his void answers and feeling ignored. I finally spent 45 minutes inventing nonsense about the system I had to test while trying to be infinitely ambiguous about the fantastic Account Ledger.

Honestly, when I was there I was kinda bitter about this interview, but now that I look at it with perspective I guess that the guy was just testing me or putting out a fire at the same time he had to do an interview. If that were the case, I would have appreciated an explanation on his side though. I talked to other interviewees and interviewers who had been very nice to me, had not been nice to them and vice versa. Part of the interview process? Maybe it was only us fantasizing about the whole process…

<h3>Fifth interview</h3>
The last interview was with the HR woman. She was very friendly and nice and, except for a logic problem, she didn't ask me questions that made me think too much. It was a shorter interview than the others and after half an hour (I had been interviewing for 4 hours and was close to exhausted) we went out to the front desk and asked for a taxi back to the hotel. By the way, the logic problem was:

You are in an oasis full of water. You have a 7 liter jug ​​and a 4 liter jug. How would you give 1 liter of water to your camel?

And another thing, I dared to tell her that I had read <a href="https://www.amazon.com/How-Would-Move-Mount-Fuji/dp/0316778494">How would you move mount Fuji</a> (a recommendable book if you like logic games and/or weird job interview stories but very oriented to the world Ms and probably outdated). I say I dared because the book in question contains the answer to ALL the riddles that had been done to me during the selection process. Although I was clear that I did not know them by heart (I made mistakes and I did most of the reasoning aloud), I assume that this information could have distorted the process.

And that's where the interview ended. Then, at dinner time, all the interviewees met at the hotel and we were able to talk a little more calmly about it all. It turns out that 2 of the 5 had been asked for a taxi after the 3rd interview. At the time we didn’t know if this was very good or very bad, now I guess we can say it was bad because none of them got hired. Another only reached the 4th and 2 of us did all the interviews. In any case, everyone answered all the logic problems correctly (we didn't go into the number of attempts) which is why I deduce that logic problems only serve to rule out people.

<h2>The offer</h2>
And that's pretty much all there is to the selection process. After 10 days they sent me an email congratulating me because they had decided to make me an offer and from there everything was rushed. I accepted without any kind of bargaining and went there to start working as a tester, live abroad and learn lots of things.
<img src="/assets/blog/how-did-I-end-up-in-Microsoft/offer.jpg"></img>

BTW, once in MDCC, I realized my first interviewer was the test lead for the whole Microsoft Dynamics NAV product (So my lead's lead). Once, at a party, I asked him why did he move forward with me if I started my first interview writing 10 lines of code with 3 mistakes. The answer was a lesson: "Because you were humble about the criticism, embraced my feedback, found the bugs and fixed them" 🥳. So another lesson to wrap up: Let the people make mistakes in the interview. 

Thanks for reading 😄
