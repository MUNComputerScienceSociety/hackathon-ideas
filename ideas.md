# List of Ideas

This document lists ideas for projects for a future hackathon hosted by the MUN CS Society.
It should use [markdown syntax](daringfireball.net/projects/markdown/) to format the list
and paragraphs.

## Goal

The MUN CS Society has hosted two hackathons in recent years- one where we worked on the
ABA Lookup project and an Aaron Swartz Memorial Hackathon. Both events were rather
well received, but in both cases participants lacked the direction that would enable
them to contribute greatly to a project.

By starting and opening up a discussion about ideas for projects early, we may be able to
flesh out a number of projects that could be adopted by groups during a hackathon.
The time between now and whenever a hackthon is held should be used to brainstorm
ideas, discuss their use cases/applications, document the problems the project
should solve and how it can be developed, and possibly begin implmeneting each
idea. We want to leave projects open-ended so that hackathon participants can
have fun and be creative, but also try to provide as much scafolding as possible
to make participants as productive, and thus involved, as we can.

## Ideas

1. A quiz system for first/second year courses.
2. A reimplementation of the project submission utility.
3. An API to a lot of parts of the MUN site.
4. A graduation progress tracker.

## Explanations

### 1. Quiz System

A lot of first year courses use quiz systems like
[LON-CAPA](https://homework.math.pitt.edu/adm/login?domain=pitt)
and [Mastering Chemistry](https://homework.math.pitt.edu/adm/login?domain=pitt)
to automate student testing and grading either in place of or along with
written assignments.  Many students do not want to have to pay a fee for access
to some of these services, but professors do not have the resources to grade
hundreds of quizes every week.  Building a quiz system that could replace such
services which allows professors to write or generate their own questions
is not unlikely to see adoption.

### 2. Reimplementation of Submission Script

Historically, a command-line submission script has been used to submit
projects and assignments to professors in the Computer Science department.
Building a better tool with a more friendly UI and a more solid/useful
backend (perhaps using Git) would likely speed up the adoption of more
usable and modern technologies in the department.

### 3. A MUN API

There are many components that comprise the Memorial site, including D2L,
my.mun.ca, self-serve, as well as the individual pages maintained by
professors personally or for individual courses.  New solutions are
contstantly being appended to the existing structure, adding more and
more complexity as time goes on.  To eliminate the need for third-party
applications to bring parts of this information together, an API could
be built to provide access to as many of these sources of information
as possible, making it easier to develop more cohesive applications that
integrate naturally into the existing infrastructure.

### 4. Graduation Progress Tracking

Keeping track of the requirements a student must fulfill in order to
graduate can be somewhat painful due to the strucutre of self-serve
and the density of the information in the university calendar.
Providing students with a simple interface to help them track their
progression towards graduating would make it substantially easier to
plan for upcoming semesters. Software such as this could be extended
to automatically populate a set of requirements based on a specified
degree type (e.g. [B.Sc, Major in Comp. Sci, Minor in Math]), and
could also potentially make course suggestions referrencing annual
offerings using the API mentioned above.
