# Wedding Invitation

A single-page wedding invitation with flip card (front, details, RSVP) and Formspree integration.

## Contents

- **index.html** – Full invitation (HTML, CSS, JS inline). Uses D3.js and Google Fonts from CDNs.
- **couple.jpg** – Main photo on the card front. **You must add this file** to the project root (same folder as `index.html`) and commit + push so it deploys (e.g. on Vercel). If missing, the card shows a “Your Photo Here” placeholder.

---

## Push to GitHub and host on Vercel

### 1. Add your photo (optional)

Place your couple photo in this folder as **couple.jpg**, then:

```bash
cd wedding-invitation
git add couple.jpg
git commit -m "Add couple photo"
```

### 2. Create a GitHub repo and push

1. On [GitHub](https://github.com/new), create a **new repository** (e.g. `wedding-invitation`). Do **not** initialize with a README (you already have one).
2. In this folder, add the remote and push:

```bash
cd wedding-invitation
git remote add origin https://github.com/thaib91/wedding-invitation.git
git branch -M main
git push -u origin main
```

 If you added **couple.jpg**, make sure it’s committed before pushing.

### 3. Deploy on Vercel

1. Go to [vercel.com](https://vercel.com) and sign in (e.g. with GitHub).
2. **Add New** → **Project**.
3. **Import** your `wedding-invitation` repo.
4. **Root Directory**: leave as `.` (repo root).
5. **Build and Output Settings**: no build command; Vercel will serve the files as static.
6. Click **Deploy**. Your site will be live at `https://your-project.vercel.app`.

Every push to `main` will trigger a new deployment.
