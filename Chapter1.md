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


