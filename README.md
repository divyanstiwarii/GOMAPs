# GOMAPs — School Bus Tracker

🚌 **Real-time school bus tracking system** built with Firebase Realtime Database.

## Features

- **Live GPS Tracking** — Real-time bus location sharing via device GPS
- **Multi-Role Dashboard** — Separate views for Parents, Drivers, Conductors, and School Management
- **Firebase Authentication** — Role-based access control with email/password sign-in
- **Parent Live Links** — Shareable, time-limited location links for parents
- **Roll Call System** — Digital student boarding check-in
- **Activity Feed** — Real-time notifications across all roles
- **Parent Sign-Up** — Self-service parent registration with school approval workflow
- **Dark Mode Support** — Automatic theme detection with manual override
- **Mobile-First Design** — Responsive, touch-friendly interface

## Tech Stack

- Pure HTML/CSS/JavaScript (no build step required)
- Firebase Realtime Database for live data sync
- Firebase Authentication for user management
- Google Maps Embed API for map display
- Geolocation API for GPS tracking

## Setup

1. Create a Firebase project at [Firebase Console](https://console.firebase.google.com/)
2. Enable Email/Password authentication
3. Set up Realtime Database with appropriate rules
4. Update the `firebaseConfig` in `index.html` with your project credentials
5. (Optional) Add a Google Maps Embed API key for map display

## Deployment

This project is deployed on **Vercel** with auto-deploy from GitHub.

Every push to the `main` branch triggers a new deployment automatically.

## License

Private project — All rights reserved.
