# Khashayar Pourtaheri's personal website

This is a small, dependency-free static site designed for GitHub Pages. It contains a home page, an about page, a research page, and the profile photo in the repository.

## Publish it

1. The repository is named `khashayar-pourtaheri.github.io`, matching the GitHub username `khashayar-pourtaheri`, so GitHub Pages serves it at the root address.
2. Upload these files and push them to the `main` branch.
3. In the repository, open **Settings → Pages** and set **Source** to **GitHub Actions**.
4. The included workflow will deploy the site whenever changes are pushed to `main`.

The site is published at `https://khashayar-pourtaheri.github.io/`. This root address works only while the repository name matches the GitHub username (`<username>.github.io`); any other name is served at `https://<username>.github.io/<repository-name>/`.

## Update content

- Edit `index.html` for the biography and contact details (`about.html` only redirects to the home page).
- Edit `research.html` to add papers and working projects.
- Replace `assets/files/Khashayar_Pourtaheri_CV.pdf` to update the CV. The web version omits the phone number.
- Replace `assets/images/khashayar-pourtaheri.jpg` to update the portrait (keep the same filename).

No site generator or package installation is needed: edit the HTML and CSS files directly, then push changes to GitHub.
