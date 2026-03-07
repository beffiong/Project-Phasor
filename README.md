# Phasor — Investor Site (projectphasor.com)

Deploy to GitHub Pages, then connect projectphasor.com as custom domain.

## Deploy
```bash
git init && git add . && git commit -m "Initial"
git branch -M main
git remote add origin https://github.com/YOUR_USER/YOUR_REPO.git
git push -u origin main
```
Settings → Pages → GitHub Actions → Static HTML → Commit

## Custom Domain
Add to Squarespace DNS:
- 4 A records (@): 185.199.108-111.153
- CNAME (www): YOUR_USER.github.io

Then Settings → Pages → Custom Domain → projectphasor.com
