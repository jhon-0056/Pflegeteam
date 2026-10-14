# B & B Ihr Pflegeteam

Static landing page for B & B Ihr Pflegeteam Sangerhausen GbR.

## GitHub Pages

`index.html` is the GitHub Pages entry point. The site has no build step and can be published from the repository root:

1. Push the repository to GitHub.
2. Open **Settings → Pages**.
3. Choose **Deploy from a branch**, select the `main` branch and `/(root)`, then save.

The page loads Tailwind, Lucide, AOS, Google Fonts, and the photos from external HTTPS CDNs. Visitors need an internet connection for these assets. The Tailwind browser CDN is convenient for this single-file page, but Tailwind documents it as a development option; compile Tailwind to a static stylesheet before using the site in a high-traffic production setting.

## Before public launch

- Confirm the phone number, email address, address, services, and service availability.
- Add the real Impressum and Datenschutzerklärung. The footer currently marks these as pending.
- Replace the demo care photos with photos approved by the care team if needed.

`bb-ihr-pflegeteam.html` is retained as the original local filename. Update it alongside `index.html` when changing the page.
