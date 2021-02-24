# How We Work

We employ agile practices to perform our work. Most importantly we use OKRs (probably one of the most critical framework we use) to set our Objectives and Key Results. We also use SCRUM for our development iterations.

Please, have a look at the SCRUM guide [here](https://www.scrumguides.org/docs/scrumguide/v2017/2017-Scrum-Guide-US.pdf#zoom=100)

## Sprints (Cycles)

We work in 2-week sprints at QBeat. This fixed cadence serves to give us an internal sense of urgency, work as a scope hammer to keep projects from ballooning, and provide a regular interval to decide what we’re working on.

The idea is not that everything we ever decide to work on has to take two weeks or can be completed in that time. But rather that we think about how we can break big projects into smaller ones that can be done in that amount of time, and that we bundle smaller things into a presentable scope of work that can be discussed.

This is particularly important for the product teams. Here we like to designate the work we take on with the scope in mind up front. We think of a small feature as a 1-weeker or a big feature as a 6-weeker (or anything in between). This designation helps us avoid a 1-weeker snowballing into a 4-weeker, just because people keep piling on more scope. Work is thus limited by a budget, and the budget focuses our discussion about what's reasonable and what's not. When a project starts slipping on its budget, the first approach should be to judo the problem and scope hammer the domain – and certainly not make it up by working more hours! Most things we work on can fit within one to four sprints (1 week - 2 months).

## Definition of Done

To increase transparency and to be open as a company, we have a definition of Done, as proposed in the Scrum Guide. This definition, helps us understand each other when we say that something is done. This is a living document/artifact.

### Definition of Done for Task (DoDT)

1. Working code
2. UT with coverage >= 80% (including memory leaks tests when applicable)
3. No findbugs warnings
4. No check style warning
5. Documentation
6. No failed tests
7. Commit and Push

### Definition of Done for Review (DoDR)

1. DoDT
2. Effective code
3. Follows our coding standards (code readability, code organization, good practices)
4. No failed tests after review

## Communication

It’s hard to keep up on what everyone is doing and what it means, if you just watch the stream of latest activity scrolling along in QBeat. (It’s also a waste of time and source of stress to even try.) Instead, we have four chief mechanisms for keeping everyone in the loop about the work that’s going on, and our weekly checkpoint.

First, we have the *Daily standup*. During the daily standup, which happens on a daily basis, we answer three questions:

* What did you achieve yesterday?
* What will you do today?
* Are there any impediments that prevent me from doing my work?

The what did you achieve question, supplies the nitty gritty details, but as a personal narrative. They’re a great conversation starter if you see someone working on something you either care about or want to learn more about. Please do use them as such!.

Second, there are the Sprint Review. These are the team versions of What did you work on the previous Sprint? This is where we summarize and celebrate the work that's been done. Every team lead is obliged to write, or designate someone on the team to write, this account at the last day of each iteration.

Third, there is the Sprint Retrospective. This is a formal opportunity for us to reflect on:

* What did we did well?
* What we did not do well?
* What is holding us back? How can we improve?

Fourth, there is the Sprint Planning. These are the team version of What are you going to work on next Sprint? This is where the plan for the coming two weeks is presented. Every team lead is obliged to write, or designate someone on the team to write, this account on the start of the new cycle.

Fifth, and finally, there’s the checkpoint (weekly question) of What will you be working on this week?, which details your intentions for the coming week.

These mechanisms work together to free individuals and teams to run their days and Sprints with confidence and independence. We make our big decisions about what to work on, and the rest of the time should chiefly be spent carrying out those short-term plans. By having clear expectations for communication, it's easier for everyone to build trust in where we're going and why.

All these questions and write-ups will be posted in the What Works project for the current year.

## Pitches

Whether you work on the product development or not, your voice and observations can help determine what we should be working on. The way to exert this influence is through pitches.

Write-up your idea of a new feature, a change to a feature, or any other product development you think we should be considering as a fully considered post (the more specific, the better). This gives the whole company a chance to consider and respond to the idea, and then we'll have the idea encapsulated in a post, available for reference at any time.

There'll always be more pitches than we have time to field, though. So it's important to have realistic expectations about what will happen after you posted your pitch. The default is simply that everyone involved with product development (and probably most everyone else in the company) will read and consider your pitch. That's a win right there. Even if the full pitch doesn't make it in, it can impact other product decisions by shining light on a weak point.

While a few pitches might instantly strike a chord loud enough to go on the plate for the next Sprint, it's more likely that your pitch will sit for a while first. There are always more ideas than time, and we can only get a few things done each Sprint. So chances are that even if everyone agrees the pitch is a great idea, it might not be the next most important thing for us to tackle. Don't be discouraged by this. We've had many pitches that have sat for many iterations, if not years, before finally coming together and then happening.

## In self-organizing, cross-functional, independent teams

Organizational theory is thick with descriptions of the trade-offs between functional and project company structures. We seek to be more project than functional. This means a single project team should be able to go from idea to deploy as independently as possible.

Thus, the fewer other departments a team has to pass through on their road to rolling out a new feature, the better.

For example, a native feature that requires an API change should be carried out by that native team directly.

When we need to use the staging database, that should be self-service too. Have a script anyone can run to restore it. Don’t require going to ops and waiting around for someone to do it for us.

None of this means we can’t talk together or ask experts with more experience or expertise for their advice. It just means it shouldn’t be a required, necessary step to make QBeat better.

## With managers of one. The whole team is autonomous

While we do have more senior people in each team, and each team is autonomous, we rely on everyone at QBeat to do a lot of self-management and lead the way. People who do this well qualify as [managers of one](https://signalvnoise.com/posts/1430-hire-managers-of-one), and we strive for everyone senior or above to embody this principle fully.

That means setting your own direction when one isn't given. Determining what needs to be done, and doing it, without waiting for someone to tell you to. A manager of one will spend their time well when left to their own devices. There's always more work to be done, always more initiatives to kick off, always more improvement to be had.

## Balanced

We limit ourselves to a 40-hour work week. Keeping our hours at work limited forces us to prioritize the work that really matters. A healthy amount of sleep and a rich and rewarding life outside of work should not be squandered for a few more hours at work.

There are occasions where teams or individuals need to work off-hours for on-call, maintenance or emergencies. This time should not be in addition to your normal working hours. Use your discretion to take time off to make up for the additional hours you put in during the week.
