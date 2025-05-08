# CoCreate Frontend Prototype

This is a frontend prototype for the CoCreate resource management platform. It demonstrates the key UI features including stock management, employee management, scheduling, reports, and dashboard overview.

## Features

- Dashboard overview with key indicators
- Resource (stock) management with add/delete functionality
- Employee and intern management with profile forms and list
- Scheduling and attendance management
- Reports and analytics with charts
- Login page UI (no backend authentication)
- Responsive design using Tailwind CSS
- Icons with Font Awesome
- Charts with Chart.js

## How to Run

1. Ensure you have Python 3 installed.

2. Open a terminal and navigate to the `cocreate-frontend` directory.

3. Run a simple HTTP server:

```bash
python3 -m http.server 8000
```

4. Open your browser and go to:

```
http://localhost:8000/index.html
```

5. Navigate through the pages using the top navigation bar.

## Notes

- This is a static frontend prototype with in-memory data management.
- No backend or database integration is included.
- Login functionality is not implemented.
- This prototype is intended for UI/UX demonstration and can be extended with backend APIs.

## Dependencies

- Tailwind CSS (via CDN)
- Google Fonts (Inter)
- Font Awesome (via CDN)
- Chart.js (via CDN)

## Future Work

- Backend integration with Java Spring Boot and MySQL
- Authentication and authorization
- Persistent data storage
- Email notifications
- Multilingual support

---
Created for CoCreate resource management platform prototype.
