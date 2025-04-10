# job-sequencing-system
This is a simple Job Sequencing System created using HTML, CSS (Bootstrap), and JavaScript. It allows Admin users to manage employees and assign jobs. Employees can log in to view their assigned jobs.

Features
Role-based Login System
Admin can:

Add new employees

Assign jobs to employees

Employee can:

View only the jobs assigned to them

Job Details

Job Title

Assigned Employee

Due Date

Priority (High, Medium, Low)

Data Storage

Uses browser's localStorage to store employees and jobs

Data remains available unless manually cleared from browser

UI/UX

Clean and responsive interface using Bootstrap 5

How to Use
Clone or download this repository.

Open the index.html file in a web browser.

Use the login section to enter a username and select a role (Admin or Employee).

If logged in as Admin:
You can add employees and assign jobs.

If logged in as Employee:
You will only see jobs assigned to you.

All data (employees and jobs) will be stored in localStorage automatically.

File Structure
index.html → Main project file with HTML, embedded CSS and JavaScript
README → Project documentation

Technologies Used
HTML5

CSS3

Bootstrap 5

JavaScript

Browser localStorage

Limitations
This is a frontend-only project. There is no backend or database integration.

Data is not shared across browsers or devices. It is stored locally in the browser.

Future Improvements
Add authentication for users

Connect with a real backend (e.g., Node.js, Firebase)

Add job status (In Progress, Completed, etc.)

Dashboard with filters and search

License
This project is open-source and free to use.

