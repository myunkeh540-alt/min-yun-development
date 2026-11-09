# Min Yun Development website

A responsive one-page freelance development website built with plain HTML, CSS and JavaScript.

## Preview locally
1. Extract the ZIP (if using the ZIP).
2. Open `index.html` in a browser.

## Before publishing
Open `index.html` and find `SITE_CONFIG` near the bottom:
- Set `whatsappNumber` to your WhatsApp number with country code and digits only, e.g. `60123456789`.
- Optionally set `emailAddress` to the email address where you want enquiries sent.

The enquiry form opens WhatsApp if a number is configured; otherwise it uses the configured email address. If neither is configured, it displays setup guidance. This static version does not store submissions in a database.

## Deploy
You can publish this static site using GitHub Pages, Netlify, or Vercel. Upload the `index.html` file (or connect the folder/repository) and follow the host's deployment steps.

## Important
The portfolio cards label QuickCut and ClothOS as in-development/planning work and VentureTrack as project work. Update these descriptions and statuses to match what you are comfortable showing publicly before launch.
