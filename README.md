# PROG101_ASSIGNMENT_1_JOSEPH_G_P_MASSAQUOI_905006084
A school attendance management system designed to record, manage, and monitor student attendance.

## PROG101 - THE SCHOOL ATTENDANCE MANAGEMENT SYSTEM

The School Attendance Management System is a console based application designed to efficiently record, manage, and monitor student attendance. The system processes attendance for twenty five students by employing a user friendly loop based entry mechanism. It utilizes string inputs for attendance status, 'P' for present and 'A' for absent, and accurately updates the counters for students present and absent in real time.

## THE PROBLEM

Traditional paper based attendance systems are highly prone to physical loss and damage, leading to permanent loss of valuable student records. Furthermore, retrieving historical attendance data is extremely time consuming and inefficient. Manual data entry also significantly increases the risk of human error during the recording or calculation of attendance totals.

## SOLUTION

The proposed solution is a console based School Attendance Management System designed to streamline the attendance tracking process. The system uses an automated loop based entry mechanism to process daily attendance for twenty five students. By accepting simple string inputs for present and absent, it accurately calculates and updates attendance totals in real time, eliminating the inefficiencies and errors associated with manual data entry.

## Sustainable Development Goal (SDG) Alignment

The proposed School Attendance Management System supports Sustainable Development Goal 4: Quality Education. This goal includes ensuring inclusive and equitable quality education and promoting lifelong learning opportunities for all. By automating daily attendance tracking, the system reduces administrative overhead for educational institutions, allowing teachers and administrators to focus more time on instruction and student engagement.
Furthermore, it aligns with Sustainable Development Goal 11: Sustainable Cities and Communities, fostering safer, more resilient, and efficient institutional environments.

## Pseudocode
START

    DECLARE Students, Present, Absent AS INTEGER
    DECLARE Attendance AS STRING

    SET Present = 0
    SET Absent = 0

    OUTPUT "Welcome to the School Attendance Management System"

    FOR Students = 1 TO 25

        OUTPUT "Enter P for Present or A for Absent"
        INPUT Attendance

        IF Attendance = "P" THEN
            Present = Present + 1

        ELSE IF Attendance = "A" THEN
            Absent = Absent + 1

        ELSE
            OUTPUT "Invalid attendance input"

        END IF

    END FOR

    OUTPUT "Total Present: ", Present
    OUTPUT "Total Absent: ", Absent

END
## FLOWCHART
![Attendance Flowchart](https://github.com/user-attachments/assets/4064fb6c-7054-41c8-ae22-b96e788afc73)

## Impact of Solution

This solution streamlines attendance tracking, eliminates errors from manual data entry, and provides real-time updates to improve efficiency.

