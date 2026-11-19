# Gangotri Medical Agency Website

This is the editable source for the static website.

## Editing

- Edit page content and contact information in `index.html`.
- Edit layout and styling in `assets/css/style.css`.
- Medicines and surgical information are in `medicines.html` and `surgical.html`.
- Images are in `assets/img/`; the page header and footer use editable text instead of a logo.

The site includes all 43 supplied partner-company names in an editable,
searchable A–Z directory, along with the directory facts: 19 A–Z groups,
serving since 1995, the Balaghat address (R58P+XQV, Gouli Mohalla,
Chitragupt Nagar, Madhya Pradesh 481001), and two order-desk phone numbers.
The shared stylesheet applies a light cyan and white theme across the pages.
The Medicines page contains the 43 supplied pharmaceutical companies. Add the
surgical supplier names to `surgical.html` when available.
The Balaghat map is available on the home, Medicines, and Surgical pages, with
a Google Maps link as a fallback if the embedded map does not load.

To preview the site locally, serve this folder with a static web server and
open its `index.html` page.

## Deploy on Netlify

This is a static site and does not need a build command. The `netlify.toml`
configuration publishes this folder directly.

1. Sign in to Netlify at https://app.netlify.com/.
2. Choose **Add new site** and select the manual deployment option.
3. Upload this project folder (the folder containing `index.html` and
   `netlify.toml`).
4. Open the site URL Netlify provides.
