# List of Ideas

This document lists ideas for projects for a future hackathon hosted by the MUN CS Society.
It should use [markdown syntax](daringfireball.net/projects/markdown/) to format the list
and paragraphs.

## Goal

The MUN CS Society has hosted two hackathons in recent years- one where we worked on the
ABA Lookup project and an Aaron Swartz Memorial Hackathon. Both events were rather
well received, but in both cases participants lacked the direction that would enable
them to contribute to a project.

By starting and opening discussion on ideas for projects early, we may be able to
flesh out a number of projects that could be adopted by groups during a hackathon.
The time between now and whenever a hackthon is held should be used to brainstorm
ideas, discuss their use cases/applications, document the problems the project
should solve and how it can be developed, and possibly begin implmeneting each
idea. We want to leave projects open-ended so that hackathon participants can
have fun and be creative, but also try to provide as much scafolding as possible
to make participants as productive (and involved) as we can.

## Ideas

1. A quiz system for first (and some second)-year courses.
2. A reimplementation of the prject submission utility.
3. An API to a lot of parts of the MUN site.

## Explanations

> Quiz System

A lot of first year courses such as the physics, chemistry, and math courses use
quiz systems like [LON-CAPA](https://homework.math.pitt.edu/adm/login?domain=pitt)
and [Mastering Chemistry](https://homework.math.pitt.edu/adm/login?domain=pitt)
to automate student testing and grading either in place of or along with
written assignments.  Many students do not want to have to pay a fee for access
to some of these services, but professors do not have the resources to grade
hundreds of quizes ever week.  Building a quiz system that could replace such
services which allows professors to write or generate their own questions
is not unlikely to see adoption.

> Reimplementation of Submission Script

Historically, a very hard-to-use submission script has been used to submit
projects and assignments to professors in the Computer Science department.
Building a better tool with a more friendly UI and a more solid/useful
backend (perhaps using Git) would likely speed up the adoption of more
usable and modern technologies in the department.

> A MUN API

There are many components that compose the Memorial site, including D2L,
my.mun.ca, self-serve, as well as the individual pages maintained by
professors (personally) or for individual courses.  New solutions are
contstantly being appended to the existing structure, adding more and
more complexity as time goes on.  To eliminate the need for third-party
applications to bring parts of this information together, an API could
be built to provide access to as many of these sources of information
as possible, making it easier to develop more cohesive applications that
integrate more naturally into the existing infrastructure.