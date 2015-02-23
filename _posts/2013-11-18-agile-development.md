---
layout: post
title: Agile Development
---

*This post was originally published at Cask, a blog on digital project management.*

-----

### A very accurate and very scientific experiment
<br>
In a fun mini-experiment, I provided subjects with a hypothetical HipChat question to probe the source of my own confusion surrounding Agile. When asked, “_If you didn’t already know the words ‘Scrum’ and ‘Kanban,’ what would you think the words meant?_,” people at Barrel provided some hilarious word associations. From a sample size of six (a notable 300% increase from the first blog post), five associated the word “Scrum” with filthy-sounding words, such as “a bug, or fungus,” “something on the bottom of your shoe,” or the notably more specific “armpit dirt,” as suggested by Betty (I’m not quite sure what “armpit dirt” is).

<!-- more -->

As for “Kanban,” people nearly unanimously reported that the word sounds like a Japanese food item – perhaps a sweet pastry of sorts – except for Jessie, who thoughtfully interpreted the word as, “a turban that is in a can and expands with water like one of those towels idk.” I give Jessie points for being imaginative. However, the most scientifically interesting was Zack’s response. Perhaps at a loss for words, or simply feeling inspired, Zack instead offered a pictorial representation of what the word “Kanban” meant for him personally:

[![anpanmanbread](/assets/blog/anpanmanbread.jpg)](/assets/blog/anpanmanbread.jpg)_<div class="caption">Anpanman giving someone a piece of his mind.</div>_

What this very precise survey data and this Japanese anime character with a bean paste pastry for a head both suggest is that the Agile jargon is inherently confusing, misleading, and sometimes makes me hungry. Luckily, I’m able to watch the Barrel team practice Agile processes every day, so I’m gaining a much deeper understanding of the techniques involved and vocabulary used. This blog post documents my findings along the way.  
 

### Agile: iterative, incremental development methods
<br>
Before witnessing Agile in action at Barrel, I thought “Agile” was another programming language I didn’t know about, and “Scrum” could only be something akin to armpit dirt. Actually, Agile, Scrum, Kanban, and Waterfall all describe _process, _as they are ways to strategically organize software development workflow in order to address certain needs of the client and of the internal team. Scrum and Kanban exist within a larger Agile category, which also includes other methods such as Extreme Programming (XP), Crystal, and Lean. Agile is typically contrasted with Waterfall.

[![waterfall](/assets/blog/waterfall.png)](/assets/blog/waterfall.png)

Barrel projects used to follow more of this **Waterfall model**, meaning that the project, say a website redesign, progressed sequentially (like a waterfall) over the stages of Strategy, UX, Design, Development, and System Admin/QA/Training and proceeded to the next phase only when the previous one was completed and reviewed. Waterfall projects typically require extensive planning and documentation upfront in order to estimate scope, timetables, and budgets.

[![agile](/assets/blog/agile.png)](/assets/blog/agile.png)

**Agile**, on the other hand, describes software development methods that generate earlier working software prototypes through several time-boxed iterations completed by cross-functional teams. Simply put, rather than internally handing off the project from stage to stage with little communication across disciplines, Agile methods bring together members of each function to work together at every interval. Project deliverables are broken up into smaller, more manageable chunks and divided into shorter, fixed-duration **iterations** typically lasting a few weeks. By tackling one iteration at a time, the cross-functional teams can produce an earlier working product for the client and thus adapt to changing needs, even quite late in the game.  
 

_Key features of Agile:_  

- Early and continuous delivery of a working product that can adapt quickly to change
- Cross-functional, self-organizing teams meeting face-to-face on a daily basis over the course of short, time-boxed iterations
- Continuous client/stakeholder involvement and communication from the very beginning
- Tasks broken up and prioritized into increments that require minimal upfront planning

 
### What is Scrum?
<br>
At Barrel, we are attempting to implement more Agile methods in projects, with a general tendency toward Scrum. Scrum is one of the most popular Agile development frameworks in use today. Scrum not only follows Agile guiding principles but also comes with its own set of Scrum-specific roles and artifacts.

