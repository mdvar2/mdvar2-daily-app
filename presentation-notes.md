# CareerLane Technical Presentation - Speaker Notes

**Presenter:** Nelisiwe Gwinya  
**Project:** CareerLane - A Job Application Tracker for Students and Early-Career Developers  
**Estimated Presentation Time:** 5-7 minutes

---

## Slide 1 - CareerLane: Title & Context
**Approximate Time: 40 seconds**

The idea for CareerLane came from an experience I had while applying for jobs. I received a call inviting me for an interview, but the position was not clearly specified.
Because I had submitted quite a number of job applications, I could not immediately remember which position I was being contacted about. At the same time, I did not want to ask in a way that made it seem like I did not even remember the position I had applied for.
That experience made me realise that there is a gap in how we keep track of our job applications, and that is where the idea for CareerLane came from.

## Slide 2 - Agenda
**Approximate Time: 20 seconds**

I will briefly explain the problem CareerLane is trying to solve, how the proposed workflow works, the technical and collaboration approach I have used so far, the project documentation and current risks, and finally the planned demo workflow and next steps.

## Slide 3 - The Problem
**Approximate Time: 45 seconds**

When you are actively looking for work, you may apply for several opportunities within a short period of time.
Each application can also be at a completely different stage. One might simply be a position you are interested in, another might have been submitted, another might have reached an assessment, and another might already be at the interview stage.
After some time, keeping track of all of this becomes difficult, especially when information is spread across emails, job platforms and personal notes.
CareerLane is therefore not trying to solve the problem of finding jobs. It focuses on keeping track of the opportunities you have found and the progress of your applications.

## Slide 4 - CareerLane Workflow
**Approximate Time: 50 seconds**

CareerLane uses a board-based workflow.
A board represents a job-search campaign, while each individual job application is represented by a card.
The application can then move through stages depending on its progress: Interested, Applied, Assessment, Interview, Offer or Rejected.
For example, if I have applied for a Software Developer Intern position and receive an assessment, that application would appear under Assessment. If I later receive an interview invitation, it would move to Interview.
Instead of relying on memory, CareerLane aims to provide one place where the user can immediately see where each application currently stands.

## Slide 5 - Key Technical Components
**Approximate Time: 40 seconds**

CareerLane is currently moving from planning into early implementation, so the technical components shown here are the tools I am currently using to manage and develop the project.
Git and GitHub are used for version control, including branches, commits and pull requests.
Asana is used for sprint planning, task management and progress tracking.
Google Workspace supports the project documentation and collaboration.
The GitHub repository contains the README, planning documents and architecture decisions.
The application itself has not yet reached the stage where components such as an API or database have been implemented.

## Slide 6 - Git & Collaboration Workflow
**Approximate Time: 40 seconds**

For version control, I follow a branch-based Git workflow.
Instead of making changes directly on main, I create a separate branch, make the required changes, commit them with a clear message and push the branch to GitHub.
From there, I create a pull request so that the changes can be reviewed before being merged into main.
This creates a clearer history of what changed and how those changes entered the project.

## Slide 7 - Documentation & Project Decisions
**Approximate Time: 40 seconds**

Documentation has also been an important part of CareerLane.
The README provides an overview of the project, its current status and important project links.
The planning documents include the product backlog, Sprint 1 backlog, sprint review and retrospective.
I also created an Architecture Decision Record for the Board-Stage-Card structure. This records the design decision and the reasoning behind it.
Supporting project documentation and tracking resources are maintained through Google Workspace.

## Slide 8 - Current Risks & Challenges
**Approximate Time: 40 seconds**

One of the main challenges at the moment is that CareerLane has been planned, but the application code still needs to be implemented.
Because of this, scope management is important. There are several features that could eventually be useful, but the core workflow needs to work before additional functionality is introduced.
Another consideration is workflow clarity.
The CareerLane stages such as Applied, Assessment and Interview represent the progress of a job application.
In comparison, statuses such as In Progress, Review and Complete in Asana represent the progress of development tasks. Keeping these workflows separate makes the project easier to understand and manage.

## Slide 9 - Demo Overview
**Approximate Time: 45 seconds**

CareerLane is not yet implemented, so I do not have a working application to demonstrate at this stage.
The planned demonstration would begin with creating a job-search board.
The user would then add an application containing information such as the company and position.
As something happens with the application, it would move through the appropriate stages.
Later, I would also like CareerLane to help users keep track of important dates such as assessments and interviews.
This is particularly useful because it can give the applicant time to prepare instead of only reacting when an interview call or email arrives.

## Slide 10 - Summary & Resources
**Approximate Time: 45 seconds**

To summarise, CareerLane came from a problem that I experienced myself. When you are sending out many applications, keeping track of every position and every stage can become difficult.
CareerLane now has a defined problem, a Board-Stage-Card workflow, an initial product backlog and Sprint 1 plan, supporting documentation, and a Git and GitHub collaboration workflow.
The next step is implementation, starting with the core functionality of creating boards, adding job applications and tracking those applications through their stages.
Ultimately, if I receive another interview call about an application I submitted weeks earlier, I should not have to rely entirely on my memory.
The goal is for CareerLane to allow me to quickly see what I applied for, where I am in the process and what I need to prepare for next.
Thank you.


# Likely Questions

## Why not just use Excel or Google Sheets?

A spreadsheet can be used to manually track applications, but CareerLane is designed specifically around the job application process. The aim is to provide a structured workflow where applications can move through defined stages instead of requiring the user to create and maintain their own tracking system.

## Is CareerLane currently working?

Not yet. CareerLane is currently moving from planning into early implementation. The project structure, backlog, Sprint 1 planning, documentation and core design decisions are in place, but the application source code still needs to be implemented.

## Why did you choose these application stages?

The stages provide a simple way of representing the progress of an application, starting from an opportunity the user is interested in and continuing through application, assessment, interview and the final outcome.

## What will you implement first?

The first priority is the core Board-Stage-Card workflow: creating a board, adding job applications and allowing those applications to be tracked through their different stages.

## What features would you add later?

After the core workflow is working, I would like to add features such as important dates and reminders, particularly for assessments and interviews. These could help users prepare for upcoming stages of their applications.

## What is the difference between CareerLane stages and your Asana workflow?

CareerLane stages represent the progress of job applications, such as Applied, Assessment and Interview. Asana statuses such as In Progress, Review and Complete represent the progress of the development work being done on CareerLane. They serve two different purposes.