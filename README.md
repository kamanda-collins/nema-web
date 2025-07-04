# NEMA Compliance Checker - Web Interface

This is the web interface that embeds the NEMA Compliance Checker Streamlit application at `nema.kamandalabs.me`.

## 🚀 Quick Deploy to Vercel

### 1. Push to GitHub

```bash
# Initialize git repository
git init
git add .
git commit -m "Initial commit: NEMA web interface"
git branch -M main

# Add your GitHub repository (create it first on github.com)
git remote add origin https://github.com/YOUR-USERNAME/nema-web.git
git push -u origin main
```

### 2. Deploy to Vercel

1. Go to [vercel.com](https://vercel.com)
2. Click "New Project"
3. Import your GitHub repository
4. Use these settings:
   - **Framework Preset:** Other
   - **Root Directory:** ./
   - **Build Command:** (leave empty)
   - **Output Directory:** public
5. Click "Deploy"

### 3. Add Custom Domain

1. In Vercel dashboard, go to your project
2. Click "Settings" → "Domains"
3. Add domain: `nema.kamandalabs.me`
4. Copy the DNS records shown

### 4. Configure DNS in Namecheap

Add this CNAME record in your Namecheap DNS settings:

```
Type: CNAME Record
Host: nema
Value: cname.vercel-dns.com
TTL: Automatic
```

## 📁 Project Structure

```
nema-web/
├── public/
│   ├── index.html          # Main landing page
│   └── favicon.svg         # Site favicon
├── vercel.json            # Vercel configuration
├── package.json           # Project metadata
├── .gitignore            # Git ignore rules
└── README.md             # This file
```

## 🎯 What This Does

- Creates a professional landing page at `nema.kamandalabs.me`
- Embeds your Streamlit app (`nema-kamandalabs.streamlit.app`)
- Provides SEO optimization and mobile responsiveness
- Handles loading states and error fallbacks

## 🔧 Local Development

```bash
# Serve locally for testing
python -m http.server 3000 --directory public
# Then open: http://localhost:3000
```

## ✅ Final Result

Your visitors will see:
- `https://nema.kamandalabs.me` → Professional landing page with embedded app
- Direct app access via buttons that link to your Streamlit app

---

Built for environmental conservation 🌿
# nema-web
