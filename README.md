# Mantra Quiz App

A full-featured quiz platform with Admin, Teacher, Student, and Projection modes.

## Requirements

- [Node.js](https://nodejs.org/) version 18 or higher

## Getting Started

1. **Install dependencies** (only needed once):
   ```bash
   npm install
   ```

2. **Start the development server:**
   ```bash
   npm run dev
   ```

3. **Open your browser** and go to:
   ```
   http://localhost:5173
   ```

## Demo Login Accounts

| Role    | Email                    | Password  |
|---------|--------------------------|-----------|
| Admin   | admin@mantra.edu         | admin123  |
| Teacher | teacher@mantra.edu       | teach123  |
| Student | student@mantra.edu       | stud123   |

## Features

- **Admin**: Approve registrations, manage classes & subjects, assign teachers to classes, assign subjects to students
- **Teacher**: Create & edit quizzes with custom timers, publish quizzes, launch Projection Mode
- **Student**: Attempt quizzes for their class & enrolled subjects, review results
- **Projection Mode**: Full-screen classroom display with large countdown timer and answer reveal

## Build for Production

```bash
npm run build
```

The built files will be in the `dist/` folder, ready to deploy.
