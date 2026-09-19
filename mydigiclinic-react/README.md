# MyDigiClinic React Client Demo

## Run locally
1. Open this folder in VS Code.
2. Open Terminal > New Terminal.
3. Run `npm install`
4. Run `npm run dev`
5. Open the localhost URL shown by Vite (normally http://localhost:5173).

## Demo flows
- Home -> Find Clinics -> Clinic -> Doctor -> Slot -> Booking -> Payment -> Patient Dashboard
- Login -> Doctor/Clinic -> Doctor Portal
- Register Doctor -> fill form -> Find Doctors -> new profile

Doctor registrations are stored in browser localStorage for this sales prototype. Do not use real patient medical/payment data.

## GitHub
Commit the project source to GitHub. For GitHub Pages, build with `npm run build` and deploy the generated `dist` folder using a Pages workflow. For the easiest Vite hosting, services such as Vercel/Netlify can import the GitHub repository directly. A production backend/database is intentionally not included in this prototype.
