# 🧮 Calculia — Opeoluwa Jamiu Portfolio

**Live site:** [https://calculiang.github.io](https://calculiang.github.io)

Personal portfolio and booking site for **Opeoluwa Jamiu Olasunkanmi** — Mathematics Educator, Ed-Tech Innovator, and Founder of Calculia.

---

## 🚀 Hosting on GitHub Pages (Step-by-Step)

### Step 1 — Create Your GitHub Account
1. Go to [github.com](https://github.com) and sign up (or log in)
2. Use the username **`calculiang`** → your site will live at `https://calculiang.github.io`

### Step 2 — Create the Repository
1. Click the **"+"** icon (top right) → **"New repository"**
2. Set **Repository name** to exactly: `calculiang.github.io`
3. Set visibility to **Public**
4. Do **NOT** tick "Add a README file" (you already have one)
5. Click **"Create repository"**

### Step 3 — Upload Your Files
1. On the new repo page, click **"uploading an existing file"**
2. Drag and drop **both files**:
   - `index.html`
   - `README.md`
3. Scroll down, add commit message: `Initial portfolio launch`
4. Click **"Commit changes"**

### Step 4 — Enable GitHub Pages
1. Go to your repo → **Settings** tab
2. In the left sidebar click **"Pages"**
3. Under **"Source"** select **"Deploy from a branch"**
4. Under **"Branch"** select **`main`** and folder **`/ (root)`**
5. Click **Save**

### Step 5 — Your Site Is Live! 🎉
- Wait **1–2 minutes**, then visit: **https://calculiang.github.io**
- Share this link anywhere — WhatsApp, LinkedIn, email, business cards

---

## ✏️ How to Edit the Website

All editable sections are clearly marked in `index.html` with comment banners like:

```html
<!-- ═══════════════════════════════════════
     SECTION: HERO
     Edit: headline, subtitle, description, CTA buttons
═══════════════════════════════════════ -->
```

### To make edits:
1. Go to your GitHub repo at `github.com/calculiang/calculiang.github.io`
2. Click on `index.html`
3. Click the **pencil icon** (Edit) top right
4. Find the section you want to change using `Ctrl+F` (search)
5. Make your changes
6. Click **"Commit changes"** at the bottom
7. Site updates automatically within **~30 seconds**

### Quick Edit Reference

| What to change | Search for in index.html |
|---|---|
| Your name / headline | `SECTION: HERO` |
| Stats (7+, 500+, etc.) | `SECTION: STATS BAND` |
| About me text | `SECTION: ABOUT` |
| Achievement cards | `SECTION: ACHIEVEMENTS` |
| Certifications | `SECTION: CERTIFICATIONS` |
| Projects | `SECTION: PROJECTS` |
| YouTube playlists | `SECTION: YOUTUBE` |
| Add new YouTube link | Duplicate a playlist card block |
| Booking form | `SECTION: BOOKING FORM` |
| Footer links / contacts | `SECTION: FOOTER` |
| Profile photo | Search for `object-position:top` |

---

## 📬 Booking Form Setup (One-Time)

The booking form uses **Formspree** to send submissions to `calculiang@gmail.com`.

**First-time activation:**
1. Someone submits the form (you can test it yourself)
2. Formspree sends a verification email to **calculiang@gmail.com**
3. Click the confirmation link in that email
4. ✅ All future bookings land directly in your Gmail

---

## 📋 Adding a New YouTube Playlist

In `index.html`, find `SECTION: YOUTUBE` and duplicate this block:

```html
<div class="reveal" style="background:var(--navy-mid);border:1px solid rgba(201,168,76,.35);...">
  <!-- Change the year, playlist URL, title and description -->
</div>
```

Update:
- The year display (`2021` / `2022` / `2023`)
- The `onclick` URL to your new playlist link
- The `href` on the "Watch Full Playlist" button
- The title and description text

---

## 🔗 Important Links

| Platform | Link |
|---|---|
| 📧 Email | calculiang@gmail.com |
| ▶ YouTube | https://www.youtube.com/channel/UCdj-SJ9aTm0fqCdhB6cHcyw |
| 💼 LinkedIn | https://www.linkedin.com/in/opeoluwajamiu |
| 💬 WhatsApp | https://wa.me/+2348061128624 |
| 🌐 Portfolio | https://calculiang.github.io |

---

## 🛠 Tech Stack

- Pure **HTML5 / CSS3 / Vanilla JavaScript** — no frameworks, no build tools
- Fonts: **Playfair Display** + **DM Sans** + **DM Mono** (Google Fonts)
- Form backend: **Formspree** (free tier)
- Hosting: **GitHub Pages** (free, forever)

---

*Built with ❤️ for mathematics education in Nigeria and beyond.*
