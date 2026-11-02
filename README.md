# FindBack – Campus Lost & Found System

**Republic Polytechnic | C237 Software Application Development**

## About the Project

FindBack is a web application designed to help students and staff report, search for and claim lost or found items on campus.

The system allows users to manage item reports, upload photos, search for missing belongings and submit ownership claims. Administrators can review claims and manage the return of items.

The application aims to make the lost-and-found process more organised and convenient.


## Key Features

- **User Authentication:** User registration, login and role-based access control.
- **Lost & Found Reporting:** Submit lost or found item reports with descriptions and optional image uploads.
- **Search & Filtering:** Search and filter items by category, location, report type and keywords.
- **Report Management:** Edit and delete personal item reports.
- **Claim Management:** Submit item claims and track their approval status.
- **Administrator Dashboard:** Review claims, approve or reject requests, and update item return statuses.


Key responsibilities included:

- Designed and developed the website interface using HTML, CSS, JavaScript and EJS.
- Built backend application features using Node.js and Express.js.
- Implemented user registration, login and session-based authentication.
- Developed lost and found item reporting forms with input validation and image uploads.
- Integrated MySQL to store and manage user accounts, item reports and claims.
- Implemented item searching, filtering, editing and deletion features.
- Developed item claiming functionality and administrator approval workflows.
- Tested application features and resolved issues to improve functionality.

## Technologies Used

| Category | Technologies |
|---|---|
| Frontend | HTML, CSS, JavaScript, EJS |
| Backend | Node.js, Express.js |
| Database | MySQL |
| Authentication | bcrypt, express-session |
| File Uploads | Multer |

## Application Workflow

1. Users register or log into FindBack.
2. Users submit reports for lost or found items.
3. Other users browse or search for matching items.
4. Users submit ownership claims.
5. Administrators review and approve or reject claims.
6. Item statuses are updated when belongings are returned.

## Running the Application Locally

**Requirements:**
- Node.js
- MySQL
- Database configuration and schema

**1. Install dependencies**

```bash
npm install
```

**2. Configure the database**

The application requires a MySQL database and a `dbConfig.js` configuration file.

Database credentials should be stored securely using environment variables.

**3. Start the application**

```bash
node app.js
```

**4. Open the application**

Visit `http://localhost:3000` in your browser.

**Note:** The repository does not currently include the database configuration file or SQL setup script. Additional configuration is required to run the application.

## Project Information

Developed as part of Republic Polytechnic's C237 Software Application Development module.
