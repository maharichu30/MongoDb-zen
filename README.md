# MongoDB Zen Class Programme Database

A MongoDB database design for managing a Zen class programme with users, attendance, code challenges, and placement tracking.

Databse Name: `zen_class`

## Collections
  Database consists of the following collections:
- **users** - Student and staff information
- **codekata** - Code challenge problems and solutions
- **attendance** - Class attendance records
- **topics** - Course topics and materials
- **tasks** - Assignment submissions and tracking
- **company_drives** - Recruitment drive events
- **mentors** - Mentor information and mentee assignments

## Key Queries

1. Find all topics and tasks taught in October
2. Find company drives between 15-Oct-2020 and 31-Oct-2020
3. Find company drives and students with placement records
4. Count problems solved by user in codekata
5. Find mentors with more than 15 mentees
6. Count users absent with unsubmitted tasks between 15-Oct-2020 and 31-Oct-2020

## Setup

Configure MongoDB connection and import sample data to the respective collections.