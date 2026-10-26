# Digital Attendance System

A simple web-based attendance management system designed for Harsha Institution of Management Studies. It helps faculty members mark student attendance quickly, search students, and export daily attendance records.

## Features

- Teacher login page with username/password validation
- Class-wise attendance tracking for BCA 1st, 2nd, and 3rd Year
- Individual student present/absent toggle
- Search students by name or roll number
- Mark all students present/absent in one click
- Save attendance data in browser local storage
- Export attendance records to CSV
- Responsive and lightweight front-end design

## Tech Stack

- HTML
- CSS
- JavaScript
- Browser localStorage for persistence

## Live Demo

[Open Live Demo](https://abinkr.github.io/attendance_project/)

## Project Structure

```bash
CollegeProjectDigitalAttendance/
├── index.html          # Login page
├── index.css           # Login page styling
├── index.js            # Login logic
├── at.html             # Attendance dashboard
├── at.css              # Attendance page styling
├── README.md           # Project documentation
└── LICENSE             # Optional project license (if added later)
```

## Login Credentials

Use the following credentials on the login page:

- Username: `harsha`
- Password: `12345678`

## How It Works

1. Open `index.html` in a browser.
2. Log in with the username and password above.
3. Choose the class from the top buttons.
4. Mark each student as present or absent.
5. Search for a student by roll number or name if needed.
6. Export the attendance as CSV for records.

## Data Storage

This project uses browser localStorage to store attendance data, so the records remain available even after refreshing the page or reopening the browser.

## Getting Started

### Option 1: Open directly

Open `index.html` in your browser.

### Option 2: Run a local server

```bash
python -m http.server 8000
```

Then open:

```bash
http://localhost:8000
```

## Notes

- This is a frontend-only project.
- It is designed for demonstration and educational use.
- Authentication is hardcoded for learning/demo purposes and should not be used in production without a proper backend.

## Future Improvements

- Add backend authentication and database storage
- Support multi-device syncing
- Add admin and faculty roles
- Generate monthly reports and analytics
- Improve security for production deployment

## License

This project is currently provided for educational/demo use. Please check the repository for the license file if one is added.

## Developer Information

- Project: Digital Attendance System
- Institution: Harsha Institution of Management Studies
- Stack: HTML, CSS, JavaScript
- Status: Active demo/development project

## Security Note

This application is a prototype. The current login system uses hardcoded credentials and is not suitable for real-world production use. For real deployment, use secure authentication, hashing, HTTPS, and a backend database.
