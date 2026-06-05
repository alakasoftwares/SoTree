# SoTree Static Website

This repository contains the static marketing and policy website for SoTree, built for direct hosting on GitHub Pages with plain HTML, CSS, JavaScript, and SVG assets.

## Preview locally

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080/`.

## Deploy with GitHub Pages

1. Push the site to your GitHub repository.
2. Open repository `Settings`.
3. Open `Pages`.
4. Set `Deploy from branch`.
5. Select `main` and `/ (root)`.

## Update before publishing

- Update the final GitHub Pages URL in `sitemap.xml` and `robots.txt` if the repository path changes.
- Add final App Store or Play Store links once those listings are available.

## Notes

- The current sitemap uses the placeholder base URL `https://bonchahere.github.io/SoTree/`.
- If your repo name or GitHub Pages path differs, update every sitemap entry before publishing.
