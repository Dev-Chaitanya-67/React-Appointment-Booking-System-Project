
# Student Teacher Appointment Booking System

<p align="center">
    <img src="https://readme-typing-svg.herokuapp.com?font=Montserrat&weight=700&size=28&pause=1000&color=1F7A8C&center=true&vCenter=true&width=700&lines=Student+Teacher+Appointment+Booking+System;Role-based+React+%2B+Firebase+workflow;Appointments%2C+schedules%2C+and+messages+in+one+place" alt="Typing banner" />
</p>

<p align="center">
    <img src="https://skillicons.dev/icons?i=react,firebase,bootstrap,js,css,html" alt="Tech icons" />
</p>

<p align="center">
    <a href="https://collegeappointments.netlify.app/">
        <img src="https://img.shields.io/badge/Live%20Demo-Netlify-00C7B7?style=for-the-badge&logo=netlify&logoColor=white" alt="Live demo" />
    </a>
    <img src="https://img.shields.io/badge/Frontend-React-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React" />
    <img src="https://img.shields.io/badge/Backend-Firebase-F5820D?style=for-the-badge&logo=firebase&logoColor=white" alt="Firebase" />
    <img src="https://img.shields.io/badge/Styling-CSS%20%2B%20Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Styling" />
</p>

## Overview

This project is a role-based appointment booking platform for educational institutions. Students can register, wait for approval, browse teachers, book time slots, and send messages. Teachers manage schedules, review requests, and respond to students. Admins control the onboarding flow by approving student registrations and adding teachers.

## Live Demo

Open the deployed app here: [https://collegeappointments.netlify.app/](https://collegeappointments.netlify.app/)

## Key Features

- Student registration with admin approval before access is granted.
- Teacher onboarding managed by admin with login-based access.
- Role-aware navigation for admin, teacher, and student dashboards.
- Teacher schedule creation and appointment request management.
- Student appointment booking, tracking, and profile management.
- Message flow between students and teachers for appointment context.
- Responsive UI built with React, CSS, Bootstrap, and Firebase.

## How It Works

1. Students register from the public flow and wait for admin approval.
2. Teachers are added by the admin and sign in with their account.
3. Students browse teacher availability and book appointments.
4. Teachers create schedules, review requests, and handle messages.
5. Admin keeps the system organized by approving registrations and managing teachers.

## Tech Stack

- Frontend: React, React Router
- Styling: CSS, Bootstrap, React Bootstrap, styled-components
- Backend: Firebase Authentication, Firebase Firestore
- Utility Libraries: date-fns, react-datepicker
- Hosting: Netlify

## Project Structure

```text
Appointment-Booking-System/
├── package.json
├── package-lock.json
├── public/
│   ├── index.html
│   └── style.css
└── src/
    ├── App.js
    ├── firebase.js
    ├── index.js
    └── pages/
        ├── main.jsx
        ├── auth.css
        ├── Admin/
        │   ├── addTeacher.jsx
        │   ├── admin.css
        │   ├── adminConfig.js
        │   ├── ApproveStudents.jsx
        │   ├── UpdateTeacherModal.jsx
        │   └── ViewTeachers.jsx
        ├── Authorization/
        │   ├── Choose.css
        │   ├── Choose.jsx
        │   ├── PasswordResetModalTeacher.jsx
        │   ├── register.jsx
        │   ├── StudentLogin.jsx
        │   └── TeacherLogin.jsx
        ├── Navigation/
        │   ├── navbar.css
        │   └── navbar.jsx
        ├── Student/
        │   ├── BookAppointment.jsx
        │   ├── GetAppointment.jsx
        │   ├── MyAppointments.jsx
        │   ├── MyProfile.css
        │   ├── student.css
        │   └── StudentProfile.jsx
        └── Teacher/
            ├── Message.jsx
            ├── MessagePopup.css
            ├── MyProfile.css
            ├── Requests.jsx
            ├── Schedule.jsx
            ├── teacher.css
            ├── TeacherProfile.jsx
            └── ViewSchedule.jsx
```

## Navigation Map

- Start here: `src/pages/main.jsx`
- Shared shell and dashboard menu: `src/pages/Navigation/navbar.jsx`
- Public auth and landing flow: `src/pages/Authorization/`
- Admin tools: `src/pages/Admin/`
- Teacher tools: `src/pages/Teacher/`
- Student tools: `src/pages/Student/`

## Local Development

If you want to run the app locally, install dependencies and start the React dev server.

```bash
npm install
npm start
```

To create a production build:

```bash
npm run build
```

## Screenshots

The original project included multiple dashboard screenshots. If you want, this README can be extended with a polished gallery section using local image assets from the project.

## Author

- Chaitanya Wagh

## Links

- GitHub: [https://github.com/Chaitron67](https://github.com/Chaitron67)
- LinkedIn: [https://www.linkedin.com/in/chaitanya-wagh-3575932ba/](https://www.linkedin.com/in/chaitanya-wagh-3575932ba/)

---

Built for a smoother student-teacher scheduling workflow.
