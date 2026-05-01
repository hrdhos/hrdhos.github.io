# Md. Hridoy Hossain — Portfolio Website

A refined legal portfolio website built with vanilla HTML, CSS, and JavaScript.

## 📁 Folder Structure

```
hridoy-portfolio/
├── index.html          ← Main page (GitHub Pages looks for this)
├── css/
│   └── style.css
├── js/
│   └── main.js
├── assets/
│   └── profile.jpg     ← ADD YOUR PHOTO HERE
└── README.md
```

---

## 🖼️ Adding Your Profile Photo

1. Name your photo file exactly: `profile.jpg`
2. Place it inside the `assets/` folder
3. The site will automatically display it

> Supported formats: `.jpg` or `.jpeg` recommended. Keep under 500KB for fast loading.

---

## 🚀 Hosting on GitHub Pages (Free)

### Step 1 — Create the repository
1. Go to [github.com](https://github.com) and sign in
2. Click **New repository**
3. Name it exactly: `YOUR-USERNAME.github.io`
   - e.g. if your GitHub username is `hridoyhossain`, name it `hridoyhossain.github.io`
4. Set it to **Public**
5. Click **Create repository**

### Step 2 — Upload your files
**Option A — Via the GitHub website (easiest):**
1. Open your new repository
2. Click **uploading an existing file**
3. Drag and drop ALL files and folders (`index.html`, `css/`, `js/`, `assets/`)
4. Click **Commit changes**

**Option B — Via Git (for developers):**
```bash
git init
git add .
git commit -m "Initial portfolio launch"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-USERNAME.github.io.git
git push -u origin main
```

### Step 3 — Enable GitHub Pages
1. In your repository, go to **Settings** → **Pages**
2. Under **Source**, select **Deploy from a branch**
3. Choose branch: `main`, folder: `/ (root)`
4. Click **Save**

### Step 4 — Visit your site
After 1–2 minutes, your portfolio will be live at:
```
https://YOUR-USERNAME.github.io
```

---

## ✏️ Customising the Site

| What to change | Where to find it |
|---|---|
| Your name, bio, experience | `index.html` |
| Colours, fonts, spacing | `css/style.css` |
| Animations, interactions | `js/main.js` |
| Profile photo | `assets/profile.jpg` |

### Colour variables (top of `style.css`):
```css
--gold:      #b8962e;   /* Accent gold */
--charcoal:  #1a1814;   /* Dark background */
--parchment: #f5f0e8;   /* Light background */
--cream:     #faf7f2;   /* Page background */
```

---

## 📞 Contact
hridoyhassan929@gmail.com
