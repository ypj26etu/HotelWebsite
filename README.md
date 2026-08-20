# Crown Hotel Norwich

A full-stack hotel booking web application built for CMP-7003B Web Development at the University of East Anglia.

## Overview

Crown Hotel Norwich is a hotel booking system that allows customers to browse rooms, make bookings and manage their reservations. Hotel staff can manage check-ins, check-outs, housekeeping and view weekly reports.

## Tech Stack

- **Frontend:** HTML, CSS, vanilla JavaScript
- **Backend:** Node.js with Express
- **Database:** PostgreSQL
- **Templating:** EJS (staff pages)

## Features

### Customer
- Browse rooms with descriptions and rates
- Search availability by date, guests and room type
- View alternative rooms if requested type is unavailable
- Complete booking with payment details
- View and print booking confirmation
- Manage or amend an existing booking by reference and email

### Reception Staff
- View all rooms and today's bookings
- Check guests in and out
- Take and view payments with full payment history
- Amend bookings by reference number

### Housekeeping Staff
- View all checked out rooms awaiting preparation
- Mark rooms as available or unavailable

### Reports
- Weekly occupancy and revenue reports
- Daily occupancy bar chart
- Revenue breakdown by room type

## Getting Started

See [SETUP.md](./SETUP.md) for full installation instructions.

**Quick start:**

```bash
git clone https://github.com/ypj26etu/HotelWebsite.git
cd HotelWebsite
npm install
node app.js
```

Visit http://localhost:3000

## Staff Portal

Access via http://localhost:3000/html/staff-login.html

Passcode: `12345`

## Project Structure

```
HotelWebsite/
├── app.js              - Express server and all routes
├── bookings.js         - All database queries
├── config.js           - PostgreSQL connection config (create locally)
├── package.json        - Node.js dependencies
├── hotel-2026.sql      - Database schema and sample data
├── views/              - EJS staff page templates
└── public/
    ├── index.html      - Homepage
    ├── styles.css      - Main stylesheet
    ├── html/           - Customer HTML pages
    ├── scripts/        - Frontend JavaScript
    ├── stylesheets/    - Staff CSS
    └── assets/         - Images and videos
```

## Group

CMP-7003B Group C3 - University of East Anglia 2025-26
