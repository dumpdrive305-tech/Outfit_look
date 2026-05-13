# 📸 My Photo Journal

A warm, editorial-style personal photo blog hosted on GitHub Pages.

---

## 🚀 Setup Instructions

### 1. Create a GitHub Repository
- Go to github.com → New repository
- Name it anything (e.g. `my-photo-journal`)
- Set it to **Public**
- Click **Create repository**

### 2. Upload These Files
Upload all files to your repo root:
```
index.html      ← public gallery
admin.html      ← admin panel
posts.json      ← post data (auto-managed)
images/         ← images go here (auto-managed)
README.md
```

### 3. Enable GitHub Pages
- Go to your repo → **Settings** → **Pages**
- Under **Source**, select `Deploy from branch`
- Choose `main` branch, `/ (root)` folder
- Click **Save**
- Your site will be live at: `https://YOUR-USERNAME.github.io/REPO-NAME/`

### 4. Create a GitHub Token
- Go to GitHub → **Settings** → **Developer settings** → **Personal access tokens** → **Tokens (classic)**
- Click **Generate new token (classic)**
- Give it a name, set expiry (or no expiry)
- Check the **`repo`** scope checkbox
- Click **Generate token**
- **Copy it immediately** — you won't see it again!

### 5. Configure the Admin Panel
- Visit `https://YOUR-USERNAME.github.io/REPO-NAME/admin.html`
- Default login: **username:** `admin` | **password:** `changeme123`
- Click **⚙ Settings** in the top bar
- Fill in:
  - GitHub Username
  - Repository Name
  - Personal Access Token
  - Branch (usually `main`)
- **Change your password** in the same settings panel!
- Click **Save Settings**

### 6. Create Your First Post!
- Pick a title, tag, body text
- Upload images from your computer
- Add links if you want
- Click **Publish Post**

The admin will automatically:
1. Upload images to the `images/` folder in your repo
2. Update `posts.json` with your new post
3. Your public gallery refreshes automatically!

---

## 🔐 Default Login
| Field    | Value          |
|----------|----------------|
| Username | `admin`        |
| Password | `changeme123`  |

**Change this immediately in Settings after first login!**

---

## 📁 File Structure
```
/
├── index.html      ← Public gallery (warm editorial style)
├── admin.html      ← Admin panel (password protected)
├── posts.json      ← All post data (auto-managed)
├── images/         ← Uploaded photos (auto-managed)
└── README.md
```

---

## ✨ Features
- 📷 Beautiful image grid layouts (1–5+ photos per post)
- 🖼 Fullscreen lightbox with keyboard navigation
- 🔗 Links with labels per post
- 🏷 Tags/categories per post
- ⚙ Admin settings panel (change GitHub config + password)
- 📱 Mobile responsive
- 🚀 Fully static — no server needed
