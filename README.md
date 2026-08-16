# Vilamoura 70.3 — Training

Personal single-page training tracker for [Ironman 70.3 Vilamoura–Algarve](https://www.ironman.com/im703-vilamoura) (3 April 2027).

## GitHub Pages

1. Create a repo on GitHub (a URL-friendly name like `vilamoura-703` works best).
2. Push this folder:

   ```bash
   git add index.html README.md .gitignore
   git commit -m "Add Vilamoura 70.3 training tracker"
   git remote add origin git@github.com:fclancym/half-Ironman.git
   git push -u origin main
   ```

3. On GitHub: **Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: `main` / `/ (root)` → Save**.

Your site will be live at `https://fclancym.github.io/half-Ironman/` within a minute or two.

## Local preview

```bash
python3 -m http.server 8080
```

Open [http://localhost:8080](http://localhost:8080).
