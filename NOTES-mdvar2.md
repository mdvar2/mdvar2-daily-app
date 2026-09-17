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

#### TrackFlow Feedback Reflection

During the in-class TrackFlow activity, the instructor reviewed my work individually, including how I had structured the user stories and assigned story points. The overall feedback on my work was positive.

The main suggestion was to make the workflow stages clearer by separating the work into **In Progress**, **Review**, and **Complete**. This would make it easier to see whether a task is still being worked on, is waiting for review, or has actually been completed.

Based on this feedback, I would improve the workflow by using these separate statuses rather than treating work that is still being reviewed as complete. This gives the board a clearer representation of the actual progress of each task.

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

The permission I had to think about most carefully was deciding who actually needed Editor access. For the CareerLane project, I gave the instructor Commenter access because she needed to review and provide feedback rather than directly edit my work.

I was not able to add another trainee as an Editor and complete the peer collaboration at the time I was working on the assignment. Some trainees were unavailable because we were completing the work at different times, and some had been working on their assignments during the day and were already offline or asleep when I was completing mine.

This showed me that collaboration also depends on availability and timing. In future, I would arrange the collaboration earlier so that another trainee can be available to edit, comment and use Suggesting mode with me rather than leaving that part until late in the assignment.

#### 3. Sync vs. async, in practice

My original split still made sense in practice. Most of the CareerLane kickoff information could be handled asynchronously through the Project Doc, tracker, presentation and shared Drive folder because the information is recorded and can be reviewed without a meeting. A live conversation is more useful when feedback needs clarification or when a decision cannot be resolved through comments. This showed me that a kickoff does not need a meeting for every activity; the live discussion should focus on decisions and blockers.

## Assignment 3.2

### Part 1 - Written Decisions

#### Question 1 - Beyond the core four

In addition to Purpose, Setup, Usage and a Contribution Guide, I would add a Current Project Status section to the CareerLane README. CareerLane is currently in the planning and early development stage, so someone visiting or cloning the repository needs to know what has already been completed and what is still being developed.

Leaving this section out could make someone assume that the full application is already implemented and ready to run, when the repository currently mainly contains the project planning and documentation. A Current Project Status section would set clear expectations and can be updated as CareerLane develops.

#### Question 2 - Comment audit

CareerLane is currently in the planning and documentation stage, and the application source code has not been added to the repository yet. Because of this, there are currently no existing code comments that I can truthfully identify by file and line for removal or improvement.

When development begins, I will use comments mainly to explain non-obvious decisions and reasons rather than restating what the code already shows. For example, if I temporarily comment out a line because it causes an error, I should explain why the line was disabled and what error or problem it caused. This will help another developer understand the reason behind the change instead of simply uncommenting the line and causing the same problem again.

I will complete the actual comment audit once CareerLane contains application source code.

#### Question 3 - What makes a decision ADR-worthy?

One real decision in CareerLane that is worth documenting is the decision to structure the application around boards, columns and cards. A board represents a job-search campaign, columns represent stages such as Interested, Applied, Assessment, Interview, Offer and Rejected, and cards represent individual job applications.

This is ADR-worthy because it defines the core structure of CareerLane and will influence how the application is designed, how job application data is organised and how users interact with the system. Changing this structure later could affect several parts of the application, so documenting why it was chosen gives future contributors context. A small implementation detail, such as the name of a variable or the wording of a button, would not need an ADR because it would not have the same impact on the overall system.

### Part 2 - Given Code Practice

#### Task 1 - Commented QuickNotes Signup Function

