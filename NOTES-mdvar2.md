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


## Assignment 2.4

### Question 1 - Rewrite Sprint 1 as real user stories

1. As a job seeker, I want to create a job-search board with a name, so that I can organise my applications into a specific job-search campaign.
2. As a job seeker, I want to view all my existing job-search boards, so that I can access and manage my different job-search campaigns.
3. As a job seeker, I want to rename an existing job-search board, so that I can keep my job-search campaigns clearly organised.
4. As a job seeker, I want to add a new job application to a board, so that I can keep track of the jobs I am interested in or have applied for.
5. As a job seeker, I want to see each job application in its current application stage, so that I can quickly understand the progress of my applications.

### Question 2 - Acceptance criteria

#### Story 1 - Create a job-search board

- The user can create a new job-search board.
- The user can enter a name for the board.
- The new board is created using the name entered by the user.
- If no board name is entered, the board is created with the default name "Untitled Board".
- The newly created board is available for the user to view.

#### Story 2 - View existing job-search boards

- The user can view all job-search boards they have created.
- Each board displays its board name.
- Newly created boards appear in the list of existing boards.
- The user can select an existing board to access it.
- If the user has no existing boards, the system displays a message indicating that no boards are available.

#### Story 3 - Rename a job-search board

- The user can select an existing job-search board to rename.
- The user can enter a new name for the selected board.
- The new board name replaces the previous name after the change is saved.
- The renamed board appears with its new name when the user views their existing boards.
- The board's existing job applications are not removed when the board is renamed.

#### Story 4 - Add a job application

- The user can add a new job application to an existing job-search board.
- The user can enter the company name and job title for the application.
- The new application is saved to the selected board.
- The newly added application appears on the selected board.
- The application is placed in the Interested stage by default when it is first created.

#### Story 5 - View applications in their current stage

- Each job application is displayed on its job-search board.
- Each application is shown in its current application stage.
- The supported stages are Interested, Applied, Assessment, Interview, Offer and Rejected.
- A newly created application appears in the Interested stage by default.
- The application remains visible in the correct stage when the board is viewed again.

### Question 3 - INVEST check

I evaluated the story: "As a job seeker, I want to rename an existing job-search board, so that I can keep my job-search campaigns clearly organised."

- Independent: It is mostly independent because renaming a board can be developed without depending on the application tracking and reminder features.
- Negotiable: The exact way the user starts and saves the rename action can still be discussed without changing the purpose of the story.
- Valuable: It gives the job seeker a useful way to keep their different job-search campaigns organised.
- Estimable: The expected behaviour and acceptance criteria are clear enough for me to estimate the work.
- Small: The story focuses only on renaming an existing board and is small enough to complete within the sprint.
- Testable: The acceptance criteria make it possible to verify that the board can be renamed and that its existing applications are preserved.

The story passes all six parts of INVEST, so I would not change its scope.

### Question 4 - Estimating alone, again

I used relative estimation with a Fibonacci-style scale of 1, 2, 3, 5 and 8.

- Create a job-search board - 3 story points
- View all existing job-search boards - 2 story points
- Rename an existing job-search board - 2 story points
- Add a new job application to a board - 5 story points
- See each job application in its current application stage - 5 story points

The Sprint 1 total is 17 story points.

The estimate that surprised me most was adding a new job application. As a backlog phrase, it sounded like a simple action, but after writing the full story and acceptance criteria, I realised that it involves capturing application information, saving it to the correct board, displaying it and assigning an initial application stage. This made it larger than I first expected.

## Assignment 3.1

### Question 1 - Suggesting mode vs. comments vs. direct edits

I would use direct editing when I am responsible for the content and the change does not need someone else's approval. For example, in the CareerLane project documentation, I could directly correct a spelling mistake or update the Sprint 1 story point total after confirming the correct value. I would use Suggesting mode when I want to propose a change to someone else's work without permanently changing their original content. For example, if a teammate wrote the CareerLane project scope, I could suggest clearer wording for one of the scope statements and allow them to accept or reject the change.

I would use comments when I want to ask a question, give feedback or discuss something without changing the actual document. For example, I could comment on the CareerLane timeline and ask whether a particular feature should be completed in Sprint 1 or moved to a later sprint.

### Question 2 - Permissions, deliberately

For my CareerLane Drive folder, I would assign permissions based on what each person actually needs to do.

- Editor: I would keep Editor access for myself and give it to a teammate if we were actively working together on CareerLane. Editors need to create, update and organise the project files, so they require permission to make changes.
- Commenter: I would give my instructor Commenter access. This allows the instructor to review my CareerLane documentation, leave feedback and suggest improvements without directly changing the project content.
- Viewer: I would give Viewer access to other trainees or cohort members who only need to see the project. They can follow the project and understand what is being built, but they do not need permission to change or comment on the files.

I would not give everyone Editor access because this could lead to accidental changes or deletion of project content. Each person should receive only the level of access needed for their role.

### Question 3 - Sync or async?

For a CareerLane project kickoff, I would use a combination of synchronous and asynchronous communication instead of having a meeting for everything.
Goal-setting should happen synchronously in a Google Meet because the people involved may have different ideas about what the project should achieve. A live discussion makes it easier to clarify the goal and agree on the direction of the project. Task assignment can begin during the live kickoff so that responsibilities are clear, but the final assignments should be recorded asynchronously in the project tracker. This gives everyone a place to check their responsibilities after the meeting.

Routine status updates should be asynchronous. Team members can update the project tracker or project documentation with their progress instead of scheduling a meeting just to report what they have completed. Blocking questions should first be raised asynchronously when they are simple and can be answered quickly. If a blocker requires discussion, affects several tasks, or cannot be resolved through comments or messages, it should be moved to a live Meet conversation.

This approach keeps live meetings focused on decisions and problems that benefit from discussion, while Docs, Sheets and Calendar provide a record of information that the team can access without needing another meeting.

### NOTES.md Updates

#### 1. What the TidyUp practice revealed

Working on TidyUp first helped me understand how the different Google Workspace tools can support the same project instead of being separate files. When I created the CareerLane kickoff, I had a clearer idea of how to organise the Drive folders and how the Project Doc, tracker and kickoff presentation should connect. I also kept the tracker lightweight because Asana is still the main place where I manage the Sprint 1 work.

#### 2. The permission you almost got wrong

The permission I had to think about most carefully was the instructor's access. It would have been easy to give Editor access simply because the project needed to be shared, but the instructor does not need to directly change my project files. Commenter access is more appropriate because it allows feedback without giving unnecessary editing permission.

#### 3. Sync vs. async, in practice

My original split still made sense in practice. Most of the CareerLane kickoff information could be handled asynchronously through the Project Doc, tracker, presentation and shared Drive folder because the information is recorded and can be reviewed without a meeting. A live conversation is more useful when feedback needs clarification or when a decision cannot be resolved through comments. This showed me that a kickoff does not need a meeting for every activity; the live discussion should focus on decisions and blockers.







