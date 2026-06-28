# AI SOC Dashboard

A simple static Artificial Intelligence Security Operations Center dashboard built with HTML, CSS, and JavaScript only.

## Features

- Dashboard metrics for Total Alerts, Critical Alerts, and Safe Systems.
- Log Upload with simple AI-style log analysis for failed logins and suspicious activity.
- Threat Detection grouped by High, Medium, and Low severity.
- Alert Management with Open and Resolved status controls.
- Security Report page with CSV download.
- Login session flow using `localStorage`.

## Files

- `index.html` - Login page.
- `dashboard.html` - Main SOC dashboard.
- `report.html` - Security report and CSV export page.
- `style.css` - Dark responsive cybersecurity theme.
- `script.js` - Login flow, protected pages, sample data, log analysis, alert status controls, and CSV download.
- `sample_logs.csv` - Sample security logs for upload testing.
- `README.md` - Project documentation.

## How to Run

Open `index.html` in any modern browser and sign in with the demo credentials.

Username: `admin`

Password: `admin123`

No backend, database, package installation, or build step is required.

## Deployment

This project is ready for GitHub Pages or Vercel as a static site.

For GitHub Pages, upload the files to a repository and enable Pages from the repository settings.

For Vercel, import the repository and deploy it as a static project.
