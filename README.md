# ICMT Faculty Directory & Academic Portal

Official centralized faculty directory and academic information portal for the **Indian Commerce and Management Teachers (ICMT)** — built as a seamless extension of the main ICMT platform ([https://sites.google.com/view/icmtmembers/home](https://sites.google.com/view/icmtmembers/home)).

## Project Structure

```text
ICMT_FACULTY_DIRECTORY/
├── index.html              # Public Faculty Overview & Portal Entry
├── faculty.html            # Public Faculty Information & Mentors Page
├── public-directory.html   # Public Faculty Directory (Search, Filter, Grid/Table & Modal)
├── member-profile.html     # Dedicated Standalone Public Member Profile (?id=ICMTxxx)
├── admin.html              # Admin Workspace (Login, Dashboard, Member Management, Users, Logout)
├── README.md               # Documentation & Navigation Architecture
│
├── css/
│   └── style.css           # Core Application Stylesheet (Lato font & ICMT teal theme)
│
├── js/
│   ├── app.js              # Admin Application Logic
│   └── member-data.js      # Single Source of Truth (All 343 records + embedded portraits)
│
└── images/
    └── new/                # Clean Faculty Portrait Photos
```

## Navigation Flows

1. **Public Flow**:
   ICMT Main Website &rarr; **Faculty** &rarr; **Faculty Information** (`faculty.html`) &rarr; **Faculty Directory** (`public-directory.html`) &rarr; **Member Profile** (`member-profile.html`)

2. **Admin Flow**:
   **Admin Login** &rarr; **Dashboard** &rarr; **Member Management** &rarr; **User Management** &rarr; **Logout** (`admin.html`)

## GitHub Pages Deployment

This repository is structured so that `index.html` is the root public entry page with relative paths. It is immediately ready for GitHub Pages hosting (Settings &rarr; Pages &rarr; Source: `main` branch / root).
