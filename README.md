# NCERC CampusMove — Ride Booking and Fee Management (Demo)

## Files
- `index.html` — Student login/register and website homepage
- `student-dashboard.html` — Submit ride requests, view ride history, fees and statements
- `admin-login.html` — Admin login
- `admin-dashboard.html` — Manage students, ride statuses, payments, exit dates and CSV reports
- `style.css` — Responsive styling
- `app.js` — Website logic and browser-local demo data

## Demo admin login
- Username: `admin`
- Password: `admin123`

Students register using their Student ID, name, department, semester and password.

## Fee rules
- ₹20 for each ride marked **Completed** by the admin.
- **Pending**, **Accepted**, **In Progress**, and **Cancelled** rides cost ₹0 until marked Completed.
- Admin can change each ride status from the student's ride-history table.
- Monthly/semester reporting should summarize the same completed rides, not create additional charges.
- Outstanding balance = completed ride charges − recorded payments (minimum ₹0).
- Exit date stops eligible ride charges after that date; it does not add a fixed monthly fee.

## Run locally
1. Extract the ZIP.
2. Open the folder in VS Code.
3. Use Live Server or open `index.html` in a browser.
4. Register a student account and add ride records.
5. Use the Admin Login link on the site and sign in with the demo credentials.
6. Select a student, mark rides Completed/Cancelled/Pending, then record payments or export CSV.

## GitHub Pages
Upload the files to the root of a GitHub repository. Open **Settings → Pages**, choose the `main` branch and `/ (root)`, then save.

## Important limitations
This is a front-end demonstration using browser `localStorage`; data does not sync across devices. Admin credentials and records are not secure enough for real student or financial data. For real deployment, use Firebase Authentication/Firestore or a secure backend with server-enforced role permissions and database security rules.

## College logo
In `index.html`, replace `YOUR_NEHRU_COLLEGE_LOGO_IMAGE_URL_HERE` with a direct URL to the approved college logo image.


Campus locations: Main Gate, Admission Block, Administrative Office, Principal’s Office, Accounts Office, CSE Block, AI & Data Science Lab, Computer Lab, Electronics Lab, Electrical Lab, Mechanical Workshop, Civil Engineering Lab, Central Library, Canteen, Auditorium, Seminar Hall, College Bus Stop, Parking Area, Hostel, Sports Ground, Indoor Recreation Area, Medical Room, Workshop Block. These are suggested sample stops; adjust them to match the actual campus.
