## StudentHub Timetabling Portal — User Stories

Story 1: View Weekly Timetable
As a student, I want to view my personal weekly timetable, so that I can plan my classes and manage my time.

Story 2: View Class Details
As a student, I want to see the room and lecturer details for each class, so that I know where to go and who will be teaching.

Story 3: Receive Timetable Updates
As a student, I want to receive notifications when a class is rescheduled or cancelled, so that I can adjust my plans.

Story 4: Swap Lab or Tutorial Slots
As a student, I want to swap into an alternative lab or tutorial slot, so that I can avoid clashes with other commitments.

Story 5: Export Timetable to personal Calendar
As a student, I want to export my timetable to my phone's calendar app, so that I can view my classes alongside other events.

Story 6: Cancel or Relocate a Class
As a lecturer, I want to mark a class as cancelled or relocated, so that students receive accurate information about where and when their class takes place.

Story 7: View Overcapacity Slots
As an administrator, I want to see which timetable slots are over capacity, so that I can identify scheduling problems and take corrective action.

Acceptance Criteria
Story 1: View Weekly Timetable
Given a student is logged in, when they open their timetable, then their classes for the current week are displayed.
Each class displays its date, start time, and end time.
If the student has no classes scheduled for a day, the timetable clearly indicates that there are no classes.
Story 3: Receive Timetable Notifications
Given a student is enrolled in a class, when that class is cancelled, then the student receives a notification about the cancellation.
Given a student's class is rescheduled, when the change is saved, then the student receives a notification showing the updated details.
Notifications identify the affected class and the relevant change.
INVEST Review

The stories aim to follow INVEST principles:

Independent: Each story focuses on a distinct feature where possible.
Negotiable: The implementation details can be discussed and refined.
Valuable: Each story provides a benefit to students, lecturers, or administrators.
Estimable: Each story has a clear goal that can be estimated by a development team.
Small: Each story focuses on a manageable piece of functionality.
Testable: Each story can be checked against clear requirements or acceptance criteria.
