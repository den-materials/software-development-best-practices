![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png)

<!--9:04 WDI4 -->
<!--9:05 -->
<!--9:00 10 minutes -->

# Software Development Best Practices

<!--Hook... As another teacher once said to me, "Being a developer is about managing two types of communication: communication with this computer in front of me, and communication with other people."   For those who get into this line of work to avoid dealing with people, I have bad news for you: the best developers have solid inter-personal communication skills.  I have worse news for you: this is only becoming more true as time goes on. -->

### Why is this important?
<!-- framing the "why" in big-picture/real world examples -->
*This workshop is important because:*

 - Well-planned projects with flexible processes are more enjoyable to work on and turn out better. In the following workshop we will discuss how to plan appropriately and follow some best practices.
 - There are numerous roles like *Agile Coach* or *Scrum Master* that you may serve in, either as a full-time position, or as part of your responsibilities as a developer.

### What are the objectives? 
<!-- specific/measurable goal for students to achieve -->
*After this workshop, developers will be able to:*

- **Compare** and contrast several development methodologies
- **Define** features as user stories
- **Inform** a UI with mockups
- **Conduct** a scrum

### Where should we be now?
<!-- call out the skills that are prerequisites -->
*Before this workshop, developers should already be able to:*

* **Have** projects in the planning phase

<!-- 9:11 -->
<!-- 9:10 5 minutes-->
## Waterfall Methodology

