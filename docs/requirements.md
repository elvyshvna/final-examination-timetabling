# Requirements

## Functional requirements (what the system must DO)
1. The system shall import student enrollment data, course lists, and room capacities from CSV or Excel files.
2. The system shall generate a conflict-free exam timetable that ensures no student is booked for two exams at the same time.
3. The system shall assign exams to rooms based on the number of students enrolled and the available seats.
4. The system shall allow administrators to manually adjust times and rooms after the schedule is generated.
5. The system shall publish the final timetable online so students and teachers can view their personalized schedules.

## Non-functional requirements (how the system must PERFORM)
1. The system shall generate a complete timetable within 2 minutes after the administrator clicks the start button.
2. The system shall remain online 99.9% of the time during the high-traffic exam publication week.
3. The system shall protect all student data by encrypting passwords and personal records in the database.
