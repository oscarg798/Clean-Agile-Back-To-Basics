# Introduction to Agile 

In February 2001, a group of 17 software experts gathered in Snowbird, Utah, to talk over the deplorable state of software development. At that time, most software was created using ineffective, heavyweight, high-ritual processes like Waterfall and overstuffed instances of the Rational Unified Process (RUP). The goal of these 17 experts was to create a manifesto that introduced a more effective, lighter-weight, approach.

This was no mean feat. The 17 were people of varied experience and strong divergent opinions. Expecting such a group to come to consensus was a long shot. And yet, against all odds, consensus was reached, the Agile Manifesto was written, and one of the most potent and long-lived movements in the software field was born.

Unfortunately, once a movement becomes popular, the name of that movement gets blurred through misunderstanding and usurpation. Products and methods having nothing to do with the actual movement will borrow the name to cash in on the name’s popularity and significance. And so it has been with Agile.

Presented here are the fundamentals of Agile. Many have embellished and extended these ideas—and there is nothing wrong with that. However, those extensions and embellishments are not Agile. They are Agile plus something else. What you will read here is what Agile is, what Agile was, and what Agile will inevitably always be.

## History of Agile
The idea of choosing small intermediate goals and measuring the progress after each is just too intuitive, and too human, to be considered any kind of a revolution.

Scientific Management is a top-down, command-and-control approach. Managers use scientific techniques to ascertain the best procedures for accomplishing a goal and then direct all subordinates to follow their plan to the letter. In other words, there is big up-front planning followed by careful detailed implementation.

Scientific Management worked best for projects that suffered a high cost of change and solved very well-defined problems with extremely specific goals.

What process did we use during those days? It certainly wasn’t Waterfall. We had no concept of following detailed plans. We just hacked away on a day-to-day basis, running compiles, testing our code, and fixing bugs. It was an endless loop that had no structure. It also wasn’t Agile, or even Pre-Agile. There was no discipline in the way we worked. There was no suite of tests and no measured time intervals. It was just code and fix, code and fix, day after day, month after month.

I first read about Waterfall in a trade journal sometime around 1972. It seemed like a godsend to me. Could it really be that we could analyze the problem up front, then design a solution to that problem, and then implement that design? Could we really develop a schedule based on those three phases? When we were done with analysis, would we really be one-third done with the project? I felt the power of the concept. I wanted to believe it. Because, if it worked, it was a dream come true.

Apparently I wasn’t alone, because many other programmers and programming shops caught the bug too. And, as I said before, Waterfall began to dominate the way we thought.

It dominated, but it didn’t work. For the next thirty years I, my associates, and my brother and sister programmers around the world, tried and tried and tried to get that analysis and design right. But every time we thought we had it, it slipped through our fingers during the implementation phase. All our months of careful planning were made irrelevant by the inevitable mad dash, made before the glaring eyes of managers and customers, to terribly delayed deadlines.

Despite the virtually unending stream of failures, we persisted in the Waterfall mindset. After all, how could this fail? How could thoroughly analyzing the problem, carefully designing a solution, and then implementing that design fail so spectacularly over and over again? It was inconceivable6 that the problem lay in that strategy. The problem had to lie with us. Somehow, we were doing it wrong.

15. This is one of those strange coincidences that occur from time to time. There is nothing special about OO that makes it less likely to mix with Waterfall, and yet that meme was gaining a lot of traction in those days.

At the time, I was running a company named Object Mentor. We partnered with Kent to offer a five-day boot camp course on XP that we called XP Immersion. From late 1999 until September 11, 2001,16 they were a big hit! We trained hundreds of folks.

There were 17 of us. We have since been criticized for being 17 middle-aged white men. The criticism is fair up to a point. However, at least one woman, Agneta Jacobson, had been invited but could not attend. And, after all, the vast majority of senior programmers in the world, at the time, were middle-aged white men—the reasons why this was the case is a story for a different time, and a different book.

