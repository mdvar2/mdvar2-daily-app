# Notes

## Assignment 2.1

### Question 1 - Scrum or Kanban, for two different contexts
For my Daily App, CareerLane, I would use Kanban. I will be working on the project alone in short sessions, so having a continuous flow of work would suit me better than working in fixed sprints. Kanban also allows me to limit work in progress, which will help me focus on finishing the work I have already started before taking on more. I would choose Kanban over Scrum for CareerLane because Scrum includes sprint planning, roles and ceremonies that would add unnecessary structure when I am the only person working on the project.

For TrackFlow, I would use Scrum because it is a shared class project with several people contributing. Sprints would give the team a common goal and a clear period in which to complete planned work. Scrum roles and ceremonies would also help the team coordinate responsibilities, review progress and communicate about problems.

My choice is different for the two projects because TrackFlow needs more coordination between team members, while CareerLane needs the flexibility of continuous individual work.

### Question 2 - A real trade-off
I would choose individuals and interactions over processes and tools.

While planning CareerLane, I could spend a lot of time choosing tools and creating a detailed process for how the application should work. However, I would rather speak to students and early-career developers and find out what problems they actually experience when keeping track of job applications.

I would lean towards individuals and interactions because feedback from potential users could show me that some of my planned features are unnecessary or that I have missed something important. I would still use planning tools and processes, but they should support the project rather than become more important than understanding the people who will actually use CareerLane.

### Question 3 - Critique and redesign

#### Problem 1 - Requirements are locked too early
The Waterfall plan assumes that all requirements can be known before development starts and does not allow changes once the design phase begins. For CareerLane, students might later tell me that tracking assessment deadlines is important. Under this approach, I would not be able to respond easily because the requirements have already been approved.

This goes against the Agile value of responding to change over following a plan. An Agile approach would allow me to use feedback to adjust the backlog and include valuable changes in a later iteration.

#### Problem 2 - Feedback comes too late
The plan says that there will be no demos until the build phase is complete. This means I could spend weeks developing CareerLane before finding out that I missed an important feature or that something does not meet the users' needs.

Timely feedback is important during software development because users can tell me what is working, what needs improvement and what should change while there is still time to respond. This goes against the Agile principle of delivering working software frequently and getting regular feedback.

#### Problem 3 - Testing happens too late
The plan leaves full QA testing until almost the end of the project. If CareerLane is developed this way, bugs could remain unnoticed for several weeks and affect other features built on top of them.

For example, if there is a problem with moving application cards between stages, it could cause information to be lost or parts of the system to fail. Finding the problem near the end would also make it harder to identify and fix. An Agile approach would test working features throughout each iteration instead of waiting until the whole application has been built.

#### Agile Redesign

##### Iteration 1 - Basic Application Board
I would start by allowing the user to create a CareerLane board for their job search. The board would contain basic application stages such as Interested, Applied, Assessment, Interview, Offer and Rejected.

The user would be able to add a simple job application card containing the company name and job title and move it between the stages. At the end of the iteration, I would test the basic workflow and get feedback before deciding what to add or change next.

##### Iteration 2 - Important Dates and Reminders
After testing the basic board, I would add the ability to record important dates such as application deadlines, assessment dates and interview dates. CareerLane would then provide reminders to help users avoid missing these important events.

I would test the reminder feature with users and use their feedback to decide what should be improved or added in the next iteration.

### NOTES.md Updates
1. Naming CareerLane made the project feel more specific than the generic board idea. Once I chose job applications as the domain, it became easier to think about what the Board, Columns and Cards should represent and which features would actually be useful.

2. The problem that would hurt the most in practice is getting feedback too late. If I only show the application after most of it has already been built, I could discover too late that I missed an important feature or designed something in a way that users do not find useful. Getting feedback after each iteration would make it easier to improve CareerLane while development is still in progress.

## Assignment 2.2

### Question 1 - Roles, solo and shared
For TrackFlow, the instructor could act as the Product Owner because they guide the project requirements and priorities. One trainee could act as the Scrum Master, or the role could rotate between trainees. The trainees working on TrackFlow would make up the Development Team.

