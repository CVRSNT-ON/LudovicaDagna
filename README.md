# Ludovica Benedetta Dagna — Art Curator

Personal website for Ludovica Benedetta Dagna, Art Curator, Art Manager, and Project Coordinator.

## Structure

```
/
├── index.html          ← Main (only) page
├── logo.png            ← LD Digital Atelier logo
├── PHOTO-2026-03-24-07-59-51.jpg  ← Portrait photo (add manually)
├── netlify.toml        ← Netlify build + headers config
├── _redirects          ← Netlify routing rules
├── robots.txt          ← SEO
└── README.md
```

## Deploy on Netlify

### Option A — Netlify Drop (fastest)
1. Go to [app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag the entire project folder onto the page
3. Done — you'll get a live URL immediately

### Option B — GitHub + Netlify (recommended for updates)
1. Create a new GitHub repository
2. Push all files:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/ludovica-dagna.git
   git push -u origin main
   ```
3. Go to [app.netlify.com](https://app.netlify.com) → **Add new site** → **Import an existing project**
4. Connect GitHub, select the repo
5. Build settings: leave blank (static site, no build command)
6. Click **Deploy site**

## Forms
The contact form uses Netlify Forms (`data-netlify="true"`).  
It works automatically when deployed to Netlify — no backend needed.  
Go to **Netlify → Forms** to see submitted messages.

## Customization checklist
- [ ] Replace `PHOTO-2026-03-24-07-59-51.jpg` with the actual portrait photo
- [ ] Update Instagram handle in `index.html` if different
- [ ] Update `robots.txt` with your final Netlify URL
- [ ] Optionally add a custom domain in Netlify → **Domain settings**
