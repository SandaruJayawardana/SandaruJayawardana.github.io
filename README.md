# Researcher Portfolio

A clean, professional academic portfolio site built for [GitHub Pages](https://pages.github.com/).

## Preview locally

Open `index.html` in your browser, or serve the folder:

```bash
python3 -m http.server 8000
```

Then visit [http://localhost:8000](http://localhost:8000).

## Customize

1. Edit `index.html` — replace placeholder name, affiliation, publications, and links.
2. Add your photo at `assets/images/photo.jpg` and update the hero section HTML.
3. Add your CV at `assets/cv.pdf` (or update the download link).
4. Adjust colors and fonts in `assets/css/style.css` (`:root` variables at the top).

## Deploy to GitHub Pages

1. Create a new repository on GitHub named `researcher-portfolio` (or `yourusername.github.io` for a user site).

2. Push this project:

```bash
git add .
git commit -m "Initial researcher portfolio"
git remote add origin git@github.com:YOUR_USERNAME/researcher-portfolio.git
git push -u origin main
```

3. In the repo on GitHub, go to **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
5. Choose branch `main` and folder `/ (root)`, then save.

Your site will be live at:

- **Project site:** `https://YOUR_USERNAME.github.io/researcher-portfolio/`
- **User site** (if repo is `YOUR_USERNAME.github.io`): `https://YOUR_USERNAME.github.io/`

## License

Content is yours to customize. Site template is free to use and modify.
