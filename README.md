# Orbit — real-time messaging app

Responsive DM app built with React + Vite + Firebase Authentication + Firestore realtime listeners.

## Features
- Email/password signup and login
- User profiles and people search
- Direct conversations
- Live message updates and history
- Responsive desktop/mobile layout

## Setup
1. Create a Firebase project and register a Web App.
2. Enable **Authentication → Email/Password**.
3. Create a Firestore database.
4. Publish the included `firestore.rules` in Firestore → Rules.
5. Copy `.env.example` to `.env` and fill in the Firebase web config.
6. Run:
   ```bash
   npm install
   npm run dev
   ```

## Deploy
Build with `npm run build`. Connect this repo/branch to a web host such as Vercel and add the six `VITE_FIREBASE_*` environment variables. Firebase setup is required for real accounts and messages.

**Privacy:** the app stores display name and username in the user directory, not email. Firestore rules restrict conversations and message access to their two members. Never commit service-account keys.

## Status
Source and rules are committed. Firebase and hosting still need to be connected before launch.
