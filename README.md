# SwipeClean — Privacy Policy Website

This folder contains a ready-to-publish static privacy policy for SwipeClean.

How to publish on GitHub Pages:

1. Create a new **public** repository on GitHub (e.g. `swipeclean-privacy`).  
2. On your local machine, in the project root run:

```bash
git init
git add website/*
git commit -m "Add privacy policy website"
git branch -M main
git remote add origin https://github.com/<your-username>/swipeclean-privacy.git
git push -u origin main
```

3. In the GitHub repository settings → Pages, set "Source" to `main / / (root)` or `main / /docs` depending on where you pushed. If you pushed `website/` files to root, use root.  
4. After saving, GitHub will publish a URL like `https://<your-username>.github.io/swipeclean-privacy/`. Use that URL in Play Console as the Privacy Policy URL.

If you prefer, push the `website/` contents into a `gh-pages` branch and enable GitHub Pages from that branch.

If you want, I can provide the exact git commands to push from your local clone or help create the repo.

