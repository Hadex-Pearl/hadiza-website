# Hadiza Yusuf — Personal Academic Website

A clean, minimal personal website built for GitHub + Netlify deployment.

## 📁 Folder Structure

```
hadiza-website/
├── index.html          ← Your entire website (single file)
├── assets/
│   └── Hadiza_Yusuf_CV.pdf   ← Place your CV PDF here
└── README.md
```

## 🚀 How to Deploy (Step-by-Step)

### Step 1 — Set up your folder
1. Create a folder on your computer called `hadiza-website`
2. Place `index.html` inside it
3. Create a subfolder called `assets` and put your CV PDF inside it (name it `Hadiza_Yusuf_CV.pdf`)

### Step 2 — Push to GitHub
Open your terminal and run:

```bash
cd hadiza-website
git init
git add .
git commit -m "Initial website launch"
```

Then go to github.com → New Repository → name it `hadiza-website` → Create.
Copy the commands GitHub shows you (they'll look like):

```bash
git remote add origin https://github.com/YOUR-USERNAME/hadiza-website.git
git branch -M main
git push -u origin main
```

### Step 3 — Connect to Netlify
1. Go to netlify.com and sign up (free)
2. Click "Add new site" → "Import an existing project"
3. Choose GitHub → authorize → select `hadiza-website`
4. Build settings:
   - Build command: *(leave empty)*
   - Publish directory: `/` (or leave as default)
5. Click **Deploy site**

Your site will be live at something like `hadiza-yusuf.netlify.app` in ~30 seconds!

### Step 4 — Custom Domain (optional)
- Buy a domain (e.g. `hadizayusuf.com`) from Namecheap or Porkbun (~$10/yr)
- In Netlify: Site Settings → Domain Management → Add custom domain
- Follow Netlify's DNS instructions

## ✏️ How to Update Your Site

Edit `index.html` in any text editor, then:

```bash
git add .
git commit -m "Updated publications"
git push
```

Netlify auto-detects the push and re-deploys within seconds.

## 📝 Things to Customize

- [ ] Replace `assets/Hadiza_Yusuf_CV.pdf` with your actual CV
- [ ] Add real links to your publications (search DOI/Google Scholar)
- [ ] Add your photo (replace the "HY" avatar initials with an `<img>` tag)
- [ ] Update blog posts when you're ready to write
- [ ] Update Google Scholar profile URL with your actual citation ID
- [ ] Add your personal email `hadizayusuf7@gmail.com` or keep institutional one

## 🌐 Sections Included
1. About / Hero
2. Research (6 projects)
3. Publications (6 papers)
4. Teaching (6 roles)
5. Talks & Presentations
6. News
7. Blog (3 placeholder posts)
8. CV (inline + PDF download)
9. Contact
