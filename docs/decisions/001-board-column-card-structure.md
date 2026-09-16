# ADR 001: Use Boards, Columns and Cards for Job Application Tracking

## Status

Accepted

## Context

CareerLane needs a simple structure that allows students and early-career developers to organise multiple job applications and clearly see the progress of each application. A job seeker may have different job-search campaigns, such as graduate opportunities or junior developer positions. Each campaign can contain several applications, and each application can move through different stages during the recruitment process.

The project therefore needs a structure that keeps campaigns separate while making the progress of individual applications easy to understand.

## Decision

CareerLane will use a Board, Column and Card structure.
- A **Board** represents a job-search campaign.
- **Columns** represent application stages: Interested, Applied, Assessment, Interview, Offer and Rejected.
- A **Card** represents an individual job application.

As an application progresses, its card can move from one stage to another within the board.

## Consequences

### Positive

- Job applications can be organised by job-search campaign.
- Users can clearly see the current stage of each application.
- The structure provides a simple visual representation of application progress.
- Future CareerLane features can be designed around a consistent data structure.

### Trade-offs

- The application will need to maintain the relationship between boards, stages and application cards.
- Changes to the workflow stages in the future may affect how application data is organised and displayed.
- The design assumes that an application has one current stage at a time.


