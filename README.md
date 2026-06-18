# Static Preview and Local Run

This repository is a Next.js app. Two easy ways to view the site:

1) Static preview (quick, works by double-clicking in a browser)

- Open `index.html` in your browser. It now includes the homepage, products, cart, account, checkout, orders, wishlist, track-order, login, and signup previews in one file.

2) Full development server (dynamic, recommended)

- Install dependencies: `pnpm install`
- Start dev server: `pnpm dev`
- Open: `http://localhost:3000`

Notes:

- I updated the `lint` script in `package.json` to avoid failures when ESLint isn't installed.
- The full app uses React/Next.js — run the dev server for dynamic behavior and server-side routes.

## Android App Preparation

This project is set up for Capacitor Android.

1. Install dependencies: `pnpm install`
2. Start the web app: `pnpm dev`
3. Open Android Studio: `pnpm exec cap open android`
4. Run the app on an emulator or device.

Note: The Android app is configured to load the local web app from `http://10.0.2.2:3000`.