**Scrum Team**  
   
Scrum prescribes very specific roles to manage the various tasks involved in the process. Along with the **Development Team**, comprising cross-functional team members who create the deliverables, there is the **Product Owner**, who represents the client and ensures his or her needs are met. The **Product Owner **is in charge of prioritizing the features that the product needs to have in order to create a **Product Backlog** (described below).  


There is also a **Scrum Master **who facilitates the Scrum rules and ensures that the team reaches the sprint goals (iterations in Scrum are called **sprints**). Scrum Master typically leads daily scrums and ensures everyone has what they need to be productive during the workday.

[![ScrumLee](/assets/blog/ScrumLee.jpg)](/assets/blog/ScrumLee.jpg)_<div class="caption">Lee the Scrumlord – er, Scrum Master – leading one of our daily Scrums at our task board.</div>_
 

**Product Backlog and Planning Poker**  


I was really excited to hear that I’d be playing poker with the team during my first week at Barrel, and then I heard the rules of **Planning Poker**. Rule #1 of Planning Poker is that it’s not real poker.  

Planning Poker is an exercise used to help create the **Product Backlog**, a prioritized list containing all desired features or changes to a product. By simultaneously “playing” cards bearing the numbers 1, 2, 3, 5, 8, 12, 20, 40, and 100 (exact values vary), members of the team estimate the effort or uncertainty involved in realizing **user stories**.  

A **user story **is a sentence that captures a what users must be able to do while using the product. They typically follow the template “As a [role] I want [goal] so that [benefit].” For instance, here’s a user story for an app that Barrel is creating at the moment: “As an admin, I want to view all users, so that I can manage permissions of each user.”  

All members of the team consider a single user story and will make an estimate on the level of effort involved by playing a card – the higher the number, the greater the effort or uncertainty. A consensus is made to average, or if there are outstanding numbers played, those individuals will voice their concern about the kind of effort needed. By the end of planning poker, the user stories/features are placed on a graph to decide which of the user stories should be prioritized in the workflow. The Product Owner creates the Product Backlog from these graphed user stories, ordering them based on risk, ROI, date needed, etc. A **Sprint Backlog** is created for each sprint, using the top user stories on the main Product Backlog. During every sprint, the development team works to complete the tasks on the sprint backlog in the order they were arranged after prioritization.  
 

**Meetings**  

Every morning during what’s called our daily **Scrum**, everyone on the team gathers briefly for only about 15 minutes to answer three questions: _1) What have you done? 2) What are you going to do? and 3) Any needs/impediments to overcome in order to complete your tasks?_ Drawing from these daily updates, We often write out each task on Post-It Notes so we can visualize the workflow on a **scrum task board**. Each member of the team moves his or her own Post-Its from “To Do” to “In Progress” to “Verify” on the task board until they finally reach “Done.” Once the sprint wraps up, the team will reset the task board in preparation for the new sprint.  

At the end of each sprint, the team also assembles for both a **review meeting** to present to the client what was accomplished during the sprint (usually in the form of a working demo) and a **retrospective** in which members reflect on lessons learned and ways to improve for the next iteration.

   
**Metrics of Progress**  

One defining characteristic of Scrum is that progress can be measured and predicted by the team’s **velocity**, which is the total effort that a team can accomplish in a sprint. These estimates draw from the original Planning Poker numbers assigned to each task, then aggregated to give a target velocity for the entire sprint.

Our Scrum Master has been tracking our velocity using a **burn-down chart**, which shows Remaining Work/Effort Required over Time. Ideally, the graph shows a downward slope as the amount of work remaining decreases. The slope indicates a velocity, which can be used to estimate a final delivery date. It’s Agile because if the Scrum team doesn’t complete as many tasks as projected, it can adapt by restructuring future sprints. The Scrum team moves through sprint after sprint before finally delivering the product when all features on the Product Backlog have been addressed.

