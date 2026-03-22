# Personal Academic Website — Hadiza Umar Yusuf

This is the source code for my personal academic website, live at **[hadiza-yusuf.netlify.app](https://hadiza-yusuf.netlify.app)**.

## About

I am a PhD candidate in Computer & Information Sciences at the **University of Michigan-Dearborn**, working in the AISE-CPS Lab under Professor Khouloud Gaaloul. My research focuses on the safety and verification of AI-enabled Cyber-Physical Systems, supported by the National Science Foundation (NSF).

This site serves as a central hub for my research, publications, teaching experience, and academic journey.

## What's on the Site

- **About** — Bio and research overview
- **Research** — Current and past research projects
- **Publications** — Peer-reviewed papers in top venues
- **Teaching** — Teaching roles and experience
- **Talks & Presentations** — Conference talks and invited speaking engagements
- **News** — Recent academic highlights and milestones
- **Blog** — Reflections on research, teaching, and academia
- **Contact** — Ways to reach me

## Built With

- Plain HTML & CSS — no frameworks, no build tools
- [Lora](https://fonts.google.com/specimen/Lora) & [DM Sans](https://fonts.google.com/specimen/DM+Sans) (Google Fonts)
- Hosted on [Netlify](https://netlify.com) with continuous deployment from this repository

## Structure

```
hadiza-website/
├── index.html               ← Entire website (single file)
├── assets/
│   ├── photo.jpg            ← Profile photo
│   └── Hadiza_Yusuf_CV.pdf  ← Downloadable CV
└── README.md
```

## Contact

- 📧 hyusuf@umich.edu
- 🔗 [linkedin.com/in/hyusuf7](https://www.linkedin.com/in/hyusuf7)
- 🎓 [Google Scholar](https://scholar.google.com/citations?user=zffZglgAAAAJ)
- 💻 [GitHub @Hadex-Pearl1](https://github.com/Hadex-Pearl1)

---

*Feel free to use this as inspiration for your own academic website. If you do, a mention or star would be appreciated!*

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
