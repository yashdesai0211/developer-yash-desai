# Developer Yash Desai — Website

A responsive, multi-page static portfolio website designed for GitHub Pages.

## Pages
- `index.html` — Home
- `services.html` — All five services
- `projects.html` — Project gallery and case studies
- `about.html` — Developer profile
- `contact.html` — Email and Instagram contact links

## Included
- Dark and light theme toggle (preference is remembered in the browser)
- Responsive mobile navigation
- Project category filters
- User-provided profile photo in `assets/yash-profile.jpg`
- No build step or server required

## Preview locally
Open `index.html` in a browser. For best results, use a local static server or the VS Code Live Server extension if already available.

## Publish with GitHub Pages
1. Create or open a GitHub repository for this website.
2. Extract this ZIP on your device.
3. Upload the *contents* of this folder to the repository root. `index.html` must be at the root, not inside another nested folder.
4. Commit the upload.
5. In GitHub, open **Settings → Pages**.
6. Under **Build and deployment**, choose **Deploy from a branch**.
7. Choose branch `main` and folder `/(root)`, then save.
8. Wait for deployment and open the Pages URL shown by GitHub.

## Update contact details
Email and Instagram appear in `contact.html`, `index.html`, `services.html`, `projects.html`, and `about.html` footers. Search the repository for:
- `firstforgestudio.games@gmail.com`
- `its_yashhh02`

Replace all matching instances if you change them.

## Add a project
In `projects.html`, copy one `<article class="project-card" ...>` block inside `.projects-page-grid`, then update:
- `id` (must be unique)
- `data-category` (`web` or `software`)
- project title, description, tags and case study
- website link, if there is a real public URL

The homepage featured projects are separate cards in `index.html`; update those too if you want the new project featured there.

## Notes
- This is a static website, so it does not include a database, login, admin panel or server-side enquiry form.
- The email enquiry button opens the visitor's email app using a `mailto:` link.
- The completed Rushabh portfolio link is included: https://yashdesai0211.github.io/rushabh-the-editor/. Laxmikant Sir Hindi is linked to its published website: https://yashdesai0211.github.io/laxmikant-mishra-website/.
- The Android game is shown as a project description only; there is no APK download link.
- Google Fonts are loaded online when available; fallback fonts are included.
