# 📘 Shafac E-Waxbarasho — Website Files

## Files Included
- `index.html` — Homepage (Somali welcome, courses, about, certificate)
- `login.html` — Student login & registration page
- `admin.html` — Admin panel (login: shafac / shafac12)
- `course-beginner.html` — Beginner course with video, quiz & certificate
- (Duplicate `course-beginner.html` for other courses and rename)

---

## How to Add Your Photo
Open `index.html` and find this comment:
```html
<!-- Replace the placeholder below with: <img src="your-photo.jpg" alt="Shafac Hussein Omar"> -->
```
Replace it with:
```html
<img src="shafac-photo.jpg" alt="Shafac Hussein Omar">
```
Put your photo file (`shafac-photo.jpg`) in the same folder.

---

## How to Add a Video Lesson
In `course-beginner.html`, find the video placeholder and replace with:
```html
<iframe src="https://www.youtube.com/embed/YOUR_VIDEO_ID" 
        allowfullscreen style="width:100%;height:100%;border:none"></iframe>
```
Get YOUR_VIDEO_ID from the YouTube video URL:
`https://www.youtube.com/watch?v=dQw4w9WgXcQ` → ID is `dQw4w9WgXcQ`

---

## How to Go Live FREE (Step by Step)

### Step 1 — Create a GitHub account
Go to https://github.com and sign up for free.

### Step 2 — Upload your files
1. Click "New repository"
2. Name it: `shafac-ewaxbarasho`
3. Click "Upload files" and drag all your HTML files

### Step 3 — Deploy on Vercel (free)
1. Go to https://vercel.com and sign up with your GitHub account
2. Click "New Project"
3. Select your `shafac-ewaxbarasho` repository
4. Click "Deploy" — your site goes live in 1 minute!
5. You get a FREE URL like: `shafac-ewaxbarasho.vercel.app`

### Step 4 — Custom domain (optional, ~$10/year)
Buy a domain like `shafacelearning.com` at https://namecheap.com
Then in Vercel → Settings → Domains → add your domain.

---

## Admin Panel
URL: `yoursite.com/admin.html`
Username: `shafac`
Password: `shafac12`

⚠️ Change the password in `admin.html` before going live!
Find: `if(u==='shafac'&&p==='shafac12')`
Change `shafac12` to your new password.

---

## Contact
Shafac Hussein Omar — +252 71 829777