```javascript
function signup(email, password) {
  if (!email.includes('@')) return { error: 'invalid' };
  if (password.length < 8) return { error: 'weak' };

  // Use 10 bcrypt rounds to balance password-hashing security with application performance.
  const hash = bcrypt.hashSync(password, 10);

  const existing = db.users.find(u => u.email === email);
  if (existing) return { error: 'exists' };

  // New accounts remain unverified until the user confirms their email.
  const user = db.users.insert({ email, hash, verified: false });
  sendEmail(user.email, 'confirm-token-' + user.id);

  return { id: user.id };
}

#### Task 2 - QuickNotes README Excerpt

##### Setup

QuickNotes requires Node.js and npm.

1. Clone the project repository.
2. Open a terminal in the project directory.
3. Install the required dependencies:
```bash
npm install
```
4. Ensure the application has access to its user database and email service before starting it.
5. Start the application using the start command configured by the project.

##### Usage

The `signup` function creates a new QuickNotes user account using an email address and password. The email address must contain `@`, and the password must contain at least 8 characters. If the email is already registered, the signup request is rejected. When signup succeeds, the password is securely hashed before the user is stored. The new account starts as unverified, and a confirmation email is sent to the user.

Example:
```javascript
signup("user@example.com", "password123");
```

A successful signup returns the ID of the newly created user:
```javascript
{ id: 1 }
```
Invalid input or an existing account returns an error instead.

#### Task 3 - QuickNotes Signup Endpoint Documentation

##### POST /api/signup

**Description**

Creates a new QuickNotes user account using an email address and password. The account is created as unverified and a confirmation email is sent after successful registration.

**Authentication**

No authentication is required because this endpoint is used to create a new account.

**Request Body**

```json
{
  "email": "user@example.com",
  "password": "password123"
}
```

| Field | Type | Required | Description |
|---|---|---|---|
| email | String | Yes | Email address for the new account. It must contain `@`. |
| password | String | Yes | Password for the account. It must contain at least 8 characters. |

**Successful Response**

**201 Created**

The account was created successfully.
```json
{
  "id": 1
}
```

**Error Responses**

**400 Bad Request - Invalid email**

Returned when the supplied email address does not contain `@`.
```json
{
  "error": "invalid"
}
```

**400 Bad Request - Weak password**

Returned when the password contains fewer than 8 characters.
```json
{
  "error": "weak"
}
```

**409 Conflict - Existing account**

Returned when an account with the supplied email address already exists.
```json
{
  "error": "exists"
}
```

#### Task 4 - QuickNotes ADR

### Title: Hash Passwords with bcrypt at 10 Rounds

**Status:** Accepted

**Context**

QuickNotes needs to store user passwords securely rather than saving them as plain text. Password hashing should make stored passwords difficult to recover if user data is exposed, while still allowing the signup process to perform efficiently.

**Decision**

QuickNotes will hash user passwords using bcrypt with a cost factor of 10 rounds before storing them in the database.

**Consequences**

Using bcrypt means that plain-text passwords are not stored in the user database. The cost factor also makes password hashing deliberately more computationally expensive, which helps protect stored passwords.
The trade-off is that hashing requires additional processing time. If the cost factor is changed in the future, the team should consider both security requirements and application performance.

### Part 3 - Apply It to CareerLane

#### Task 5 - Real README

The CareerLane README was updated to include Purpose, Setup, Usage, Current Project Status, Project Documentation, Project Links and Contributing sections. The Setup instructions were tested by cloning the repository into a clean directory and opening the cloned project successfully.

#### Task 6 - Real Comment Audit

CareerLane does not contain application source code yet, so there is currently no real source-code comment that I can truthfully remove, rewrite or add. When application development begins, I will apply the comment guidance from this assignment by removing comments that only repeat what the code already shows and adding comments where the reason behind a non-obvious decision needs to be explained.

#### Task 7 - Real CareerLane ADR

A CareerLane ADR was created at:
`docs/decisions/001-board-column-card-structure.md`

The ADR documents the decision to structure CareerLane around Boards, Columns and Cards, where a Board represents a job-search campaign, Columns represent application stages, and Cards represent individual job applications.

#### Task 8 - Real Endpoint or Function Documentation

CareerLane does not currently contain an API or implemented application functions because the project is still in the planning and documentation stage. Therefore, there is no real endpoint or non-trivial application function that I can truthfully document with implemented inputs, outputs and error cases yet.

The planned CareerLane functionality includes creating boards, adding job applications and moving applications through stages such as Interested, Applied, Assessment, Interview, Offer and Rejected. However, I have not documented any of these as implemented functions because the application source code has not yet been developed.

I will complete this documentation once the corresponding CareerLane function or module has been implemented.

### NOTES.md Updates

#### 1. What the sample exercise revealed

Documenting the QuickNotes signup function helped me understand that good technical documentation should explain information that is not immediately obvious from the code. When I moved to the CareerLane README and ADR, I focused more on explaining the purpose of the project, its current state and why important design decisions were made. It also made me realise that documentation should be honest about what has and has not been implemented yet instead of making the project appear more complete than it currently is.

#### 2. The comment you were wrong about

CareerLane does not contain application source code yet, so I could not complete a real comment removal or rewrite. However, the exercise changed how I think about comments before I begin implementing the application. I originally thought comments were mainly useful for describing what a section of code does. I now understand that clear code should normally explain what it does itself, while comments are more useful for explaining why something was done.

For example, if I comment out a line because it causes an error, I should not leave the disabled code without an explanation. I should document why it was disabled and what problem or error occurred so that another developer does not uncomment it without understanding the reason.

#### 3. The line between decision and detail

After writing the CareerLane ADR, I would document fewer but more important decisions rather than documenting every implementation choice. The Board, Column and Card structure is worth documenting because it affects how CareerLane organises job-search campaigns, application stages and individual applications.

Smaller implementation details that can easily be understood from the code would not need their own ADR. I would use ADRs for decisions that affect the overall structure of the system or would be difficult to change later without affecting other parts of the project.

### Assignment 3.2 Links
- CareerLane README: https://github.com/mdvar2/mdvar2-daily-app/blob/main/README.md
- CareerLane ADR: https://github.com/mdvar2/mdvar2-daily-app/blob/main/docs/decisions/001-board-column-card-structure.md
- CareerLane endpoint/function documentation: Not yet applicable because CareerLane application development has not started and the repository does not currently contain an API or application function to document.

## Assignment 3.3

### Part 1 - Written Decisions

#### Question 1 - Channel choice, for real

One real communication issue I had this week was when I needed another trainee to collaborate with me on my CareerLane Google Drive documents by giving them Editor access. By the time I reached that part of the assignment, the trainees I could have asked were already offline or asleep, so I could not complete the collaboration at that time.

A Slack or Teams message would have been appropriate because I only needed to coordinate quickly with another trainee rather than create a formal record. However, I should have sent the message earlier instead of waiting until I was already completing that part of the assignment. I would also make the request specific by explaining that I needed someone to be available to edit or comment on a CareerLane document and stating when I needed to complete the activity. This would give the other trainee enough context and time to respond.

#### Question 2 - The self-check you did or skipped

One blocker I experienced this week was when an assignment required me to work with application code, including an API endpoint or function, but CareerLane is still in the planning and early implementation phase and I had not developed that part of the application yet.

Before trying to complete the requirement, I checked the CareerLane repository to confirm what files and functionality were actually available. This helped me realise that there was no existing API or application function that I could truthfully document. Instead of creating code just to make the requirement appear complete, I documented the current project status and noted that this part would need to be completed once the relevant functionality has been implemented.

The self-check was useful because it prevented me from documenting functionality that does not yet exist. It also showed me that checking the current state of the project should come before asking for help or assuming that a requirement can already be completed.

#### Question 3 - Specific vs. vague feedback, side by side

**Specific feedback:**  
The README explains the purpose and planned features of CareerLane clearly, but the project status should be stated explicitly so that someone visiting the repository does not assume that the application is already fully implemented. Add a "Current Project Status" section explaining that CareerLane is currently in the planning and early implementation phase and that application functionality is still being developed.

**Vague feedback:**  
The README looks good, but it still needs some work.

**Difference:**  
The specific feedback identifies exactly what needs improvement, explains why it matters, and suggests a clear action, while the vague feedback does not tell the developer what should be changed.

### Part 2 - Given Scenario Practice: BudgetBuddy

#### Task 1 - Channel Rewrite

The budget sync issue is an immediate sprint blocker, so I would communicate it through Slack or Teams for quick coordination. The decision about whether the export feature should be included in the sprint should be handled separately by email because it affects sprint planning and is useful to keep as a clear record.

**Slack/Teams message - Budget sync blocker:**

Hi team, I'm currently blocked on the BudgetBuddy budget sync feature. The sync is not working as expected, so I am investigating the issue now. Has anyone recently worked on the sync functionality or seen a similar problem? I can share the exact behaviour and what I have tried in the thread.

**Email - Export feature decision:**

**Subject: Decision needed: Export feature for current BudgetBuddy sprint**

Hi team,

I would like us to confirm whether the export feature is still part of the current sprint scope. Please let me know whether we are keeping it in this sprint or moving it to a later sprint so that our sprint plan remains clear.

Thanks.

#### Task 2 - Question Rewrite

**Context:**  
I'm working on the BudgetBuddy budget totals and the category totals are not adding up correctly after the budget is updated.

**What I tried:**  
I reviewed the `updateBudget()` function and checked the part responsible for recalculating the category totals to understand where the incorrect result might be coming from.

**Exact error/behaviour:**  
There is no specific error message provided, but the calculated totals do not match the expected budget totals after the update.

**Specific ask:**  
Could someone help me check whether the issue may be in how `updateBudget()` recalculates the category totals, or point me to the next part of the calculation I should investigate?

#### Task 3 - PR Feedback

The `updateBudget()` function is currently handling several responsibilities in one 40-line block: validating the input, recalculating category totals, and writing the changes to the database. This makes the function harder to read, test, and maintain.

I suggest separating these responsibilities into smaller functions, for example one function for validating the budget input, another for recalculating the category totals, and keeping the database update separate. It would also help to add a short comment where the recalculation logic is not immediately obvious, explaining why that calculation is necessary rather than commenting every line.

#### Task 4 - Receiving It Well

Thanks for the feedback. I understand that `updateBudget()` is doing too many things in one function, which makes it harder to maintain and test.

Would you recommend separating all three responsibilities into their own functions, or should the database update remain in `updateBudget()` while the validation and recalculation logic are extracted first?

I appreciate the suggestion. I would use the clarification to refactor the function into smaller responsibilities and then review whether the recalculation logic needs an explanatory comment.

### Part 3 - Applying This to My Real Work

#### Task 5 - Real Help Request

**Context:**  
Hi Skye, I am working through the technical documentation requirements for CareerLane. The project is currently in the planning and early implementation phase, so the repository does not yet contain application source code, an API endpoint, or an implemented application function.

**What I tried:**  
I checked the repository and reviewed the existing CareerLane files to make sure I had not overlooked any functionality that I could use for the code-related documentation tasks. At the moment, the repository contains the project documentation and planning work, but not the application code required for those parts.

**Exact blocker:**  
Because that functionality has not been implemented yet, I cannot truthfully audit source-code comments or document a real endpoint/function without creating something that does not currently exist in the project.

**Specific ask:**  
For the requirements that depend on existing application code, should I document that they are not yet applicable and complete them once CareerLane reaches that stage of implementation, or would you prefer me to approach those requirements differently?

#### Task 6 - Leave Real PR Feedback

I reviewed the DevFlow Daily App repository of another trainee and left feedback on the pull request that included their updated README.

**Feedback left:**

> The README is well structured, and I like that you clearly separate the current project status from the planned features, which makes it easy to understand what has and has not been implemented yet. One small suggestion would be to format the Architecture section as a clearer diagram or code block showing the Browser → DevFlow API → Database flow and the future mobile app connection. This could make the planned architecture easier to understand at a glance.

The feedback focused on a specific part of the README, acknowledged what was already done well, and suggested a small improvement that could make the architecture easier for other developers to understand.

**PR:** https://github.com/scroogerzy/DevFlow/pull/5 

#### Task 7 - Reflect on Real Feedback Received

During the Asana TrackFlow activity, the instructor reviewed how I had organised my CareerLane work in Asana and suggested that I add separate sections for **In Progress**, **Review**, and **Complete**.

This feedback was useful because it was specific about how I could improve the way work progress is represented in Asana. Having separate sections would make it easier to distinguish tasks that are currently being worked on, tasks that are waiting for review, and tasks that have been completed.

I would respond by thanking the instructor for the feedback and applying the suggested sections to my Asana workflow. If I was unsure about how a task should move between the sections, I would ask for clarification before making assumptions.

#### Task 8 - Before/After a Real Message

**Original message:**

> hey can you share your your email so I can send you an invitation to be an editor

I sent this message to another trainee when I needed to add someone as an Editor to my CareerLane Google Drive work.

**Rewritten message:**

> Hi, can you please share the email address you use for Google Drive? I need to add another trainee as an Editor to my CareerLane project document for the collaboration activity. Once I send the invitation, I will need you to make an edit or leave a comment on the document. Please let me know if you are available to help. Thanks.

**What changed and why:**

The original message communicated what I needed but did not provide enough context. In the rewritten version, I explained why I needed the email address, what the invitation was for, what I needed the other trainee to do, and asked whether they were available. This makes the message more self-contained and reduces the need for follow-up questions.

### Assignment 3.3 Reflections

#### 1. What the BudgetBuddy practice revealed

The BudgetBuddy exercise made me notice that a message can make sense to me because I already know the context, while the person receiving it may not have that same information. This became clear when I looked back at the message I sent asking another trainee for their email address. I knew that I needed it to add them as an Editor to my CareerLane Google Drive work, but I did not explain all of that in the original message.

Rewriting the BudgetBuddy messages helped me recognise the same habit in my own communication. Going forward, I would include the purpose of the request and what I need from the other person so that they can understand and respond without needing several follow-up messages.

#### 2. The self-check I almost skipped

For the CareerLane blocker in Task 5, I could have easily asked the instructor what to do as soon as I saw that the assignment required an API endpoint or application function. Instead, I first checked the repository and reviewed the existing files to confirm whether there was already something I could use.

That check confirmed that CareerLane had not yet reached the stage where the required API or application function existed. Doing the self-check first meant that my help request could explain exactly what I had already verified and ask a more specific question instead of simply saying that I could not complete the task.

#### 3. Giving feedback on something real

Giving feedback on a real trainee's DevFlow project felt different from writing feedback on the BudgetBuddy sample because I was more careful about how my feedback could be received. With the sample, I could focus only on identifying the problem and suggesting a solution. With a real person's work, I wanted to acknowledge what they had done well while still providing a useful suggestion without making unnecessary changes to their project.

I therefore focused on a small improvement to the DevFlow README's Architecture section. I first acknowledged that the README was well structured and clearly separated the current project status from the planned features, and then suggested presenting the architecture flow more clearly as a diagram or code block. This experience showed me that useful feedback can recognise good work while still giving a specific and actionable suggestion.

### Assignment 3.3 Real Artifact Links and Copies

- **Task 5 - Real help request:** The complete help request is included above under **Task 5 - Real Help Request**. It is based on the real CareerLane blocker encountered when the project did not yet contain the application code or API required by the technical documentation task.

- **Task 6 - Real PR feedback:** https://github.com/scroogerzy/DevFlow/pull/5  
  My feedback was posted on DevFlow PR #5 and is also copied above under **Task 6 - Leave Real PR Feedback**.

- **Task 7 - Real feedback received:** The instructor gave me this feedback during the in-class Asana TrackFlow activity. My reflection is included above under **Task 7 - Reflect on Real Feedback Received**.  
  CareerLane Asana project: https://app.asana.com/1/1218292849466881/project/1218305236133456/list/1218305237603854

- **Task 8 - Real message:** The original message I sent to another trainee is copied verbatim above under **Task 8 - Before/After a Real Message**, together with the rewritten version. The message was sent when I needed another trainee's email address so that I could invite them as an Editor to my CareerLane Google Drive work.  
  CareerLane Google Drive folder: https://drive.google.com/drive/folders/1txXZ4mM-LCSo5C14cz1FuBwtfZG-7k5r?usp=drive_link



















