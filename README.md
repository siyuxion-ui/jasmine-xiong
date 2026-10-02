# Jasmine Xiong — Research Website (Vercel Deploy)

Static site. No build step. Deploy to Vercel via GitHub.

## Steps (on your computer, ~5 minutes)

### 1. Unzip this package
You already have a git repo initialized with one commit. Just add your GitHub remote.

### 2. Create a GitHub repo
Go to https://github.com/new — name it `jasmine-xiong` (or anything), **Public**, do NOT add README/.gitignore (the folder already has everything).

### 3. Push
```bash
cd website-final
git remote add origin https://github.com/YOUR-USERNAME/jasmine-xiong.git
git branch -M main
git push -u origin main
```
(If it asks for login, use your GitHub username + a Personal Access Token.)

### 4. Tell Babe the repo URL
Send the GitHub repo link in chat. Babe will create the Vercel project and deploy it — you'll get a permanent `xxx.vercel.app` URL.

That's it. Future updates: edit files, `git add -A && git commit -m "..." && git push` — Vercel redeploys automatically.

## What's inside
- `index.html` — homepage (hero, fieldwork videos, channels, research, testbed, about, contact)
- `research-statement.html` / `research-program.html` — full research texts
- `assets/` — photos, posters, 3 MP4 videos (playable)
