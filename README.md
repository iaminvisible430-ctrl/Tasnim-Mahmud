# Tasnim Mahmud | AI Founder & Developer — Portfolio v2.1

**🌐 Live Site:** https://tasnimport-ruddy.vercel.app  
**💻 GitHub:** https://github.com/iaminvisible430-ctrl/Tasnim-Mahmud  
**📧 Contact:** mahmudnil48@gmail.com

---

## 📁 Complete File Structure

```
/
├── index.html                    ← Main portfolio (10 sections, Flutter-smooth)
├── favicon.ico                   ← Browser tab icon (multi-size ICO)
├── favicon.png                   ← Standard favicon (32×32)
├── favicon-16x16.png             ← Small browser favicon
├── favicon-32x32.png             ← Medium browser favicon  
├── favicon-48x48.png             ← Taskbar favicon
├── favicon-192x192.png           ← Android home screen
├── favicon-512x512.png           ← High-res PWA icon
├── apple-touch-icon.png          ← iOS home screen icon (180×180)
├── icon-192.png                  ← PWA icon (manifest)
├── icon-512.png                  ← PWA icon large (manifest)
├── manifest.json                 ← PWA manifest (installable app)
├── site.webmanifest              ← Safari/iOS manifest
├── browserconfig.xml             ← Microsoft Edge/IE tile config
├── sw.js                         ← Service Worker (offline PWA)
├── robots.txt                    ← Search crawler rules
├── sitemap.xml                   ← All pages for search engines
├── vercel.json                   ← Deployment + security headers
├── googlee20e635f2e73a52d.html   ← Google Search Console verify
├── package.json                  ← Project metadata
├── .gitignore                    ← Git ignore rules
└── README.md                     ← This file
```

---

## 🏷️ Why Vercel Branding Appeared (and how it's fixed)

Vercel shows its own branding when:
1. **No `<title>` tag** — browser shows domain name ("vercel.app")
2. **No favicon** — Vercel's default triangle icon appears
3. **No Open Graph tags** — link previews show Vercel defaults
4. **No custom domain** — URL shows "vercel.app"

**Fixed in this version:**
- ✅ `<title>Tasnim Mahmud | AI Founder & Developer</title>`
- ✅ All favicon sizes provided (16, 32, 48, 192, 512)
- ✅ Full Open Graph + Twitter Card meta tags
- ✅ Complete `manifest.json` with personal branding
- ✅ `vercel.json` with custom headers

---

## 🔍 Search Engine Submission Guide

### 1. Google Search Console
- Go to: https://search.google.com/search-console
- Add property → URL prefix → `https://tasnimport-ruddy.vercel.app`
- Verify using the HTML file already in repo (`googlee20e635f2e73a52d.html`)
- Submit sitemap: `https://tasnimport-ruddy.vercel.app/sitemap.xml`

### 2. Bing Webmaster Tools
- Go to: https://www.bing.com/webmasters
- Import from Google Search Console OR add manually
- Submit sitemap URL
- Use IndexNow for instant indexing: https://www.bing.com/indexnow

### 3. Yandex Webmaster
- Go to: https://webmaster.yandex.com
- Add site → verify → submit sitemap

### 4. DuckDuckGo
- DuckDuckGo uses Bing's index — get indexed on Bing first
- Also uses: Yahoo, its own crawler
- No direct submission needed

### 5. IndexNow (Instant Indexing for Bing/Yandex)
- Create an API key file: `{your-key}.txt` in root
- Call: `https://api.indexnow.org/indexnow?url=YOUR_URL&key=YOUR_KEY`

---

## 🚀 Deploy Instructions

```bash
# Push to GitHub (Vercel auto-deploys)
git add .
git commit -m "v2.1: favicon + SEO improvements"
git push origin main

# OR manual deploy
vercel --prod
```

---

## 📞 Contact

- **Email:** mahmudnil48@gmail.com
- **WhatsApp:** +880 1782-242874  
- **GitHub:** github.com/iaminvisible430-ctrl

---
*Built with logic, vision & 🔥 | AIRCIMpco · Bangladesh 🇧🇩*
