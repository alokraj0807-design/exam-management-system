# ExamPro – Exam Management System

A responsive, frontend-only Exam Management System built with HTML, CSS and vanilla JavaScript.

## Run the project
1. Extract `exam-management-system.zip`.
2. Open the extracted folder in VS Code.
3. Open `index.html` in a browser, or use the VS Code Live Server extension.
4. Sign in with the demo credentials below.

## Demo login
- Email: `admin@exampro.com`
- Password: `admin123`

## Modules
- Dashboard with exam and result statistics
- Exam scheduling (create, edit, delete)
- Subject management (create, edit, delete)
- Student registration and printable hall tickets
- Simulated timed online examination with automatic scoring
- Answer sheet entry and evaluation
- Result processing and pass/fail calculation
- Printable student marksheets
- Result reports and CSV export

## Data storage
Data is stored in the browser's `localStorage`. It remains in that browser unless site data is cleared. Use the browser's developer tools to clear the `examProDB` localStorage key and restore the demo seed data by clearing the key.

## Important limitations
This is a frontend demo, not a production-ready examination platform. Login is a client-side demonstration only; there is no secure server authentication, database, multi-user access control, or server-side exam integrity. Do not use real student data or conduct high-stakes examinations with this version.
