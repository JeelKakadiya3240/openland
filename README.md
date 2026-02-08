# Open View Landscape And Tree Service – Website

A simple, professional website for **Open View Landscape And Tree Service** (Tempe, AZ): tree removal, landscaping, masonry, and related services.

## What’s included

- **Single-page site** with: Hero, Why Choose Us, Services, About, Reviews, Gallery, Contact
- **Content** taken from the business’s Yelp listing (services, highlights, about, sample reviews)
- **Responsive layout** for mobile and desktop
- **Landscape-themed design** (greens, cream, clear typography)

## How to run locally

1. Open the folder in your editor (e.g. Cursor).
2. Open `index.html` in a browser (double-click or “Open with” your browser).
3. Or run a simple local server, e.g.:
   - `npx serve .`
   - or use the “Live Server” extension in VS Code/Cursor.

## Before going live – update these

1. **Phone number**  
   In `index.html`, search for `(480) 555-1234` and replace with the business’s real number in both the header “Call for Free Estimate” link and the Contact section.

2. **Yelp link**  
   In the Contact section there’s a generic Yelp link. Replace it with the actual Yelp business URL so “Leave a review” goes to their page.

3. **Gallery photos**  
   The “Our Work” section uses placeholder boxes. Replace them with real images (from Yelp or your own) by adding `<img>` tags or swapping the placeholder divs for image elements and pointing to your image files.

4. **About image**  
   The “About” section has a placeholder. You can add a real photo (team, truck, or project) by replacing the `.about-image-placeholder` block with an `<img>`.

## File structure

- `index.html` – all page content and structure  
- `styles.css` – layout, colors, typography, responsive rules  
- `script.js` – mobile menu toggle and basic behavior  

No build step or frameworks required; plain HTML, CSS, and JavaScript.

## Publish on GitHub & GitHub Pages

This project is set up so you can push it to GitHub and turn on GitHub Pages to get a live URL (e.g. `https://yourusername.github.io/open_space/`).

### 1. Create a new repository on GitHub

1. Go to [github.com](https://github.com) and sign in.
2. Click **New repository** (green button).
3. Set **Repository name** (e.g. `open-space` or `open-view-landscape`).
4. Choose **Public**.
5. Do **not** add a README, .gitignore, or license (this folder already has them).
6. Click **Create repository**.

### 2. Push this folder from your computer

In a terminal, from this project folder (`open_space`), run:

```bash
cd /Users/jeelkakadiya/Desktop/open_space

git init
git add index.html styles.css script.js README.md .gitignore
git commit -m "Initial commit: Open View Landscape website"

git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
git push -u origin main
```

Replace `YOUR_USERNAME` with your GitHub username and `YOUR_REPO_NAME` with the repo name you chose (e.g. `open-space`).

### 3. Turn on GitHub Pages

1. Open your repo on GitHub.
2. Go to **Settings** → **Pages** (left sidebar).
3. Under **Build and deployment**:
   - **Source**: Deploy from a branch
   - **Branch**: `main` (or `master`) → **/ (root)**
4. Click **Save**.

After a minute or two, your site will be live at:

- **https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/**

Example: if your repo is `open-space`, the URL is `https://yourusername.github.io/open-space/`.

---

## Other hosting

- **Netlify** or **Vercel**: connect your GitHub repo or drag this folder.
- **Any web host**: upload `index.html`, `styles.css`, and `script.js` to the same directory.

After updating the phone number, Yelp link, and (optionally) images, the site is ready to use.
