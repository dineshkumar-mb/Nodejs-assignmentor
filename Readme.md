Assign-Mentor API
This documentation provides details about the Assign-Mentor API, implemented using Node.js and Express. This API allows you to manage mentors and students, assign mentors to students, change mentors, and retrieve mentor-student relationships.

Base URL: http://localhost:4000

Packages installed:

Express: npm install express

Cors: npm install cors

Dotenv: npm install dotenv

Mongoose: npm install mongoose

1. POST Create Mentor
http://localhost:4000/api/mentor/create

Create Mentor

Description: Creates a new mentor with details about the mentor.

URL: /api/mentor/create

Method: POST

Example: http://localhost:4000/api/mentor/create

![creatementor](https://github.com/dineshkumar-mb/Nodejs-assignmentor/assets/166787277/239d075a-8acc-4226-a49c-f10d08ab08c5)


2. POST Create Student

http://localhost:4000/api/student/create

POST Create Student

URL: /api/student/create

Description: Creates a new student wi
th details about the student.

Method: POST

Example: http://localhost:4000/api/student/create
![create student](https://github.com/dineshkumar-mb/Nodejs-assignmentor/assets/166787277/0286b7e1-dc37-47ea-b694-ba1be041e264)

3. GET Display All Mentors

http://localhost:4000/api/mentor/all-mentors

Display All Mentors

URL: /api/mentor/mentors

Description: Retrieves and displays the list of all mentors.

Method: GET

Example: http://localhost:4000/api/mentor/all-mentors

![display mentors](https://github.com/dineshkumar-mb/Nodejs-assignmentor/assets/166787277/265431dc-7e62-41c9-8848-505548c0bce7)

4. GET Display all Students

http://localhost:4000/api/student/all-students

GET Display All Students

URL: /api/student/students

Description: Retrieves and displays the list of all students.

Method: GET

Example: http://localhost:4000/api/student/all-students
![display students](https://github.com/dineshkumar-mb/Nodejs-assignmentor/assets/166787277/e2cb1c18-9deb-49d2-ab51-e693bfccf4df)


5. PUT Assign students to mentor

http://localhost:4000/api/mentor/assign/665719d090123c0986bbff2a

Assign Students to Mentor

URL: /api/mentor/assign/:id

Description: Assigns multiple students to a specific mentor.

Method: PUT

Example:http://localhost:4000/api/mentor/assign/665719d090123c0986bbff2a

![assign student to mentor](https://github.com/dineshkumar-mb/Nodejs-assignmentor/assets/166787277/cb552f17-fc2f-4918-b4e6-4498c634cf06)

6. PUT Change mntr for one std

http://localhost:4000/api/mentor/change-mentor/66571bbc01359215f8c7117c

Change Mentor for One Student

URL: /api/mentor/change-mentor/:id

Description: Changes the mentor for a specific student and records the previous mentor.

Method: PUT

Example:

http://localhost:4000/api/mentor/changementor/66571bbc01359215f8c7117c
![change mentor](https://github.com/dineshkumar-mb/Nodejs-assignmentor/assets/166787277/9f88b163-f909-4966-a39a-e0b0d9abadaf)


7. GET Display students of the mentor

http://localhost:4000/api/mentor/students/665716d86eebd693694b38a2

Display Students of the Mentor

URL: /api/mentor/students/:id

Description: Retrieves and displays the list of all students assigned to a specific mentor.

Method: GET

Example: http://localhost:4000/api/mentor/students/665716d86eebd693694b38a2
![display students of particular mentor](https://github.com/dineshkumar-mb/Nodejs-assignmentor/assets/166787277/44b64fa4-fea7-41c4-8415-48b999c45ccd)


8. GET Previous Mentor

http://localhost:4000/api/mentor/previous-mentors/66571bbc01359215f8c7117c

Previous Mentor

URL: /api/mentor/previous-mentors/:id

Description: Retrieves and displays the list of previous mentors for a specific student.

Method: GET

Example:

http://localhost:4000/api/mentor/previous-mentors/66571bbc01359215f8c7117c
![display previous mentor](https://github.com/dineshkumar-mb/Nodejs-assignmentor/assets/166787277/e8c6c772-f63a-4996-99e8-2b8259e2fa95)


The postman documentation link is as follows: https://documenter.getpostman.com/view/35182338/2sA3QtfC1k
