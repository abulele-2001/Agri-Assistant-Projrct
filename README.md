# AgriTech AI — Smart Farming Assistant

A responsive smart-farming dashboard portfolio project built with **HTML, CSS and vanilla JavaScript**. It is designed to publish as a static website on GitHub Pages.

## Features

- Responsive farm overview dashboard
- Crop register with add, search and remove actions
- Plant photo upload and preliminary crop inspection checklist
- Farming assistant chat with built-in demo responses
- Soil moisture and pH record form
- Equipment information hub
- CSV exports for crop and soil records
- Light/dark theme
- Browser-local storage for crop and soil records

## Run locally

You can open `index.html` in your browser, or use the Live Server extension in Visual Studio Code. No build step or package installation is required.

## Publish on GitHub Pages

1. Upload `index.html`, `README.md` and the `static` folder to the **root** of your GitHub repository.
2. Open the repository's **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Choose your publishing branch (usually `main`) and folder **/(root)**, then save.
5. Wait for the Pages deployment to finish and open the published link.

The `index.html` file must be in the repository root. Keep the `static` folder beside it, with `styles.css` and `app.js` inside.

## Important demo limitations

This is a front-end portfolio demonstration. The chat uses built-in responses, not a live AI model. The plant photo feature displays your selected photo and creates a general inspection checklist; it does **not** run trained image recognition or confirm plant disease. Weather readings and overview metrics are illustrative sample data, not a live weather feed or connected farm sensors. Crop and soil records are stored in the current browser only and are not synced to a server. Never use this demo as the sole basis for pesticide, disease-treatment or irrigation decisions.

## Tech stack

- HTML5
- CSS3 (responsive layout and dark theme)
- Vanilla JavaScript
- Browser `localStorage` and CSV downloads
