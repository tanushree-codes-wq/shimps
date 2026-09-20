# SHIPMS — Smart Health Informatics and Patient Management System

A browser-based patient management system for a hospital/clinic: patient
registration, doctor records, appointment scheduling, diagnosis and
prescription tracking, billing, and an analytics dashboard.

This started as a Python console app backed by SQLite, and has been
rebuilt as a single-page web app so it can run anywhere with just a
browser — no install, no server.

## Features

- **Patients** — register, search, view, and delete records; expand a
  patient's full medical history inline
- **Doctors** — add and list staff with their specialization
- **Appointments** — book, view, and complete an appointment (completing
  one records a diagnosis and prescription automatically)
- **Billing** — generate bills, mark them paid, and track outstanding dues
- **Dashboard** — live stats: patient/doctor/appointment counts, revenue
  collected, outstanding dues, top diagnoses, and the busiest doctor

## Running it

It's a single self-contained HTML file — open `index.html` directly in
any modern browser, or serve the folder with any static file host
(e.g. GitHub Pages, Netlify, Vercel).

Data is stored in the browser's `localStorage`, so it persists between
visits on the same browser/device but is not shared across devices —
there is no backend server or database.

## Tech

Plain HTML, CSS, and vanilla JavaScript. No build step, no dependencies.

## License

MIT — see [LICENSE](LICENSE).
