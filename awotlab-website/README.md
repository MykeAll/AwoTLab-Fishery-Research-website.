# AwoTlab Website — responsive static site

A polished, mobile-first website starter for AwoTlab, combining aquatic research, aquaculture business, analytics, academy, innovation and international collaboration.

## Run locally
1. Extract the ZIP.
2. Open `index.html` in a modern browser, or use VS Code Live Server for the best local preview.
3. Internet access is needed for Google Fonts and the remote editorial/hero photographs. The fish specimen gallery uses the photographs supplied with the brief and is stored locally.

## Project structure
- `index.html` — page structure, sections and metadata
- `assets/css/style.css` — visual design, responsive breakpoints, reduced-motion support
- `assets/js/app.js` — mobile navigation, hero carousel, scroll reveals, image lightbox and contact-form preview
- `assets/images/` — locally stored photos supplied for the AwoTlab fish gallery

## Before publishing
- Replace `YOUR-VERIFIED-EMAIL@example.com` in `assets/js/app.js` with the contact email approved by AwoTlab. The contact form currently prepares an email draft; it is not connected to a server.
- Confirm AwoTlab’s public phone number, physical location, social links and business details before adding them.
- Confirm the identity of each fish specimen before assigning a scientific/common species name. The supplied photographs are labelled as specimens pending verification; do not assume they are all marine fish or Clarias.
- Replace remote editorial imagery with properly licensed, organisation-owned, or otherwise approved photos before commercial launch. External image URLs require internet access and can change.
- Confirm publication titles and any research-impact statistics with Dr. Awotunde before publishing; this version avoids inventing metrics.
- Add a privacy notice and server-side form processing if collecting personal information.
- Test on current Chrome, Edge, Firefox, Safari, iOS and Android.

## Design notes
- Responsive layouts for large screens, tablets and mobile phones
- Hero image carousel with manual controls, autoplay, pause/resume and reduced-motion respect
- Keyboard-friendly mobile navigation and specimen image dialog
- Scroll reveal animations, section-aware navigation and progress bar
- Semantic headings, image alt text, focus styles and accessible form labels

## Deployment
This is a static HTML/CSS/JS project. It can be hosted on Netlify, GitHub Pages, Cloudflare Pages or any standard static host. Upload the contents of this folder (not the ZIP itself) to the hosting provider.