The 17 of us represented quite a few different viewpoints, including 5 different lightweight processes. The largest cohort was the XP team: Kent Beck, myself, James Grenning, Ward Cunningham, and Ron Jeffries. Next came the Scrum team: Ken Schwaber, Mike Beedle, and Jeff Sutherland. Jon Kern represented Feature-Driven Development, and Arie van Bennekum represented the Dynamic Systems Development Method (DSDM). Finally, Alistair Cockburn represented his Crystal family of processes.

The rest of the folks were relatively unaffiliated. Andy Hunt and Dave Thomas were the Pragmatic Programmers. Brian Marick was a testing consultant. Jim Highsmith was a software management consultant. Steve Mellor was there to keep us honest because he was representing the Model-Driven philosophy, of which many of the rest of us were suspicious. And finally came Martin Fowler, who although he had close personal connections to the XP team, was skeptical of any kind of branded process and sympathetic to all.

I don’t remember whether the magic happened on the first day or on the second. It seems to me it was toward the end of the first day. It may have been the affinity groupings that identified the four values, which were Individuals and Interactions, Working Software, Customer Collaboration, and Responding to Change. Someone wrote these on the whiteboard at the front of the room and then had the brilliant idea to say that these are preferred, but do not replace, the complementary values of processes, tools, documentation, contracts, and plans.

This is the central idea of the Agile Manifesto, and no one seems to remember clearly who first put it on the board. I seem to recall that it was Ward Cunningham. But Ward believes it was Martin Fowler.

On the other hand, perhaps it’s best that we never really know.

* Individuals and interactions over processes and tools.

* Working software over comprehensive documentation.

* Customer collaboration over contract negotiation.

* Responding to change over following a plan.

As the second day drew to a close, Ward volunteered to put up the agilemanifesto.org website. I believe it was his idea to have people sign it.

## AGILE OVERVIEW


How do you manage a software project? There have been many approaches over the years—most of them pretty bad. Hope and prayer are popular among those managers who believe that there are gods who govern the fate of software projects. Those who don’t have such faith often fall back on motivational techniques such as enforcing dates with whips, chains, boiling oil, and pictures of people climbing rocks and seagulls flying over the ocean.


These approaches almost universally lead to the characteristic symptoms of software mismanagement: Development teams who are always late despite working too much overtime. Teams who produce products of obviously poor quality that do not come close to meeting the needs of the customer.

## Charts on the Wall

So how does Agile aid this kind of management? Agile provides data. An Agile development team produces just the kinds of data that managers need in order to make good decisions.

Many people would disagree with that last paragraph. After all, the charts aren’t mentioned in the Agile Manifesto, nor do all Agile teams use such charts. And, to be fair, it’s not actually the charts that matter. What matters is the data.

Agile development is first and foremost a feedback-driven approach. Each week, each day, each hour, and even each minute is driven by looking at the results of the previous week, day, hour, and minute, and then making the appropriate adjustments. This applies to individual programmers, and it also applies to the management of the entire team. Without data, the project cannot be managed.19

# The First Thing You Know

What is the first thing you know about a project? Before you know the name of the project or any of the requirements, there is one piece of data that precedes all others. The Date, of course. And once The Date is chosen, The Date is frozen. There’s no point trying to negotiate The Date, because The Date was chosen for good business reasons. If The Date is September, it’s because there’s a trade show in September, or there’s a shareholders’ meeting in September, or our funding runs out in September. Whatever the reason, it’s a good business reason, and it’s not going to change just because some developers think they might not be able to make it.

At the same time, the requirements are wildly in flux and can never be frozen. This is because the customers don’t really know what they want. They sort of know what problem they want to solve, but translating that into the requirements of a system is never trivial. So the requirements are constantly being re-evaluated and re-thought. New features are added. Old features are removed. The UI changes form on a weekly if not daily basis.

This is the world of the software development team. It’s a world in which dates are frozen and requirements are continuously changing. And somehow in that context, the development team must drive the project to a good outcome.

## The Meeting