![waterfall](https://i.imgur.com/yJMVO91.png)

Waterfall is a good example of a linear methodology in which the project's progress steady flows down from one team to another. It's "easy" to manage due to the rigidity of the model.

### Consequences...

...

> What tends to happen to new projects in waterfall organizations?

<!-- CFU think-group-share ^^^^  ^^^^^ -->

<!-- 9:17 -->
<!--9:16 WDI4 -->
<!-- 9:15 10 minutes -->
## Agile Methodology

_**Agile software development** is a group of software development methods in which requirements and solutions evolve through collaboration between self-organizing, cross-functional teams. It promotes adaptive planning, evolutionary development, early delivery, continuous improvement, and encourages rapid and flexible response to change_- [Wikipedia](http://en.wikipedia.org/wiki/Agile_software_development)

The [Agile Manifesto](http://www.agilemanifesto.org/) is a formal "proclamation" of key values for approaching software development put together in 2001. Let's discuss its core [12 principles](http://www.agilemanifesto.org/principles.html):

* Our highest priority is to **satisfy the customer**
through early and **continuous delivery
of valuable software**.

* **Welcome changing requirements**, even late in 
development. Agile processes harness change for 
the customer's competitive advantage.

* **Deliver working software frequently**, from a 
couple of weeks to a couple of months, with a 
preference to the shorter timescale.

* Business people and developers must **work 
together** daily throughout the project.

* Build projects around **motivated individuals**. 
Give them the environment and support they need, 
and trust them to get the job done.

* The most efficient and effective method of 
conveying information to and within a development 
team is **face-to-face conversation**.

* **Working software** is the primary measure of progress.

* Agile processes promote **sustainable development**. 
The sponsors, developers, and users should be able 
to maintain a constant pace indefinitely.

* Continuous attention to technical excellence 
and **good design** enhances agility.

* **Simplicity**--the art of maximizing the amount 
of work not done--is essential.

* The best architectures, requirements, and designs 
emerge from **self-organizing teams**.

* At regular intervals, the team **reflects on how 
to become more effective**, then tunes and adjusts 
its behavior accordingly.

<!-- CFU: Stop and Jot, choose three words that describe Agile Software Development to you.  -->

<!--9:30 -->
<!--
<!-- 9:25 10 minutes-->

## Best practices

#### Satisfy the Customer

* **User stories** define the features an application will provide in a simple and concise way.

* **Wireframes** define the user interface of the application.

#### Deliver Working Software

* **Pair programming** is a development technique in which two programmers work on a specific problem together.

* **Test-driven development** improves code design and quality.

### Work Together

* **Scrum meetings** are short meetings used to plan, review, and increase accountability and clarity across a team.

* **Sprints** are set periods of time (usually days or weeks) in which a set amount of work is to be completed and delivered.

* **Retrospectives** are periods for reflection at the end of each sprint.

<!--CFU: Catch-phrase with these 7 phrases -->

<!--9:36 WDI4 but no catch phrase yet -->
<!--Actually 9:40 -->
<!-- 9:35 10 minutes-->

## User Stories

### How do I know what the client wants?

When you meet with the client, translate all the features that you discuss into **user stories** following the format:

**A user *(specified type optional)* can [GOAL], so that [PURPOSE]**

For example:

- _A user **can** read reviews of a book (**so that** they are better informed when making a purchase)._
- _An admin **can** update the inventory of a book **so that** the buyers know what is available._

### How can I make an accurate time and budget quote on a project?

As a user story complexity increases linearly, its time to complete it will increase geometrically. As a result, when weighing each user story's relative complexity, assign it a [Fibonacci number](https://en.wikipedia.org/wiki/Fibonacci_number) that corresponds to the relative time it will require. This is called the **point system** and is a great way to budget time and money.

**[1, 2, 3, 5, 8, 13, 21]**

corresponds to:

**[easiest, easier, easy, moderate, hard, harder, hardest]**

*Note: If something is ever bigger than 21 points, consider breaking it down into smaller user stories.*

Once all the user stories are assigned points, it is possible to start estimating how many points can be completed in a given period of time. A **sprint** is a period of predefined time, typically 1-2 weeks, during which teams aim to complete a set of user stories. The team initially estimates how many points is realistic to accomplish during the a sprint. Once the team completes a sprint, they can measure the rate of points completed in a given of time, or their **velocity**. Knowing the current and average velocities of the team, allows for more accurate projections into the future. 

A collection of user stories will contain an overall point score.

<!--CFU Make user stories for tic-tac-toe on post-its, Order the post-it notes, then put numbers on them -->

<!--9:49 -->
<!--WDI4 10:04 -->
<!-- 9:45 10 minutes-->
### What tools should I use to do this?

Head to [Trello](https://trello.com), make a new board, and create three lists: "To Do", "Doing", and "Done".

<figure>
  <img src="imgs/user-stories.png" alt="Kanban-style user stories">
  <br>
  <figcaption>Kanban-style user stories</figcaption>
</figure>

For each user story it is possible to break it down into sub tasks.

<figure>
  <img src="imgs/story-tasks.png" alt="user story tasks">
  <br>
  <figcaption>A user story's tasks</figcaption>
</figure>

> Challenge: Write an example user story for the game you are planning to build for Project 1.

<!-- 9:58 -->
<!--10:13 WDI4 -->
<!-- 9:55 5 minutes-->
## Wireframes

Wireframes illustrate how the user **navigates** to and **interfaces** with **information** presented to them.

Having user stories will better inform wireframes, while having wireframes will help further refine the user stories. They are very complementary.

Can the user intuitively **navigate** through the experience and **interface** with the **information** presented to them?

<figure>
  <img src="http://3.bp.blogspot.com/-8e_J8hkX_kM/TbSz0jywljI/AAAAAAAAAY4/Nei-hnfPGaI/s1600/Balsamiq+myTube+example.jpg" alt="example wireframe">
  <br>
  <figcaption>An example wireframe</figcaption>
</figure>

If you are looking for a wire-framing tool, there are a few big ones available online:
* [Wireframe.cc](https://wireframe.cc/)
* [Balsamiq](https://balsamiq.com/products/mockups/)
* [Moqups](https://moqups.com/)
* [InVision](https://www.invisionapp.com/)

<!--10:00 -->
<!--10:00 5 minutes -->

## Pair Programming

The practice of pair programming is cited to: **improve code quality** through an increase in communication, **facilitate team cohesion** through collective code ownership, **improve long-term velocity** through a reduction in errors made, in addition to other benefits!

One programmer, the driver, writes code while the other, the navigator, reviews each line of code as it is typed in. The two programmers switch roles frequently.

![pair programming](http://i.imgur.com/cdiZYib.jpg)

Checkout [how Atlassian does it](https://www.youtube.com/watch?v=dYBjVTMUQY0)

<!--10:05 -->
<!-- 10:05 5 minutes-->

## TDD

Test driven development will improve the design and quality of the code written. It follows the cycle:

![tdd flowchart](https://raw.githubusercontent.com/sf-wdi-26/modules/master/w08/d02/m3-testing-w-jasmine/img/tdd-flowchart.png)

*Note: pair programming and TDD can work well together in a [ping pong pattern](http://c2.com/cgi/wiki?PairProgrammingPingPongPattern).*

<!-- Bring up mocha spec from Iterators lab -->

<!--10:09 - didn't bring up mocha -->
<!-- 10:10 5 minutes-->

## Scrum

Similar to rugby, a **scrum** is when a team quickly groups up in an effort to "self-organize". It is recommended to keep the scrum as *short as possible*. Agree on a duration of about 5-15 minutes. Scrums are typically conducted at the very beginning of every day additionally as needed (e.g. afternoon and the end of the day). A standard format is to go around in a circle and for each person to answer the following questions:

* What user stories did you complete yesterday?
* What user stories are you working on today?
* Do you have any blockers?

*Note: a blocker is anything that has completely inhibited you from moving forward.*

> Conduct a scrum on Project 1 at your tables

<!-- 10:19 -->
<!--10:34 WDI4 -->
<!-- 10:15 5 minutes-->
## Retrospective

At the end of each sprint a team will conduct a **retrospective** in an effort to "become more effective". There are [numerous formats](http://retrospectivewiki.org/index.php?title=Retrospective_Plans) through which to [conduct a retrospective](http://www.funretrospectives.com/category/retrospective/); the four hats is a popular one.  

> You may see this pattern with more or fewer hats, for instance, the [six hats](http://retrospectivewiki.org/index.php?title=6_Thinking_Hats_Retrospective).

### The Three Hats

**Yellow Hat**

Participants can only talk about the **good things** that happened in the last iteration.

**Black Hat**

Participants can only talk about the **bad things** that happened, any negative criticism they have or worst case scenarios they can think of.

**Green Hat**

The discussion moves on to any **ideas** people have about solving problems or things that may add more value to the business or help in any way. Outside of the box helicopter view blue sky thinking is encouraged.

**Conclusions**

At this point, most teams take the time to formalize a few S.M.A.R.T. goals for their next sprint, based on all the restrospective information discussed.

*Specific, Measurable, Attainable, Realistic, Time-boxed

<!-- We will do this activity at end of Project 1 -->

<!--10:25 -->
<!--10:20 5 minutes -->

## Closing Thoughts

- How can writing user stories help manage our clients from a time and cost perspective?
- Name two processes a team can adhere to in order to improve the quality of the code produced.
- Assuming the use of TDD, how would a feature request get translated into working code?
- What's one thing a team can do to better self-organize and be more effective?

<!--CFU Think-pair-share--> 

<!--Actually end 10:33 -->
## Related Resources

* [Building an MVP](https://www.youtube.com/watch?v=1FoCbbbcYT8)

## Licensing
All content is licensed under a CC­BY­NC­SA 4.0 license.
All software code is licensed under GNU GPLv3. For commercial use or alternative licensing, please contact legal@ga.co.
