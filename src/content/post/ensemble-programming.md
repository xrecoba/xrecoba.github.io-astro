---
publishDate: 2022-04-18T00:00:00Z
title: Ensemble 101
excerpt: Some notes on ensemble programming after reading Technical Agile Coaching with the Samman method from Emily Bache.
image: ~/assets/images/blog/ensemble-session.jpg
tags:
  - Ensemble
  - Mob
  - resources
---

A while ago I read <a href ="https://leanpub.com/techagilecoach">"Technical Agile Coaching with the Samman method"</a> from <a href="https://twitter.com/emilybache">Emily Bache</a> which has changed a little bit how I understand what I previously had known as Mob programming sessions. So... yes, here's the first change: Emily favours the term <mark>ensemble</mark>, which refers to a group of people performing together, over Mob because it doesn't have any destructive connotations.

<h1>What is ensemble programming</h1>
Is a programming session where the whole team works together in one single task.

<h2>Mandatory roles</h2>
<h3>Typist</h3>
The person who is typing on the computer what the rest of the colleagues are saying. Important to realize that the typist doesn't have its own ideas, funnels navigator's and the rest of the ensemble ideas into the computer.

I find the name interesting in contraposition to driver which is used a lot in the context of pair programming (where the driver has an active voice). The way I understand it, the typist is not <i>driving</i> the session, just the opposite, is being driven.

<h3>Navigator</h3>
There must be only one single navigator with the responsibility of explaining what should be done... and there's an important nuance: The explanation should be done with the highest possible abstraction level.

Emily talks about 3 levels of communication that can be used:
<ol>
<li>Intention - Express what you pretend to do. If the driver knows how would she accomplish that, she's good to go.</li>
<li>Location - If after expressing the intent, the driver still doesn't know where to start acting, add information of where you would do it: "Go to class X".</li>
<li>Details - After intention and location have been expressed, if the driver still frozen, it's time to be very explicit on the how: "Introduce line 45 and a half and type..."</li>
</ol>


<h3>Supporters</h3>
Unless there are people acting with other roles, this would be everyone else in the ensemble. The supporters should be actively listening and helping both the driver and the navigator measuring their contributions. In their case, silence is very valuable, as sometimes waiting a couple of extra seconds to say something can really spare that comment, it's important not to disrupt the flow and avoid context switching when possible.

Flow should be interrupted whenever a team member is not following the current work to ask for explanations or clarifications.

<h2>Optional roles</h2>
<h3>Facilitator</h3>
Used by teams who are learning to ensemble, the person with this role ensures the guidelines to do it properly are being followed (rotations on time, roles are respected, breaks are taken, ...)

<h3>Researcher</h3>
Whenever a very specific information is needed, the researcher is entitled to use a second computer and search for that information. Once is found, then the researcher goes back to its original role of supporter (I've done this in a more wacky way, were almost everyone was googling in parallel whenever we got stuck somewhere 😅)

<h3>Archivist</h3>
This person is kinda writing the diary of the session: which alternatives were dismissed and why, steps done, tried things... whatever you feel it's worth recording.

<h3>Coach</h3>
The last optional role in an ensemble is the coach (not surprisingly, considering the book). The ensemble is an excellent forum for a coach, the whole team is there and working on a specific task (hopefully related to their real goals). The coach can benefit from the occasion to do multiple activities:
<ul>
<li> Teach - If there's a knowledge gap in the team, the coach may teach them some focused content that can be immediately used. This teaching mini-session will probably disrupt the flow of the session for a moment.</li>
<li> Mentor - Use the coach experience to lead the team to a better solution, by facilitating the adoption of new techniques or the application of concepts the team is aware of but not fully proficient with.</li>
<li>Facilitate - Help the team have a smooth ensemble, ensure every voice is heard and respected and ensemble good practices are followed (this would be putting the coach in facilitator role)
<li>Coach - Ask questions that help the team to find better solutions (answers should come from the team itself).</li>
<li>Observe - Follow with attention how the team works together and identify patterns and ways of improving they would appreciate but fail to identify. Since the goal of the coach is to make him/herself disposable for the team, it's interesting to take a step back every once in a while and observe how does the team collaborate without the coach's influence.</li>
<li>Take breaks - The coach should lead by example and take reasonable breaks too. These breaks will leave the team on its own... so it's a good opportunity for the team and the coach to see how they manage by themselves.</li>
<li>Retrospect - After an ensemble session, make sure the improvements and learnings are shared and collected. If the coach took an observer role, it's a good moment to share its findings.</li>
</ul>


<h2>Ensemble good manners</h2>
<h3>Navigator should tell before typist writes</h3>
If a typist starts to write before the navigator has explained its intention it should stop. 
<h3>Write first, argue afterwards</h3>
The driver should write the code and argue afterwards. Conversation is easier in front of a living example that you can toy around with.
<h3>Yes, and</h3>
I've been multiple times in an ensemble session with the feeling that we were running in circles, doing and undoing code. Emily suggests a simple rule that hopefully alleviates these situations, the "Yes, and" rule. 
Inspired by improvisational theater, the rule states that you should also follow up the conversation with a "yes, and". Translated to the ensemble context, this means you should not negate (delete) what has been done before you get the navigator or typist role, you should build on top of it and refactor if you consider that appropriate.

In my case, we sometimes used an alternative to this rule that we called the "3 minutes rule", where someone in the ensemble was allowed to work alone for 3 minutes and then we all discussed the outcome. It helped us move forward when we where blocked, but I see these rules targeting different problems.

<h2>Want more?</h2>
These are just some notes on <a href ="https://leanpub.com/techagilecoach">"Technical Agile Coaching with the Samman method"</a>, I highly recommend you the book if you found this short article interesting, the book is way better and also has great contents on Learning Hours and coaching in general.