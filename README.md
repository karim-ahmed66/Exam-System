# Exam System

A front-end prototype of an online examination system with two separate portals — one for **students** and one for **admins** (instructors).

> Built during my early web-development training (2023) to practise page structure, forms and multi-page navigation with plain HTML & CSS.

## Features

**Student portal**
- Login page

**Admin portal**
- Admin login and registration
- Dashboard ("missions") linking to all management pages
- Add courses
- Create exams and add questions to them
- Add, update and delete students
- Manage student scores

## Project structure

```
Exam-System/
├── index.html              # Landing page: choose Student or Admin login
├── CSS/master.css          # Shared styles
├── JS/main.js
├── assets/Images/
└── Components/
    ├── Student/Login.html
    └── Admin/
        ├── admin-Login.html
        ├── Register/
        └── Messions/       # Courses, exams, questions, students, scores
```

## Tech

HTML5 · CSS3

## Run locally

No build step — clone the repo and open `index.html` in a browser.

## Status

UI prototype only: pages are static and there is no backend or data persistence.

---

Made by [Karim Ahmed Hamdy](https://github.com/karim-ahmed66) · [LinkedIn](https://www.linkedin.com/in/karim-ahmed-hamdy)
