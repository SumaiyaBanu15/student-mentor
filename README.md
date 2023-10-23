Student Mentor Management System 

Through this system we can able to do create mentor, create students, assigned mentor for particular student,  assigned student for particular mentor, delete student and mentor, Select one mentor add many students.

Create Students : http://localhost:8000/students

Create Mentors : http://localhost:8000/students/mentor

Get all created Students : http://localhost:8000/students

Get all created Mentors : http://localhost:8000/students/allmentors

Assigned Mentor particular Student : http://localhost:8000/students/assignedMentor/:studName

Assigned Students for particular Mentor : http://localhost:8000/students/assingedStudents/:mentorName

Assigned new Mentor for particular Student : http://localhost:8000/students/assignMentor 

Previously Assigned Mentor for Particular Student : http://localhost:8000/students/previousMentor/:studName

Select One Mentor add many Students : http://localhost:8000/students/assignStudent

Delete Student : http://localhost:8000/students/:studName

Delete Mentor : http://localhost:8000/students/deleteMentor/:mentorId
