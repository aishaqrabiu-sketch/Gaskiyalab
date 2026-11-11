# Gaskiya Medical Diagnostics and Research Laboratory - LIMS

A single-page laboratory information system (patients, test orders, results, culture and seminalysis reports, printing).

## Host on GitHub Pages
1. Create a new repository on GitHub (e.g. `gaskiya-lims`).
2. Upload the files from this zip (`index.html`, `.nojekyll`, `README.md`) to the repository root.
3. Go to **Settings > Pages**, set **Source** to "Deploy from a branch", choose branch `main` and folder `/ (root)`, then Save.
4. After a minute your site is live at `https://YOUR-USERNAME.github.io/gaskiya-lims/`.

## Important
- Data is saved in each browser's local storage. It does not sync between devices and is lost if browser data is cleared.
- A public GitHub Pages site is visible to anyone with the link. Do not rely on this version for confidential patient records without a proper backend and login.

## Logging in
The home screen has two options:
- **Admin / Staff** - enter the admin PIN (the first time, create one) to manage patients, orders, results and the test catalog.
- **Patient Results** - patients enter their full name or phone number to view and print only their completed results.

You can also send patients straight to the patient view by adding `#results` to the site address, e.g. `https://YOUR-USERNAME.github.io/gaskiya-lims/#results`.
