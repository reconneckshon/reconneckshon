# Reconneckshons Wellness Center website

A plain static site (HTML, CSS, one small JS file). No build step, no framework.

```
index.html      Home: hero, what we offer, FAQ, responsibility notice, contact + map
about.html      About us: founder, story, mission and vision, values
gallery.html    Gallery
css/style.css   All styles
js/main.js      Mobile menu toggle
images/         Favicon, plus the photos you add (see below)
```

## Add the photos

The pages look for these files and show a soft placeholder until they exist.
Portrait crop, about 3:4 (for example 1200 x 1600), JPG, under about 300 KB each.

- `images/venise-samuels.jpg` (About page)
- `images/gallery/hillside.jpg`
- `images/gallery/yoga-meditation.jpg`
- `images/gallery/light-therapy.jpg`
- `images/gallery/prayer-space.jpg`
- `images/gallery/wellness-products.jpg`
- `images/gallery/community.jpg`

## Publish on GitHub Pages

1. Create a new repository on GitHub (for example `reconneckshons-site`).
2. From this folder: `git remote add origin https://github.com/<your-username>/reconneckshons-site.git` then `git push -u origin main`.
3. In the repository, open Settings > Pages, choose "Deploy from a branch", pick `main` and `/ (root)`, and save.
4. The site goes live at `https://<your-username>.github.io/reconneckshons-site/`.

## Using www.reconneckshons.com

Only do this when you are ready to switch over from Framer. Add a file named `CNAME` containing `www.reconneckshons.com`, set the custom domain in Settings > Pages, and point the domain's DNS `www` CNAME record at `<your-username>.github.io`.
