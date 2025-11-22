# Hanzo Technologies Multi-Language Website

## 🌍 12 Languages Supported

This repository contains the complete Hanzo Technologies website in 12 languages:

- 🇺🇸 **English (EN)** - Default
- 🇪🇸 **Spanish (ES)** - Español
- 🇫🇷 **French (FR)** - Français
- 🇸🇦 **Arabic (AR)** - العربية (RTL)
- 🇯🇵 **Japanese (JA)** - 日本語
- 🇨🇳 **Chinese (ZH)** - 中文 (Simplified)
- 🇰🇷 **Korean (KO)** - 한국어
- 🇻🇳 **Vietnamese (VI)** - Tiếng Việt
- 🇩🇪 **German (DE)** - Deutsch
- 🇮🇳 **Hindi (HI)** - हिन्दी
- 🏔️ **Tibetan (BO)** - བོད་ཡིག
- 🏝️ **Hawaiian (HAW)** - ʻŌlelo Hawaiʻi

## 📁 Folder Structure

```
hanzo-website/
├── index.html          # English (default)
├── es/
│   └── index.html     # Spanish
├── fr/
│   └── index.html     # French
├── ar/
│   └── index.html     # Arabic (RTL)
├── ja/
│   └── index.html     # Japanese
├── zh/
│   └── index.html     # Chinese
├── ko/
│   └── index.html     # Korean
├── vi/
│   └── index.html     # Vietnamese
├── de/
│   └── index.html     # German
├── hi/
│   └── index.html     # Hindi
├── bo/
│   └── index.html     # Tibetan
└── haw/
    └── index.html     # Hawaiian
```

## 🚀 GitHub Pages Deployment

### Step 1: Create GitHub Repository

1. Go to GitHub and create a new repository
2. Name it: `hanzo-technologies-website` (or any name you prefer)
3. Make it **Public**
4. Don't initialize with README (we have our own)

### Step 2: Upload Files

**Option A: GitHub Web Interface**
1. Click "uploading an existing file"
2. Drag all folders and files from this directory
3. Commit the changes

**Option B: Git Command Line**
```bash
git init
git add .
git commit -m "Initial commit - Multi-language Hanzo Technologies website"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/hanzo-technologies-website.git
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository Settings
2. Navigate to "Pages" in the left sidebar
3. Under "Source", select "Deploy from a branch"
4. Select branch: **main**
5. Select folder: **/ (root)**
6. Click "Save"

### Step 4: Wait for Deployment

- GitHub Pages will build your site (takes 1-2 minutes)
- Your site will be live at: `https://YOUR_USERNAME.github.io/hanzo-technologies-website/`

## 🔗 URL Structure

After deployment, your language versions will be accessible at:

- English: `https://YOUR_USERNAME.github.io/hanzo-technologies-website/`
- Spanish: `https://YOUR_USERNAME.github.io/hanzo-technologies-website/es/`
- French: `https://YOUR_USERNAME.github.io/hanzo-technologies-website/fr/`
- Arabic: `https://YOUR_USERNAME.github.io/hanzo-technologies-website/ar/`
- Japanese: `https://YOUR_USERNAME.github.io/hanzo-technologies-website/ja/`
- Chinese: `https://YOUR_USERNAME.github.io/hanzo-technologies-website/zh/`
- Korean: `https://YOUR_USERNAME.github.io/hanzo-technologies-website/ko/`
- Vietnamese: `https://YOUR_USERNAME.github.io/hanzo-technologies-website/vi/`
- German: `https://YOUR_USERNAME.github.io/hanzo-technologies-website/de/`
- Hindi: `https://YOUR_USERNAME.github.io/hanzo-technologies-website/hi/`
- Tibetan: `https://YOUR_USERNAME.github.io/hanzo-technologies-website/bo/`
- Hawaiian: `https://YOUR_USERNAME.github.io/hanzo-technologies-website/haw/`

## 🌐 Language Selector

Every page includes a language selector in the navigation bar that allows users to switch between all 12 languages seamlessly.

## ✨ Features

- **Dark Mode Design** - Sleek black background with red accents
- **Liquid Glass Effects** - Apple-inspired frosted glass cards
- **Responsive Design** - Works perfectly on mobile, tablet, and desktop
- **RTL Support** - Proper right-to-left layout for Arabic
- **Proper Character Encoding** - All scripts display correctly (Kanji, Devanagari, Tibetan, etc.)
- **SEO Optimized** - Proper meta tags and language declarations
- **Fast Loading** - Single-page architecture with smooth scrolling

## 📝 Contact Information

All language versions include contact details:
- **Founder:** quielo@hanzotechnologies.com
- **Business:** outreach@hanzotechnologies.com
- **Press:** press@hanzotechnologies.com
- **Support:** support@hanzotechnologies.com

## 🛠️ Updating Content

To update content across all languages:

1. Edit the appropriate `index.html` file in each language folder
2. Commit and push changes to GitHub
3. GitHub Pages will automatically rebuild (takes 1-2 minutes)

## 🎨 Branding

- **Primary Color:** #C41E3A (Red - matching Hanzo logo)
- **Font:** SF Pro Display / Inter
- **Style:** Apple-inspired minimalist design

## 📱 Social Media

- Twitter/X: @HanzoTech
- Instagram: @HanzoTech

## 🔒 Custom Domain (Optional)

To use a custom domain (e.g., hanzotechnologies.com):

1. Buy domain from registrar (Namecheap, GoDaddy, etc.)
2. Add CNAME record pointing to: `YOUR_USERNAME.github.io`
3. In GitHub repo settings → Pages → Custom domain
4. Enter your domain and save
5. Enable "Enforce HTTPS"

## 📊 Analytics (Optional)

To add Google Analytics:

1. Get your Google Analytics tracking ID
2. Add tracking code to the `<head>` section of each `index.html`

## 🐛 Troubleshooting

**Site not loading?**
- Wait 2-3 minutes after enabling GitHub Pages
- Check that branch is set to "main" and folder to "/ (root)"
- Verify all files were uploaded correctly

**Language pages not working?**
- Ensure folder names are lowercase (es, fr, ja, etc.)
- Check that each folder contains an `index.html` file

**Characters displaying incorrectly?**
- Ensure UTF-8 encoding is preserved when editing files
- Use a text editor that supports Unicode (VS Code, Sublime Text, etc.)

## 📄 License

© 2025 Hanzo Technologies. All rights reserved.

## 🙋 Support

For questions or issues, contact: support@hanzotechnologies.com

---

**Built with ❤️ for Hanzo Technologies**
**USA-Japan Innovation | Advancing Robotics & AI**
