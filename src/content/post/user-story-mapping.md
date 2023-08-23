---
publishDate: 2022-10-5T00:00:00Z
title: Using and abusing “User Story Mappings”
excerpt:  Some reflections on how we used User Story Mappings at LIFULL Connect to plan and track a couple of projects
image: ~/assets/images/blog/user-story-mapping/user-story-mapping.png
tags:
  - LIFULL Connect
  - User Story Mapping
---

<h2>Our first User Story Map</h2>

Some months ago, when I was working in <a href ="https://www.lifullconnect.com/">LIFULL Connect</a>, our team was working on a project to be able to measure the volume of conversations that take place due to an interest of a user on a Real estate listing using instant messaging applications (like WhatsApp, Line, Viber).

We had implemented a Lean proof of concept (PoC) which demonstrated the viability and potential of the idea, and were transitioning towards building the “real thing”. Thanks to the PoC learnings, the next steps were clear in our minds but we didn’t feel comfortable dumping a bunch of tickets in our JIRA because:
<ul>
    <li>We only created tickets for stuff we planned to do soon or very soon</li>
    <li>Had we dumped all those tickets, it would have been hard for us to see what was the current state of the project as we only had a Kanban with 4 columns (Backlog, To do, In Progress, Done)</li>
    <li>We wanted to be able to talk about project stages (Walking Skeleton, MVP and more) and they were hard to represent in JIRA</li>
</ul>

At that moment in time, I had recently finished reading <a href="https://www.oreilly.com/library/view/agile-technical-practices/9781838980849/">Agile Technical Practices Distilled</a> from <a href="https://twitter.com/pedromsantos">Pedro M. Santos</a>, <a href="https://twitter.com/consolondon">Marco Consolaro</a> and <a href="https://www.linkedin.com/in/alessandro-di-gioia/">Alessandro Di Gioia</a> and there’s a chapter in the book called “Understand the Business” which explains multiple techniques that can be used to … well, understand the business 😜. Among the techniques there’s User Story Mapping (surprise!) so I proposed to experiment with it in one of our weekly retrospectives and the team embraced the idea.

User Story Mapping is a technique developed by Jeff Patton who defines it as:

<mark>A dead simple idea. Talk about the user’s journey through your product by building a simple model that tells your user’s story as you do.</mark>

So, after documenting ourselves a little bit on how to do a User Story Mapping, we built our first one which ended up becoming something like this (sorry, blurred for privacy):

<img src="images/user-story-mapping/our-first-user-story-map.jpeg"/>

<img src="public/images/user-story-mapping/our-first-user-story-map.jpeg"/>

Let me explain the process which lead us to this diagram:

<ol>
    <li>Backbone definition — The backbone is the journey of the user and, since User Story Maps put the user at the center of the mapping experience, we started by creating the backbone cards and their actors</li>
    <li>Cards definition — We then had a brainstorming session where everyone in the team created cards with the different tasks we thought had to be accomplished to finish the project. Of course, we had plenty of repeated elements and some nuances with the granularity levels, it wasn’t hard to merge and clean-up afterwards and we did our best not to forget anything</li>
    <li>Sorting and prioritization — Once all the cards were agreed upon, we then sliced the project in the different phases which we called Walking Skeleton, MVP and Growing the feature.</li>
</ol>

The outcome was a User Story Mapping pretty similar to the one in the image. Obviously, we missed stuff, learnt new things and changed opinions which had impact on the diagram, but it was very easy to keep it updated.

Some of the benefits we got from that User Story Mapping were:
<ul>
    <li>Clarity on the status of the project both for Product and Tech stakeholders from inside and outside the team (it’s very easy to read for everyone, we barely had questions when we shared it outside our team without more explanation than the link itself)</li>
    <li>Very smooth way to discuss and manage expectations on what feature could be delivered and when</li>
</ul>

<h2>(Ab)use</h2>
So, after a couple of months we were done with tracking leads via an Instant Messaging solution and moved into another project, this one about how to display information of our Leads. Again, we were faced with the complex conversation of discussing a set of features and projecting them at multiple levels (delivery dates, what could be defined as minimum for the MVP, how could different features be phased to be more efficient, constraints due to communication with customers — for example, releasing to production in small batches wasn’t an option due to communication costs, …).


After our success with the previous project, we (ab)used User Story Mapping to organize our ideas. Why do I say we abused it? Because we skipped the Backbone and the Actors discussion, and we organized the map in columns by products/technologies involved in the project. In that case we ended up with something like this:
<img src="images/user-story-mapping/component-based-user-story-mapping.jpeg"/>

I know that we were probably anchored in an implementation idea and the User Story Mapping was heavily influenced by that, also that we are partially defeating the purpose of the exercise of having the user in the centre. As an argument to justify why we did it, I would like to say that the idea came from a previous discussion/analysis were multiple alternatives were considered. Based on that, we knew we had a heavily preferred option and we had high hopes that it would work (still, we started reducing risks with a walking skeleton).

I think it’s worth saying that the discussion came up very naturally to us, and that Product team felt comfortable with the approach, not only on the early days of the project but also during the project evolution.

<h2>My take</h2>
With my current experience, User Story Maps help a lot managing projects like the ones we had when I was in LIFULL. As a tool it’s really helpful, even if you don’t do them “by the book”. Note I don’t mean to say that the book is very prescriptive (I’m half-way through :shame:), just that we took a libertarian approach to it at some moments and it worked for us. I expect to continue using them or variants sometime soon :).

<h2>More info</h2>
<ul>
    <li>Jeff Patton “User Story Mapping” <a href="https://www.amazon.com/dp/1491904909/ref=cm_sw_r_as_gl_api_glt_fabc_943R88XEDXR0C93EARN1?linkCode=ml1&tag=jefpatass-20">book</a></li>
    <li>Jeff <a href="https://www.jpattonassociates.com/story-mapping/">website’s</a> is also full of related resources</li>
</ul>


Credits: Thanks <a href="https://www.linkedin.com/in/guidolavecchia/">Guido Lavecchia</a>, <a href="https://www.linkedin.com/in/mjtordesillas/">Manu Tordesillas</a>, <a href="https://www.linkedin.com/in/jes%C3%BAs-sp%C3%ADnola/">Chus Spínola</a> and <a href="https://twitter.com/d_asensio">David Asensio</a> for embracing and <a href="https://www.linkedin.com/in/eduardmateu/">Edu Mateu</a> for reviewing.