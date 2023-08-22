---
publishDate: 2021-02-24T00:00:00Z
title: The Dora Retro
excerpt: A retrospective to reflect on learnings from Accelerate and the Dora Project and how they can be mapped to your team
image: ~/assets/images/blog/the-dora-retro/the-dora-retro-header.png
tags:
  - DORA metrics
  - DevOps   
---

<h2>Book retros</h2>

I like to do retros often, to have short feedback loops, and with variety, to stimulate conversations and topic diversity. Given that context, I have debility for what I call <mark>book retros</mark>. A book retrospective is a thematic retrospective built around the main ideas explained in a book. 

The goal of a book retro is multiple:
* Gather ideas on how to improve (as usual with retros) on a topic (maybe the topic is not your usual topic though)
* Very short training around the topic (hopefully to trigger team's interest on the topic or at least raise awareness)
* Align team expectations on the topic
* Bonus point: Help getting your retros out of the groundhog day if you have such problem

<h2>The <s>Accelerate</s> Dora retro</h2>

One of the books that had bigger impact on me the most during these last years has been Accelerate, by <a href="https://twitter.com/nicolefv">Nicole Forsgren Phd</a>, <a href="https://twitter.com/jezhumble">Jez Humble</a>, <a href="https://twitter.com/RealGeneKim">Gene Kim</a>, so I decided to prepare a book retro of it. Circumstantially, the Accelerate retro became the Dora retro, as a lot of the content was in the end extracted from the  <a href="https://www.devops-research.com/research.html">Dora research program</a> :). 

How to use it:
* You can download the retro material from <a href="https://drive.google.com/file/d/1e-3RE1AlAaDl9mv5j5nf_3Ao-jrkpyIl/view?usp=sharing" download>here</a>. This post explains the motivations and rationale behind the retro and its activities, is meant for the facilitator. The material is meant to be shown to all participants during the session.
* The retro focuses mostly on technical aspects of Software Development, so in our case we did it while our PM was on holidays
* The exercise doesn't necessarily need to be done as a retro. You can do it anytime and you can set it up to gather experiments for the next week or goals for the next quarter, up to you. 
* As somebody already noticed, it may remind you of <a href=https://engineering.atspotify.com/2014/09/16/squad-health-check-model> the spotify squad health check model</a>, which they suggest to do on a quarterly basis, that could be an option too. I was not aware of such model when I created the retro, but thanks anyway to <a href=https://twitter.com/henrikkniberg>Henrik Kniberg</a> and <a href=https://twitter.com/klindwall>Kristian Lindwall</a>, I shamelessly have borrowed part of your model to improve the second exercise ;).

<h4>Ice breaker + Prime directive</h4>
I always start my retros with an <mark>Ice breaker</mark> because I want people to clean their slates when entering a retro. Ice-breakers help people disconnect with what they were doing 5 minutes before entering the retro and that's very valuable as it usually lightens the mood and allows for better perspective during the exercise.

After the ice breaker and before getting our hands dirty we read the <mark>prime directive</mark>, it never hurts.

Feel free to skip both steps.

<h4>What is Dora?</h4>
Dora is a company that was founded by the authors of Accelerate (and also authors or coauthors of "Continuous Delivery", "Lean Enterprise", "The DevOps Handbook", "The Unicorn Project" and "The Phoenix Project" - they are all excellent reads). Dora focuses on DevOps and helps companies improve their organizational performance (including Google, I guess, as they acquired at the end of 2018).
<br><br> 

I think it's worth reflecting on the fact that you could understand DevOps as <i>a way to improve collaboration between Dev and Ops</i>, but we should not forget that the whole motivation behind improving their collaboration is because that improves organizational performance (what we are really looking for and what DevOps is implicitly becoming the term for).

Dora annually publishes the <a href="https://www.devops-research.com/research.html#reports">State of DevOps report</a>, which gathers data from companies all-over the world. These reports are the outcome of their rigorous research on practices and capabilities of high performing tech orgs.

<h4>Retro goal</h4>
Reflect on their findings to see how we could improve.

