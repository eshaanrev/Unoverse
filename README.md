# Unoverse

An interactive platform for learning Arduino programming and electronics. Unoverse combines step-by-step lessons, hands-on projects, and circuit explanations into one place, and tracks your progress as you work from the basics up to more advanced builds.

## Features

- Step-by-step lessons with live code examples
- Complete Arduino projects with wiring diagrams and explanations
- Interactive circuit diagrams and component breakdowns
- Progress tracking across lessons and completed projects
- Reference material on sensors, actuators, and modules
- Accounts with Google sign-in (Firebase Auth)

## Tech stack

- **Framework:** React 18 + TypeScript
- **Build tool:** Vite
- **Routing:** React Router
- **Styling:** Tailwind CSS
- **Animation:** Framer Motion
- **Backend:** Firebase (Authentication + Firestore)
- **UI:** lucide-react icons, react-hot-toast

## Setup

```bash
npm install
npm run dev          # start the dev server (Vite prints the local URL)
npm run build        # production build to dist/
npm run preview      # preview the production build
```

To run against your own backend, create a Firebase project, enable **Google** authentication and **Cloud Firestore**, and replace the `firebaseConfig` object in `src/lib/firebase.ts` with your project's web-app config. (Firebase web config values are safe to ship to the client; access is controlled by your Firestore security rules.)

Hosting is configured for Firebase Hosting (`firebase.json`); deploy the built `dist/` with `firebase deploy`.

## Screenshots

<!-- Add screenshots here -->
| Landing | Course / lesson | Dashboard |
| --- | --- | --- |
| _coming soon_ | _coming soon_ | _coming soon_ |
