# NOVA website

A clean, responsive static website for **NOVA — Your digital crutch**.

## Preview locally
Open `index.html` in a browser.

## Publish free with GitHub Pages
1. Create a GitHub repository for the website.
2. Upload `index.html`, `style.css`, and `script.js` to the repository root.
3. In the repository, open **Settings → Pages**.
4. Choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
5. GitHub will provide the public website address.

## Add the Windows download
The Windows download button is intentionally marked **Coming soon**. Do not advertise a download until you have a working, tested Windows package.

When the NOVA Windows package is ready:
1. Create a GitHub Release in your NOVA app repository.
2. Attach the tested installer (for example, `NOVA-Setup.exe`) to that release.
3. Edit `index.html`: replace the disabled download link in the `#download` section with the exact GitHub Release download URL, remove `aria-disabled="true"` and the `onclick` handler, and change the button text to **Download for Windows**.

## Notes
- Hosting this static site with GitHub Pages can be free, subject to GitHub's current plan limits and terms.
- This site itself does not provide an AI service or host an installer.
- No analytics, sign-in, payment, or API key is included.
