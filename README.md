# ICMT Faculty Directory

Official centralized faculty directory and academic information portal for the **International Council for Management & Technology (ICMT)**.

## Project Structure

```text
ICMT_FACULTY_DIRECTORY/
├── index.html              # Main Public Entry Page (Overview, Key Metrics & CTAs)
├── faculty.html            # Public Faculty Information Page
├── public-directory.html   # Public Faculty Directory (Search, Filter, Grid/Table & Modal)
├── member-profile.html     # Dedicated Standalone Public Member Profile (?id=ICMTxxx)
├── admin.html              # Admin Workspace (Login, Dashboard, Member Management, Users, Logout)
│
├── css/
│   └── style.css           # Core Application Stylesheet
│
├── js/
│   ├── app.js              # Admin Application Logic
│   └── member-data.js      # Single Source of Truth (All 343 records + embedded photos)
│
└── images/
    └── new/                # Clean Faculty Portrait Photos
```

## Navigation Flow

1. **Public User Journey**:
   `index.html` (Public Home) &rarr; `faculty.html` (Faculty Info) &rarr; `public-directory.html` (Directory) &rarr; `member-profile.html` (Member Profile)

2. **Administrator Access**:
   `index.html` / `public-directory.html` &rarr; **Admin Login** &rarr; `admin.html` (Dashboard & Member Management)

## GitHub Pages Deployment

This repository is structured so that `index.html` is the root public entry page. It is immediately ready for GitHub Pages hosting (Settings &rarr; Pages &rarr; Source: `main` branch / root).
