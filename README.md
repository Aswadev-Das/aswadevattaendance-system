# Attendly — Student Attendance Management

A responsive, browser-only student attendance dashboard. It runs without a server, account, or database.

## Open in VS Code

1. Download or clone this folder and open it in VS Code.
2. Open `index.html` in a browser. For convenient live reload, install the **Live Server** VS Code extension, right-click `index.html`, and choose **Open with Live Server**.

## Publish with GitHub Pages

1. Create a GitHub repository and add the files in this folder to its root.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**, choose `main` and `/(root)`, then save.
4. GitHub will show the published site URL in the Pages settings when it is ready.

## Features

- Dashboard with attendance summary, monthly calendar, and recent activity.
- Mark daily attendance and view or filter attendance records.
- Submit leave requests and complaints, then remove them from the browser.
- Add a profile photo and edit your display name and student ID.
- Dark mode, responsive layout, and local date formatting.
- Requests, profile, attendance, and theme are saved in this browser using `localStorage`. The sign-in session uses `sessionStorage` and ends when the browser tab session ends.

## Privacy and limits

This demo has no password, server, or identity verification: entering a name opens the dashboard. Data is stored on the device in that browser and is not shared with teachers or other devices. Clearing site data removes the saved profile and records. Uploaded profile photos are stored in browser storage (maximum 3 MB). The sample dashboard shows illustrative attendance figures until you begin recording attendance.
