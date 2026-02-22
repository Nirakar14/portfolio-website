# Nirakar Nepal — Portfolio v2
## Your Complete Update Guide

---

## 📁 What Files You Have

```
nirakar-portfolio-v2/
│
├── index.html              ← EVERYTHING is in this one file (CSS + JS + content)
└── assets/
    ├── images/             ← PUT ALL PHOTOS HERE
    │   ├── profile.jpg     ← Your profile photo (rename yours to exactly this)
    │   ├── cert-1.jpg      ← Certificate photos (cert-1.jpg, cert-2.jpg, ...)
    │   ├── photo-1.jpg     ← Gallery photos (photo-1.jpg, photo-2.jpg, ...)
    │   └── ...
    └── documents/
        └── cv.pdf          ← YOUR CV FILE (rename yours to exactly cv.pdf)
```

> **Why one file?** This way the site works correctly when you open it locally on your computer too — no styling issues.

---

## 🚀 How to Put This on GitHub (Replace Old WordPress Files)

1. Go to your GitHub repository
2. **Delete all the old WordPress files** (select all → delete)
3. **Upload everything** from the `nirakar-portfolio-v2` folder:
   - `index.html` (goes in root)
   - The entire `assets/` folder with all subfolders
4. Go to **Settings → Pages** → confirm Source is set to main branch / root
5. Wait 2-3 minutes → visit `www.nirakarnepal.com.np`

---

## ✅ Fill These In Before Going Live

Open `index.html` in any text editor (Notepad, VS Code, etc.) and search for `★ UPDATE` or `★ REPLACE`.

| What | Where to look | What to change |
|------|--------------|----------------|
| Profile photo | `assets/images/` | Add your photo, name it `profile.jpg` |
| CV | `assets/documents/` | Add your CV, name it `cv.pdf` |
| LinkedIn URL | Search `YOUR-LINKEDIN` | Replace with your full LinkedIn URL |
| ORCID URL | Search `YOUR-ORCID` | Replace with your ORCID number |
| Instagram URL | Search `YOUR-INSTAGRAM` | Replace with your username |
| Email | Search `your.email@example.com` | Replace with your real email |
| Paper 1 title + link | Paper 01 card | Fill in real title, link, journal, year |
| Paper 2 title + link | Paper 02 card | Fill in real title, link, journal, year |
| Paper 3 title + link | Paper 03 card | Fill in real title, link, journal, year |
| Experience dates | `2022 — 2023` etc. | Replace with your real dates |
| Best Paper Award | Awards section | Add real conference name and year |

---

## ➕ How to Add New Things (Simple Copy-Paste)

### New Research Paper
Find this in `index.html`:
```html
<!-- ★ ADD MORE: Copy a .paper-card block for each additional paper -->
```
Copy the entire block from `<a href=...class="paper-card"` to the closing `</a>` and paste it below. Change `Paper 04`, the link, title, description, journal, and year.

### New Gallery Photo
1. Put your photo in `assets/images/` (e.g. `photo-5.jpg`)
2. Find `<!-- ★ ADD MORE: Copy a .gal-item block for each photo -->`
3. Copy a `<div class="gal-item"...>` block and paste below
4. Change `photo-4.jpg` → `photo-5.jpg` and update the caption

### New Experience / Job
Find the Experience section and copy a `.tl-item` block. Update the date, title, place, and description.

### New Certificate
1. Put the certificate photo in `assets/images/` (e.g. `cert-3.jpg`)
2. Find the Certificates section and copy a `.cert-card` block
3. Update the image src, name, and issuer

### New Award
Find the Awards section and copy an `.award-item` block. Fill in the icon, name, meta, and description.

### New Skill
Find the Skills section and copy a `.skill-card` block. Change the emoji, name, and description.

---

## ⚠️ Common Problems & Fixes

**Photo doesn't appear?**
→ Check the filename is exactly right. `Profile.jpg` and `profile.jpg` are different!
→ Make sure it's in `assets/images/` not just `assets/`

**CV download doesn't work?**
→ Make sure the file is named exactly `cv.pdf` (lowercase)
→ Make sure it's in `assets/documents/`

**Site looks broken on GitHub?**
→ Make sure `index.html` is at the ROOT of the repo, not inside a subfolder

**Changes not showing?**
→ GitHub Pages takes 2-3 minutes to update. Try Ctrl+Shift+R (hard refresh)

---

## 💡 Tip: Preview Locally Before Uploading

Since everything is in one `index.html` file, you can just double-click it to open in your browser and see how it looks. Images will only show if the `assets/` folder is next to the `index.html`.
