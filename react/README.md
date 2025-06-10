# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration
If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.


# Students and Studies – Student Management System

## Project Description
An interactive web-based system for students, including login, signup, forums, summaries, profile editing, and an admin dashboard. Users can manage their personal data, upload summaries, manage resumes, and participate in forum chats. Authentication is handled via Firebase Authentication.

## Main Features

* Login and registration using Firebase
* Home page displaying user details
* Forum system with chat functionality
* Summaries page for adding, editing, and deleting notes
* Admin dashboard with statistics on users, summaries, and forums
* Profile editing page including resume management
* Navigation between pages using a top menu

## Live Demo Link
 No live demo available for this project.

## Installation & Local Run Instructions

### Prerequisites
* Node.js
* npm

### Steps
```bash
git clone https://github.com/<your-username>/<your-repo>.git
cd react
npm install
npm run dev
```

## Project Folder Structure
```
react/
├── public/
├── src/
│   ├── assets/            # Images and styles
│   ├── firebase/          # firebase.js
│   ├── view/              # All system pages
│   └── components/        # Shared components (Navigation)
├── vite.config.js
├── package.json
└── README.md
```

## Technologies Used
* React.js
* Vite
* Firebase Authentication
* CSS Modules
