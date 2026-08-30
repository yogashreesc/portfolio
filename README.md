# My First Website

A simple "About Me" personal website built with plain HTML & CSS.

## Files
- `index.html` — page structure/content
- `style.css` — styling

## 1. Open in VS Code
1. Unzip this folder.
2. Open VS Code → File → Open Folder → select `my-first-website`.

## 2. Preview with Live Server
1. Install the **Live Server** extension (by Ritwick Dey) from the VS Code Extensions tab.
2. Right-click `index.html` → **Open with Live Server**.
3. Your site opens at something like `http://127.0.0.1:5500/index.html`.

## 3. Push to GitHub
In the VS Code terminal (inside the project folder):

```bash
git init
git add .
git commit -m "My first website"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```

(Create the empty repo on GitHub first, then copy its URL into the command above.)

## 4. Deploy free with GitHub Pages
1. On GitHub, go to your repo → **Settings** → **Pages**.
2. Under "Build and deployment", set **Source** to `Deploy from a branch`.
3. Choose branch `main`, folder `/ (root)`, then **Save**.
4. After a minute, your live site will be at:
   `https://<your-username>.github.io/<repo-name>/`

## Customize
- Replace the email/LinkedIn/GitHub links in the Contact section with your real ones.
- Edit the text in `index.html` to match your own bio, skills, and projects.
- Tweak colors in `style.css` (search for `#ff6b6b` and `#1a1a2e`).