For CareerLane, I would have to take all three roles because I am working on the project alone. The role I think I would neglect first is the Scrum Master role. When I am busy, I could easily focus on completing the actual work and skip things such as checking my progress and planning what I should work on next.

To prevent this, I would have a short check-in at the beginning of every work session where I review what I completed, what I am doing next and whether anything is blocking me.

### Question 2 - Definition of Ready and Definition of Done
For CareerLane's first epic, Application Boards, my Definition of Ready would be:

An Application Boards backlog item is ready when its purpose is clear, the expected user action is described, the information needed for the feature is identified, the acceptance criteria are written, and there are no known blockers or unanswered questions that would prevent me from starting it.

My Definition of Done would be:
An Application Boards backlog item is done when it meets all of its acceptance criteria, works as expected, and has been tested to make sure the required functionality works correctly.

### Question 3 - The artifact most at risk
The Scrum artifact most at risk for CareerLane would be the Sprint Backlog. Since I am working alone, I might be tempted to choose tasks directly from the Product Backlog and start working without deciding what I should focus on for the current sprint.

The cost of skipping the Sprint Backlog is that I could lose focus, take on too much work at once, or keep switching between tasks without completing them. Maintaining a Sprint Backlog would give me a clear short-term goal and help me keep track of what I have committed to completing.

### Assignment 2.2 Reflections

1. The Scrum Master role is still the role I think I would neglect first. While creating the Sprint Backlog, I realised that it is easy to focus on the actual work and forget about regularly checking progress, blockers and whether I am still following the Sprint plan. A short check-in at the beginning of each work session would help me avoid this.

2. My Definition of Ready filtered out the backlog item for deleting a job-search board. I originally wanted to include it in Sprint 1, but I had not decided what should happen to the job application cards inside the board when it is deleted. Because this question was still unresolved, the item was not ready to be included in the Sprint.

## Assignment 2.3

### Question 1 - Choosing a view

For CareerLane, I would use Timeline as my primary day-to-day view. Job applications often have important dates such as application deadlines, assessment dates and interview dates. The Timeline view would help me see these dates in order and understand what is coming up, which would make it easier to plan my work and avoid missing important deadlines.

I would use the Board view when I want to see where each job application is in the application process, such as Interested, Applied, Assessment, Interview, Offer or Rejected. This would make it easy to see the progress of applications as they move between stages.

I would use the List view when I need a simple and detailed overview of my tasks and application information. It would be useful when I want to review several items quickly or check details without focusing on dates or application stages.

### Question 2 - Custom fields, deliberately

For CareerLane, I would use two custom fields: Priority and Type. The Priority field would have High, Medium and Low values. I would use it to decide which items need my attention first. It would also allow me to filter the project to see only High-priority items when I need to focus on the most important work.

The Type field would have Board, Application, Application Details and Reminder values. I would use it to identify what kind of CareerLane work each task represents. For example, I could filter by Reminder when I only want to see work related to important dates and notifications. I chose these fields because each one supports a specific decision or filter instead of adding information that I would not use.

### Question 3 - Tag or field?

For CareerLane, I would use needs-review as a tag. I could apply it to tasks that I need to come back to and review, and the same tag could also be useful across other projects. I would use Priority as a custom field with High, Medium and Low values. Priority needs consistent values because I want to use it to filter tasks and decide which work needs attention first.

If I swapped them, Priority as a tag could become inconsistent because I could create different free-form versions of the same priority. Using needs-review as a custom field would also add unnecessary structure for something that only needs to mark certain tasks temporarily.

### Assignment 2.3 Reflections

1. The Asana feature that changed how I thought about my backlog the most was dependencies. Before using them, I mostly saw the backlog as a list of separate tasks. Adding dependencies made me think about the order in which tasks need to be completed. For example, in CareerLane, viewing existing job-search boards depends on first having a board that has been created.

2. One field I almost added without a clear purpose was Application Stage. At first it seemed useful to show stages such as Interested, Applied, Assessment and Interview. However, I realised that a custom field should help me make a decision, organise work or filter useful information rather than just add more data. This made me think more carefully about which fields are actually useful.

3. One dependency I discovered in CareerLane is that "View all existing job-search boards" is blocked by "Create a new job-search board with a board name." This dependency is real because there needs to be an existing board before the user can meaningfully view it.




