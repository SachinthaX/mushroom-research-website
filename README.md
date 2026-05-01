# Mushroom Research Website - Vite React

Single-page professional React website for:
**A Predictive Analytics Framework for Optimizing Mushroom Cultivation**

## Run locally
```bash
npm install
npm run dev
```

## Build for upload
```bash
npm run build
```
Upload the contents of the `dist/` folder.

## Replace Google Drive links
Open `src/App.jsx` and replace all values in the `driveLinks` object:
```js
const driveLinks = {
  charter: "PASTE_GOOGLE_DRIVE_PROJECT_CHARTER_LINK_HERE",
  proposal: "PASTE_GOOGLE_DRIVE_PROPOSAL_DOCUMENT_LINK_HERE",
  finalReport: "PASTE_GOOGLE_DRIVE_FINAL_REPORT_LINK_HERE",
  ...
}
```

Google Drive file access should be: **Anyone with the link → Viewer**.

## Replace team photos
Current team images are professional placeholder SVGs. Replace these files with real photos if needed:
- `public/images/team/dhananjaya.svg`
- `public/images/team/sachintha.svg`
- `public/images/team/yukthila.svg`

## Replace milestone marks/dates
Open `src/App.jsx` and update the `milestones` array.

## Important for course upload
This project uses Drive links for PDFs/slides to keep the uploaded site small. The React build is static HTML/CSS/JS after running `npm run build`.
