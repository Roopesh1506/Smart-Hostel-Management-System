# Smart Hostel Management System

## Problem Statement

Managing a hostel means keeping track of many things like student details, rooms, room allotment and complaints. Doing all this manually can take more time and it can also lead to mistakes. Sometimes it can be difficult to know which rooms are free, which students are staying in a room, or which complaints are still pending.

The **Smart Hostel Management System** is a Java based application made to keep these hostel related records in one place. It helps the admin manage students and rooms, allocate rooms, and handle student complaints more easily.

## Scope of the Project

This project mainly covers the basic hostel management work such as:

- Managing student details
- Adding hostel rooms and checking which rooms are available
- Recommending a suitable room and allocating it to a student
- Allowing students to submit complaints
- Giving a priority to complaints based on their type and severity
- Showing basic hostel information on the dashboard

The project is made as a desktop application using **Java Swing**. **MySQL** is used to store the data and **JDBC** is used to connect Java with the database.

## Target Users

### Admin / Warden

The admin or warden can manage student details, rooms, room allotments and complaints. The admin can also check basic hostel information from the dashboard.

### Students

Students can check their hostel information, submit complaints and see the status of their complaints.

## High-Level Features

- Login system for admin and students
- Add, update, delete and view student details
- Add rooms and check room availability
- Recommend a suitable room using a scoring method
- Allocate a room and update its occupancy automatically
- Submit complaints with automatic priority
- Update complaint status from the admin panel
- View submitted complaints and their status
- Basic hostel dashboard
- Store hostel data in MySQL
