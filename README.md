# Jay Kang academic website

Plain HTML/CSS academic website, ready for GitHub Pages.

## Structure

```text
.
├── index.html
├── research.html
├── teaching.html
├── cv.html
├── workshop.html
├── 404.html
├── .nojekyll
└── assets/
    ├── css/style.css
    ├── img/profile-placeholder.svg
    └── files/
```

## Edit checklist

1. Replace `assets/img/profile-placeholder.svg` with your photo.
   - Recommended: save your photo as `assets/img/profile.jpg`.
   - Then change the image source in `index.html` from `profile-placeholder.svg` to `profile.jpg`.
2. Replace placeholder research links in `research.html` with real PDF/slides links.
3. Add your Google Scholar link in `index.html`.
4. If you want a PDF CV, put it in `assets/files/Jay_Kang_CV.pdf` and update the button in `cv.html`.
5. Update workshop date, room, and final program in `workshop.html`.
6. Update the footer year or affiliation if needed.

## Deploy on GitHub Pages

### Easiest route: user website

1. Create a repository named exactly `<your-github-username>.github.io`.
2. Upload all files in this folder to the repository root.
3. Go to repository **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose branch `main` and folder `/root`, then save.
6. Your site will appear at `https://<your-github-username>.github.io/`.

### Updating the website

After deployment, edit the HTML/CSS files and push the changes. GitHub Pages will redeploy automatically.
