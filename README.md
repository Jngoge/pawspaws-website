# Pawspaws.us — Website Files

A dog training and wellness website for pawspaws.us.

## Files included

| File | Purpose |
|------|---------|
| `index.html` | Homepage |
| `book.html` | Book promotion page (primary page) |
| `training.html` | Dog training guides |
| `wellness.html` | Dog wellness guides |
| `about.html` | About & contact page |
| `styles.css` | Shared global styles |
| `home.css` | Homepage-specific styles |
| `book.css` | Book page-specific styles |
| `inner.css` | Shared inner page styles |

## How to upload to GitHub (no desktop Git needed)

### Step 1 — Create a GitHub account and repository
1. Go to https://github.com and sign up / log in
2. Click the **+** icon (top right) → **New repository**
3. Name it `pawspaws-website`
4. Set visibility to **Public**
5. Click **Create repository**

### Step 2 — Upload your files
1. Inside your new repository, click **Add file** → **Upload files**
2. Drag and drop ALL the files from this folder into the upload area
3. Scroll down, write a commit message like `Initial website upload`
4. Click **Commit changes**

### Step 3 — Enable GitHub Pages (free hosting)
1. In your repository, go to **Settings** → **Pages** (left sidebar)
2. Under "Branch", select `main` and click **Save**
3. Your site will be live at: `https://YOUR-USERNAME.github.io/pawspaws-website`

### Step 4 — Connect your domain pawspaws.us
1. In GitHub Pages settings, enter `pawspaws.us` in the **Custom domain** field and save
2. Log into your domain registrar (where you bought pawspaws.us)
3. Go to DNS settings and add these records:

**A records** (point to GitHub's servers):
```
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```

**CNAME record:**
```
www  →  YOUR-USERNAME.github.io
```

4. Wait 10–30 minutes for DNS to propagate
5. Your site will be live at https://pawspaws.us

## Customising the book

Open `book.html` in any text editor to update:
- Book title and description
- Price (search for `$24.99` and `$9.99`)
- The "Order your copy" button link (search for `href="#"` in the buy-box section)
- Reader reviews / testimonials
- Author name

## Need help?
Email: hello@pawspaws.us
