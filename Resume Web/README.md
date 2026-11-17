# Resume Portfolio

A minimalist, editorial‑grade personal finance portfolio website built for the **Web Development Mid‑Term Project** at IIM Bangalore.

## Features
- Dark Rolex‑green finance palette (`#0c1017` background, `#00a862` accents).
- Pure HTML5 & CSS3 – **no JavaScript**.
- Curated surreal collage artwork integrated throughout the site.
- Responsive layout with CSS Grid & Flexbox.
- Contact form using a `mailto:` action (no backend required).
- All images are transparent PNG/JPG assets stored locally.

## Project Structure
```
Resume Web/
├─ index.html          # Main page markup
├─ style.css           # Theme and component styles
├─ submission_report.html  # PDF‑ready report for the assignment
├─ README.md           # This file
├─ LICENSE             # MIT license
├─ .gitignore          # Git ignore rules
├─ assets/ (optional)  # Images – currently stored at the root for simplicity
│   ├─ profile.png
│   ├─ approach-untangle.jpg
│   ├─ outreach-handshake.jpg
│   ├─ reselling-growth.png
│   ├─ writing-hand.png
│   ├─ youth-parliament.png
│   ├─ yoga-flower.png
│   └─ contact-art.png
└─ *.pdf               # Reference PDFs (resume, notes)
```
> **Note**: The repository works directly from the root folder; the images are referenced by relative file names (e.g., `<img src="profile.png">`).

## Getting Started
```bash
# Clone the repo (replace <your‑repo> with the GitHub URL)
git clone https://github.com/<your‑username>/<repo>.git
cd <repo>
# Open locally (any static server works, or just open index.html in a browser)
# Example using Python’s simple HTTP server:
python -m http.server 8000
# Then navigate to http://localhost:8000
```

## Deploying to GitHub Pages
1. Push the repository to GitHub.
2. In the repository settings, enable **GitHub Pages** and select the `main` (or `master`) branch.
3. GitHub will publish the site at `https://<your‑username>.github.io/<repo>/`.

## License
MIT – see the `LICENSE` file for details.