The Waterfall model promised to give us a way to get our arms around this problem. To understand just how seductive and ineffective this was, I need to take you to The Meeting.

It is the first of May. The big boss calls us all into a conference room.

“We’ve got a new project,” the big boss says. “It’s got to be done November first. We don’t have any requirements yet. We’ll get them to you in the next couple of weeks.”

“Now, how long will it take you to do the analysis?”

We look at each other out of the corner of our eyes. No one is willing to speak. How do you answer a question like that? One of us murmurs: “But we don’t have any requirements yet.”

“Pretend you have the requirements!” hollers the big boss. “You know how this works. You’re all professionals. I don’t need an exact date. I just need something to put in the schedule. Keep in mind if it takes any more than two months we might as well not do this project.”

The words “Two months?” burble out of someone’s mouth, but the big boss takes it as an affirmation. “Good! That’s what I thought too. Now, how long will it take you to do the design?”

Again, astonished silence fills the room. You do the math. You realize that there are six months to November first. The conclusion is obvious. “Two months?” you say.

“Precisely!” the Big Boss beams. “Exactly what I thought. And that leaves us two months for the implementation. Thank you for coming to my meeting.”

Many of you reading this have been to that meeting. Those of you who haven’t, consider yourselves lucky.

## The Analysis Phase

Of course, some things are obvious. We should be sizing the project and doing basic feasibility and human resources projections. We should be ensuring that the schedule is achievable. That is the least that our business would be expecting of us. Whatever this thing called analysis is, it’s what we are going to be doing for the next two months.

This is the honeymoon phase of the project. Everyone is happily surfing the web, doing a little day-trading, meeting with customers, meeting with users, drawing nice diagrams, and in general having a great time.

Then, on July 1, a miracle happens. We’re done with analysis.

Why are we done with analysis? Because it’s July 1. The schedule said we were supposed to be done on July 1, so we’re done on July 1. Why be late?

So we have a little party, with balloons and speeches, to celebrate our passage through the phase gate and our entry into the Design Phase.

## The Design Phase

We have a bit more resolution about software design. Software design is where we split the project up into modules and design the interfaces between those modules. It’s also where we consider how many teams we need and what the connections between those teams ought to be. In general, we are expected to refine the schedule in order to produce a realistically achievable implementation plan.

Of course, things change unexpectedly during this phase. New features are added. Old features are removed or changed. And we’d love to go back and re-analyze these changes; but time is short. So we just sort of hack these changes into the design.

If only we could pull this off one more time. If only we could just say we were done with implementation. But we can’t, because the thing about implementation is that is actually has to be done. Analysis and design are not binary deliverables. They do not have unambiguous completion criteria. There’s no real way to know that you are done with them. So we might as well be done on time.

## The Implementation Phase && Death march phase

Implementation, on the other hand, has definite completion criteria. There’s no way to successfully pretend that it’s done.20

20. Though the developers of healthcare.gov certainly tried.

It’s completely unambiguous what we are doing during the Implementation Phase. We’re coding. And we’d better be coding like mad banshees too, because we’ve already blown four months of this project.

Meanwhile, the requirements are still changing on us. New features are being added. Old features are being removed or changed. We’d love to go back and re-analyze and re-design these changes, but we’ve only got weeks left. And so we hack, hack, hack these changes into the code.

As we look at the code and compare it to the design, we realize that we must have been smoking some pretty special stuff when we did that design because the code sure isn’t coming out anything like those nice pretty diagrams that we drew. But we don’t have time to worry about that because the clock is ticking and the overtime hours are mounting.

Then, sometime around October 15, someone says: “Hey, what’s the date? When is this due?” That’s the moment that we realize that there are only two weeks left and we’re never going to get this done by November 1. This is also the first time that the stakeholders are told that there might be a small problem with this project.

You can imagine the stakeholders’ angst. “Couldn’t you have told us this in the Analysis Phase? Isn’t that when you were supposed to be sizing the project and proving the feasibility of the schedule? Couldn’t you have told us this during the Design Phase? Isn’t that when you were supposed to be breaking up the design into modules, assigning those modules to teams, and doing the human resources projections? Why’d you have to tell us just two weeks before the deadline?”

