# Bustimetable SL

Bustimetable SL is a Firebase-hosted web application that helps commuters in Sri Lanka access up-to-date bus timetables and fare information. The platform is live with dedicated experiences for customers, depot timekeepers, and system administrators.

## Features
- **Customer portal** – Browse timetables, look up fares, and keep track of favourite routes.
- **Admin console** – Manage route data, update schedules, and oversee platform activity.
- **Timekeeper workspace** – Publish real-time timetable adjustments and confirm departures.
- **Firebase authentication** – Secure, role-based sign-in flows for all three user types.

## Technology stack
- [Firebase Hosting](https://firebase.google.com/docs/hosting) for static site delivery
- [Firebase Authentication](https://firebase.google.com/docs/auth) for multi-role login flows
- [Cloud Firestore](https://firebase.google.com/docs/firestore) (or Realtime Database) for storing timetable and fare data
- Modern front-end tooling (e.g., React or vanilla JavaScript) for building responsive user interfaces

## Deployment
The production instance is deployed on Firebase. Any updates to the application are built and deployed through the Firebase CLI, ensuring fast, reliable releases.

## Getting started
1. Clone the repository.
2. Install the project dependencies.
3. Create a Firebase project and configure the necessary services (Hosting, Authentication, Firestore/Realtime Database).
4. Add the Firebase configuration to the application.
5. Run the local development server and deploy with `firebase deploy` once changes are ready.

> **Note:** The source code is not yet committed to this repository. Adding the implementation, configuration files, and deployment scripts will make it easier for collaborators to contribute.

## Roadmap
- Publish the production-ready source code and Firebase configuration samples.
- Document data models for routes, stops, timetables, and fares.
- Add screenshots or a demo video of customer, admin, and timekeeper experiences.
- Provide testing instructions and set up CI/CD automation for future contributions.

## License
Specify the project license here (e.g., MIT, Apache 2.0) so others know how they can use and contribute to the project.
