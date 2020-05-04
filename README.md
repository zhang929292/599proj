# 599proj

Description:
    This is a computer room reservation system. It is designed to solve the problem of crowding in school computer room.
    There are three identifies, student, prefessor and manager. Students can log on to the system to view and book the room and wait for the teacher's approval before using the room.The administrator has the right to add and view the account information of all students and teachers, and the room reservation information. 
    There are three computer rooms in total, No. 1 computer room with maximum capacity 20 people; No. 2 computer room with maximum capacity 50 people; No. 3 computer room with maximum capacity 100 people.
    For reservation:
        The administrator is responsible for clearing the order each week.
        students can make an appointment to use the computer room in the next week. The date of reservation is from Monday to Friday. The time of reservation is 8:00-12:00 or 13:00-18:00.
        Teachers will review the reservation and check whether the appointment is approved or not according to the actual situation




Feature：

There are six classes in total.

"Identity.h"
The three identities have their commonalities and characteristics, thus, we store users name, password and operation menu in this file.

"student.h"
The main function of the student class is that the member function in the class can be used to realize the laboratory reservation operation.

"teacher.h"
The main function of the teacher class is to view students' appointments and review them.

"manager.h"
The main function of the administrator class is to manage the accounts of students and teachers, check the information of the computer room and clear the reservation record.

"globalFile.h"
Different identities may use different file operations, and we can define all the file names into a global file.

Hint: In the file "globalFIle.h", the file storage path needs to be updated to match the actual storage path, otherwise, the program may fail to run.

"computerRoom.h"
The main function of the computerRoom class is to saving computer room information.

    
    
    
Overview of implementation:
    First of all, enter the login interface. The optional login identity is: studenrt, teacher, manager and exit. 
    Users can go to the submenu after each identity being verified.
        - students need to enter: student number, name, login password
        - teachers need to input: employee number, name, login password
        - administrator needs to enter: administrator name, login password
    Student specific function
    - application for reservation -- room reservation
    - check your appointments -- check your status
    - view all appointments -- view all appointments and status
    - cancel -- cancel your own appointment, either successfully or during review
    - log out -- log out
    Specific functions of teachers
    - view all appointments -- view all appointments and status
    - review appointments -- review student appointments
    - log out -- log out
    Administrator specific functions
    - add an account -- to add a student or teacher's account, you need to check whether the student number or the teacher's staff number is repeated
    - view account number -- you can choose to view all information of students or teachers
    - view the machine room -- view all the machine room information
    - empty reservations -- empty all reservations
    - log out -- log out
    
    

Link to video:
https://www.youtube.com/watch?v=xHUA8okXR1c


Screenshots of the demo：


<img alt="Diagram" src="https://github.com/zhang929292/599proj/blob/master/student.png" width="400" text-align="center">


<img alt="Diagram" src="https://github.com/zhang929292/599proj/blob/master/teacher.png" width="400" text-align="center">


<img alt="Diagram" src="https://github.com/zhang929292/599proj/blob/master/manager.png" width="400" text-align="center">



Future work:

Change colors and fonts to improve the login interface for better readability.