And they have a point, don’t they?

So now we enter the Death March Phase of the project. Customers are angry. Stakeholders are angry. The pressure mounts. Overtime soars. People quit. It’s hell.

Sometime in March, we deliver some limping thing that sort of half does what the customers want. Everybody is upset. Everybody is demotivated. And we promise ourselves that we will never do another project like this. Next time we’ll do it right! Next time we’ll do more analysis and more design.

I call this Runaway Process Inflation. We’re going to do the thing that didn’t work, and do a lot more of it.

## Hyperbole?

Clearly that story was hyperbolic. It grouped together into one place nearly every bad thing that has ever happened in any software project. Most Waterfall projects did not fail so spectacularly. Indeed some, through sheer luck, managed to conclude with a modicum of success. On the other hand, I have been to that meeting on more than one occasion, and I have worked on more than one such project, and I am not alone. The story may have been hyperbolic, but it was still real.

## A better way 

An Agile project begins with analysis, but it’s an analysis that never ends. In the diagram in Figure 1.4 we see the whole project. At the right is the end date, November 1. Remember, the first thing you know is the date. We subdivide that time into regular increments called iterations or sprints.21

The size of an iteration is typically one or two weeks. I prefer one week because too much can go wrong in two weeks. Other people prefer two weeks because they fear you can’t get enough done in one week.

## Iteration Zero

The first iteration, sometimes known as Iteration Zero, is used to generate a short list of features, called stories. We’ll talk much more about this in future chapters. For now, just think of them as features that need to be developed. Iteration Zero is also used to set up the development environment, estimate the stories, and lay out the initial plan. That plan is simply a tentative allocation of stories to the first few iterations. Finally, Iteration Zero is used by the developers and architects to conjure up an initial tentative design for the system based on the tentative list of stories.

Some folks take this to mean that Agile is just a series of mini-Waterfalls. That is not the case. Iterations are not subdivided into three sections. Analysis is not done solely at the start of the iteration, nor is the end of the iteration solely implementation. Rather, the activities of requirements analysis, architecture, design, and implementation are continuous throughout the iteration.

## Agile Produces Data

Pretty much zero, of course. That’s because software is not a reliably estimable process. We programmers simply do not know how long things will take. This isn’t because we are incompetent or lazy; it’s because there is simply no way to know how complicated a task is going to be until that task is engaged and finished. But, as we’ll see, all is not lost.

At the end of the iteration, some fraction of the stories that we had planned to finish will be done. This gives us our first measurement of how much can be completed in an iteration. This is real data. If we assume that every iteration will be similar, then we can use that data to adjust our original plan and calculate a new end date for the project (Figure 1.5).

This calculation is likely to be very disappointing. It will almost certainly exceed the original end date for the project by a significant factor. On the other hand, this new date is based upon real data, so it should not be ignored. It also can’t be taken too seriously yet because it is based on a single data point; the error bars around that projected date are pretty wide.

To narrow those error bars, we should do two or three more iterations. As we do, we get more data on how many stories can be done in an iteration. We’ll find that this number varies from iteration to iteration but averages at a relatively stable velocity. After four or five iterations, we’ll have a much better idea of when this project will be done (Figure 1.6).

## Hope Versus Management

Hope is the project killer. Hope is what makes a software team mislead managers about their true progress. When a manager asks a team, “How’s it going?” it is hope that answers: “Pretty good.” Hope is a very bad way to manage a software project. And Agile is a way to provide an early and continuous dose of cold, hard reality as a replacement for hope.

Some folks think that Agile is about going fast. It’s not. It’s never been about going fast. Agile is about knowing, as early as possible, just how screwed we are. The reason we want to know this as early as possible is so that we can manage the situation. You see, this is what managers do. Managers manage software projects by gathering data and then making the best decisions they can based on that data. Agile produces data. Agile produces lots of data. Managers use that data to drive the project to the best possible outcome.