[![ScrumZack](/assets/blog/ScrumZack.jpg)](/assets/blog/ScrumZack.jpg)_<div class="caption">Zack, a true scrumbag if I’ve ever seen one.</div>_

<br>
### What about the Japanese bean pastries?
<br>
Scrum and Kanban are two implementations of Agile methodology, each with its own set of guiding practices. At Barrel, we practice quite a bit of Scrum and not so much Kanban (though as Agile methods attempting to achieve the same thing, there is much overlap between the two). We do use a task board for visualizing workflow, as in Kanban, though the rules of the Scrum task board are not exactly the same.   

One of the differences between the two is that in Kanban, there is a directly imposed limit on the numbers of tasks in queue, reducing the amount of Work in Progress (WIP). In Scrum, task items flow rather freely in the workflow, but the WIP is indirectly limited by the number of tasks set for each sprint/iteration. Kanban is also relatively less prescriptive (fewer rules to follow) than Scrum: time-boxed iterations, cross-functionality of teams, estimation/prioritization, and prescribed leadership roles are all optional in Kanban, and a Kanban board can take in more task items at any point as long as capacity is available. In Scrum, there must be time-boxed iterations with set tasks within each one, and there are assigned roles of Scrum Master and Product Owner.  
 

### Concluding Remarks
<br>
So far, I’d say we love Scrum and we love Agile at Barrel. I asked Kevin K. his opinion as a developer working on a big Agile project here, and his response was, I think, very positive: “SCRUM? Oh _yeah_, I’ve got a few choice words about Scrum!!” I was curious to hear more about his sincere and heartfelt appreciation for Scrum, but unfortunately, Kevin declined to comment further.  
   
Nathan, another developer on an Agile project, also offered a few choice words. “Agile is the only way I would ever run a software project,” said Nathan, whose fiery enthusiasm for Scrum, I’m sure, was suddenly audible in his keyboard strokes as he typed his response on HipChat. “It kind of seems like a common sense way to do it – writing out huge tech docs and planning 2 months ahead never really works out, but cutting it up into small, manageable chunks and dealing with them one piece at a time keeps things moving. Iteration all the way! Plus the whole agile philosophy of ‘working software is better than documentation’ makes so much sense to me.”  
   
(I would like to note here that Kevin and Nathan were _much_ too Agile to stop for a full interview for this blog, so focused were they on producing working software rather than allowing me to write documentation. Now _that’s_ Agile.)  
 

### Further “Reading”
<br>
TL;DR – I realize that the Barrel Agile method described here was lengthy and involved, and there is still a lot more to be discussed. Thankfully, there are helpful videos out there for those of you like me who don’t like to read or just don’t read good:  
 

**Videos**

- [Scrum in Under 10 Minutes](http://www.youtube.com/watch?v=XU0llRltyFM) – Actually the best and most concise Scrum overview I’ve found on the internet.
- [Explaining Scrum in Less Than 120 Seconds](http://www.youtube.com/watch?v=WxiuE-1ujCM) – For those of you who don’t like reading AND don’t like watching long videos.
- [I want to run an agile project](http://www.youtube.com/watch?v=4u5N00ApR_k) – And I want to pull all my hair out every time I watch this video.
- [The Downfall of Agile Hitler](http://www.youtube.com/watch?v=l1wKO3rID9g) – Dark programmer humor, showing how Hitler the Scrum Master would react if he discovered his team wasn’t abiding by the tenets of the Agile Manifesto. Probably not very informative, but pretty funny and very, very terrible.


**Agile Resources and Tools**

- [Kanban vs. Scrum](http://www.crisp.se/file-uploads/Kanban-vs-Scrum.pdf) – a PDF overview comparing Kanban and Scrum with very helpful visuals
- [Trajectory](http://apptrajectory.com/) – an app to help organize user stories
- [OnTime](http://ontimenow.com/) – Scrum software and digital task board
- [ProjectFlow](http://projectflowapp.com/) – Barrel’s own project management web app, which we’ve sometimes used as a task board