# Mock Technical Repair Services

A static landing page mockup for a computer repair service. It introduces the service, lists common repair options, and provides a booking form layout.

## Features

- About section and navigation links
- Service descriptions for virus removal, hard drive replacement, hardware upgrades, and data recovery
- Booking form with contact, service, date, and additional-information fields
- Responsive navigation menu for narrow screens
- Current date displayed in the page header

## Run Locally

No build tools or package installation are required. Open `index.html` in a web browser, or serve this folder with any static file server.

## Project Files

- `index.html` - Page content and booking form markup
- `styles.css` - Layout, visual styles, and mobile responsive rules
- `index.js` - Displays the current date in the header

## Current Limitations

The booking form is currently a frontend mockup. It does not send appointment details to a server or save submissions. jQuery is loaded from a CDN in `index.html`; an internet connection is needed to load that external script, although the current date display is implemented with vanilla JavaScript.
