# Makarand Pundlik – Portfolio

Single-page portfolio. Deploys to GitHub Pages.

## Deploy (GitHub Pages)

1. **Create a new repo** on GitHub: [github.com/new](https://github.com/new)  
   - Name it e.g. `portfolio` or `makarand.io`  
   - Public, no README  
   - Create repository  

2. **Commit and push** (run in this folder, in a terminal where git works):

   ```bash
   git add .
   git commit -m "Initial portfolio"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
   git push -u origin main
   ```

   If `git commit` fails due to a “trailer” option, run the commit from a normal terminal (outside Cursor) or use:  
   `git commit -m "Initial portfolio" --no-verify`

3. **Turn on GitHub Pages**  
   - Repo → **Settings** → **Pages**  
   - **Source**: “GitHub Actions” (use the workflow below) or “Deploy from a branch”  
   - If “Deploy from a branch”: Branch = **main**, Folder = **/ (root)** → Save  

4. **Open the site**  
   - After a minute or two: `https://YOUR_USERNAME.github.io/YOUR_REPO/`