<h3>Performance key metrics</h3>
The Dora research uses 4 key metrics to differentiate low, medium, high and elite performers. The 4 metrics are:
<ul>
<li> <b>Deployment frequency</b> - How often does the organization deploy to production</li>
<li> <b>Lead time for changes</b> - Time from code committed to production</li>
<li> <b>Time to restore service</b> - When an incident happens, time to restore service</li>
<li> <b>Change failure rate</b> - How often changes degrade service</li>
</ul>

While introducing this concept it's nice to justify <i>WHY</i> those 4 metrics were chosen (See chapter 2 of Accelerate for more info) and also to highlight their relationship with SW Development, SW Deployment and Service Operation.

<img src="/images/dora-retro/4-key-metrics-stages.png"/>


<h4>Activity I</h4>
<ul>
<li><b>Self-assessment</b> (5 min) - For each of those metrics, ask every team member to vote at which level do they think the team is now. This should be done hidden and in parallel, to avoid anchoring.</li> 
<li> <b>Discussion</b> (10-15 min) - For each key metric, reveal the votes and discuss the motivations behind them.</li>
<li> <b>Think time</b> (5 min) - Give every team member 5 minutes to think about experiments to improve based on whatever inspiration they have after the discussion. Experiments should be kept hidden until the next step.</li>
<li> <b>Pick one experiment</b> (10-15 min)- And only one!
</ul>


<h3>Predictive relationships</h3>
The studies from Dora have found a series of relationships between capabilities and outcomes. Those relationships are <mark>positive predictive</mark> meaning that the existence or practice of the element on the origin has a positive impact on the destination element. 
The best way to explain this is by opening <a href="https://www.devops-research.com/research.html#reports"> Dora's animated diagram</a> and playing around.

<img src="/images/dora-retro/Dora-diagram.png"/>

Given the diagram I'd like to share these insights:
* Organizational performance (probably the most interesting <i>bubble</i> for your organization) only has 3 predictors: "Lean product development", "Culture and work environment" and "Software delivery & operational performance". So, if you want to improve your organization, that's where you should put your efforts.
* You are now in a retro, good for you because you are investing in "Culture and work environment" which as you already know impacts organizational performance :)
* Continuous Delivery looks like an interesting topic (one arrow in, five arrows out, pretty good ratio!). Only by working on "Technical practices" you will have a positive impact on "Culture and work environment", "SW delivery & org. perf." (note the importance of these two dues to the previous statement), "Less burnout", "Less deployment pain" and "Less rework". Who wouldn't want to improve on all those things?

So... since this is a technical retro and improving on Continuous Delivery will have such an awesome impact, let's take a look at Continuous Delivery technical practices.

<h4>Activity II</h4>
<ul>
<li><b>Describe the practices</b> (10 min) - Continuous Delivery is composed of 12 technical practices, explain them to the team so everyone understands what they will have to assess</li> 
<li><b>Self-assessment</b> (5 min) - For each of those practices, ask every team member to vote at which level do they think the team is now. This should be done with hidden votes again. Feel free to use the table underneath</li> 
<li> <b>Discussion</b> (10-15 min) - For each technical practice, reveal the votes and discuss the motivations behind them</li>
<li> <b>Think time</b> (5 min) - Give every team member 5 minutes to think about experiments to improve based on whatever inspiration they have after the discussion. Experiments should be kept hidden again until picking time</li>
<li> <b>Pick one experiment</b> (10-15 min) - And only one!
</ul>

<img src="/images/dora-retro/cd-practices-exercise.png"/>

<h4>Fist of five + Feedback</h4>
So, you should have now 2 experiments for your next sprint, one inspired by the 4 key metrics and the other by the CD technical practices. It's time to take 2 minutes to reflect on the retro. I like to do a fist of five and ask for feedback on how to improve in the future.

Specifically for this type retro, I also like to have a small conversation on:
* Have you learnt anything new?
* Any special interest in one of the topics discussed?
* Has the shared understanding of the team improved?

And that's all, thanks for the patience and have a nice day :),

Xavi


Credits: Thanks <a href="https://twitter.com/josecgil">José Carlos Gil</a>, <a href="https://twitter.com/Aitortxu">Aitor Alzola</a> for reviewing and feedback.