## Managing the Iron Cross

Let’s start with the schedule. Let’s ask the stakeholders if we can delay the project from November 1 to March 1. These conversations usually don’t go well. Remember, the date was chosen for good business reasons. Those business reasons probably haven’t changed. So a delay often means that the business is going to take a significant hit of some kind.

On the other hand, there are times when the business simply chooses the date for convenience. For example, maybe there is a trade show in November where they want to show off the project. Perhaps there’s another trade show in March that would be just as good. Remember, it’s still early. We’re only a few iterations into this project. We want to tell the stakeholders that our delivery date will be March before they buy the booth space at the November show.

Many years ago, I managed a group of software developers working on a project for a telephone company. In the midst of the project, it became clear that we were going to miss the expected delivery date by six months. We confronted the telephone company executives about this as early as we could. These executives had never had a software team tell them, early, that the schedule would be delayed. They stood up and gave us a standing ovation.

You should not expect this. But it did happen to us. Once

## Adding Staff

In general, the business is simply not willing to change the schedule. The date was chosen for good business reasons, and those reasons still hold. So let’s try to add staff. Everyone knows we can go twice as fast by doubling the staff.

Actually, this is exactly the opposite of the case. Brooks’ law22 states: Adding manpower to a late project makes it later

Another factor, of course, is that adding staff is expensive. Often the budget simply cannot tolerate hiring new people. So, for the sake of this discussion, let’s assume that staff can’t be increased. That means quality is the next thing to change.

## Decreasing Quality

I’m sure you know that I’m going to tell you this is futile. Producing crap does not make you go faster, it makes you go slower. This is the lesson you learn after you’ve been a programmer for 20 or 30 years. There is no such thing as quick and dirty. Anything dirty is slow.

The only way to go fast, is to go well.

So we’re going to take that quality knob and turn it up to 11. If we want to shorten our schedule, the only option is to increase quality.

## Changing Scope

Stakeholders, if you need all these features then it’s going to be March. If you absolutely have to have something by November then you’re going to have to take some features out.”

“We’re not taking anything out; we have to have it all! And we have to have it all by November first.”

“Ah, but you don’t understand. If you need it all, it’s going to take us till March to do it.”

“We need it all, and we need it all by November!”

This little argument will continue for a while because no one ever wants to give ground. But although the stakeholders have the moral high ground in this argument, the programmers have the data. And in any rational organization, the data will win.

If the organization is rational, then the stakeholders eventually bow their heads in acceptance and begin to scrutinize the plan. One by one, they will identify the features that they don’t absolutely need by November. This hurts, but what real choice does the rational organization have? And so the plan is adjusted. Some features are delayed.

## Business Value Order

Of course, inevitably the stakeholders will find a feature that we have already implemented and then say, “It’s a real shame you did that one, we sure don’t need it.”

We never want to hear that again! So from now on, at the beginning of each iteration, we are going to ask the stakeholders which features to implement next. Yes, there are dependencies between the features, but we are programmers, we can deal with dependencies. One way or another we will implement the features in the order that the stakeholders ask.

## Here Endeth the Overview

What you have just read is the 20,000 foot view of Agile. A lot of details are missing, but this is the gist of it. Agile is a process wherein a project is subdivided into iterations. The output of each iteration is measured and used to continuously evaluate the schedule. Features are implemented in the order of business value so that the most valuable things are implemented first. Quality is kept as high as possible. The schedule is primarily managed by manipulating scope.

That’s Agile.

So that’s what Agile is, and that’s how Agile began. Agile is a small discipline that helps small software teams manage small projects. But despite all that smallness, the implications and repercussions of Agile are enormous because all big projects are, after all, made from many small projects.

With every day that passes, software is ever more insinuated into the daily lives of a vast and growing subset of our population. It is not too extreme to say that software rules the world. But if software rules the world, it is Agile that best enables the development of that software
