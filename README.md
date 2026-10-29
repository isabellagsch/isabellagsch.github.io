# Isabella Gschossmann — academic website

This is a static HTML website prepared for GitHub Pages. `index.html` is the homepage; the other pages and files are in the repository root and `assets/`.

## Put the site on GitHub Pages

The connected GitHub account is `isabellagsch`. Create a **public** repository named `isabellagsch.github.io` and leave it empty (do not add a README or license during creation). Then, from this folder, run:

```sh
git init -b main
git add .
git commit -m "Set up academic website"
git remote add origin https://github.com/isabellagsch/isabellagsch.github.io.git
git push -u origin main
```

In the repository, open **Settings → Pages** and choose **GitHub Actions** as the publishing source. The included workflow deploys the site automatically after each push. The default address will be `https://isabellagsch.github.io/`.

## Use a custom domain

Buy a domain from a registrar, add it under **Settings → Pages → Custom domain**, and then set the DNS records GitHub shows for that domain with the registrar. GitHub recommends verifying domain ownership first. Their guide covers the record types and values: <https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site>.

## Site files

- `index.html`: welcome page and contact details
- `research.html`: working papers
- `policy-publications.html`: policy publications
- `assets/Isabella_Gschossmann_CV.pdf`: current CV
- `assets/portrait.jpg`: current photo placeholder

The site uses locally bundled Lato fonts, with its license in `assets/fonts/OFL.txt`, and Imperial-inspired dark blue accents.
