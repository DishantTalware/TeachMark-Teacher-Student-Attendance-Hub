TeachMark: Teacher & Student Attendance Hub
TeachMark is a Django-based Attendance System designed to streamline student attendance tracking efficiently. This web application enables students to mark their attendance by selecting a specific subject, ensuring accurate record-keeping. Simultaneously, teachers have the ability to monitor and mark attendance for their respective subjects, ensuring transparency and reliability.



Features
Student Attendance: Students can select a subject and mark their attendance easily.

Teacher Dashboard: Teachers can view and mark attendance for their subjects and apply for leave.

Subject-Based Tracking: Attendance is categorized and tracked by subject for better clarity and management.

User Authentication: Secure login system for students, teachers, and admins, ensuring access control and data security.



Installation:
First need to create venv
then activate venv

- create project
django-admin startproject student_attendance
cd student_attendance
py manage.py startapp appname




Set up your database:

python manage.py migrate
Create a superuser (optional, for admin access):
python manage.py createsuperuser


Run the development server:
python manage.py runserver

Open your browser and go to http://127.0.0.1:8000/ to access the application.


Usage
Students: Students can log in, select the subjects they are enrolled in, and mark their attendance.

Teachers: Teachers can log in, view their subject-wise attendance, mark attendance, and apply for leave.

Admin: Admins can manage the system, users, and perform other administrative tasks.



Technologies Used
Django - Framework for building the web application.

SQLite/PostgreSQL/MySQL - Database for storing attendance records.

HTML, CSS, JavaScript - Frontend technologies for creating a user-friendly interface.

Bootstrap - For responsive design.


Contributing
Feel free to fork this project, submit issues, or open pull requests for improvements or bug fixes. Contributions are welcome!
