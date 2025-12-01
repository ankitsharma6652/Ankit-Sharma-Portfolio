# 📸 Social Media Preview Images Guide

## Creating Professional Preview Images for Your Portfolio

When you share your portfolio on LinkedIn, Twitter, or other platforms, a preview image (Open Graph image) makes it look more professional and increases click-through rates.

---

## 🎨 Option 1: Use Canva (Easiest - Recommended)

### Step 1: Create Account
1. Go to [canva.com](https://canva.com)
2. Sign up for free account

### Step 2: Choose Template
1. Search for "LinkedIn Post" or "Social Media"
2. Dimensions: **1200 x 630 pixels** (standard OG image size)
3. Or create custom size: 1200 x 630

### Step 3: Design Your Preview

**Suggested Layout:**

```
┌─────────────────────────────────────┐
│                                     │
│         ANKIT SHARMA                │
│                                     │
│   Marketing Data Analyst            │
│   Aspiring Data Engineer | Gen AI   │
│                                     │
│   ✓ 30+ Dashboards                  │
│   ✓ $9.4M Spend Tracked             │
│   ✓ Snowflake Expert                │
│   ✓ Python | SQL | Tableau          │
│                                     │
│   📊 View Portfolio →               │
│                                     │
└─────────────────────────────────────┘
```

**Design Tips:**
- **Background:** Clean gradient (indigo to violet)
- **Text:** White or light color for contrast
- **Font:** Poppins or similar professional font
- **Icons:** Add relevant emojis or icons
- **Branding:** Keep it clean and professional

### Step 4: Download
1. Click "Download"
2. Format: **PNG** (best quality)
3. Save as: `portfolio-preview.png`

---

## 🎨 Option 2: Use Figma (Professional)

### Step 1: Setup
1. Go to [figma.com](https://figma.com)
2. Create free account
3. Create new file

### Step 2: Create Frame
1. Press `F` for frame tool
2. Create frame: **1200 x 630 px**
3. Name it: "Portfolio Preview"

### Step 3: Design Elements

**Background:**
```
- Gradient: #6366f1 to #8b5cf6
- Or solid color: #6366f1
```

**Text Layers:**
```
1. Name: 72px, Bold, White
2. Title: 36px, Semi-bold, White/90%
3. Stats: 24px, Regular, White/80%
4. CTA: 28px, Bold, White
```

### Step 4: Export
1. Select frame
2. Right panel → Export
3. Format: PNG
4. Scale: 2x (for retina)
5. Export

---

## 🎨 Option 3: Quick Template (Copy-Paste)

### HTML Template for Preview Image

Create a simple HTML file and screenshot it:

```html
<!DOCTYPE html>
<html>
<head>
    <style>
        body {
            margin: 0;
            width: 1200px;
            height: 630px;
            background: linear-gradient(135deg, #6366f1 0%, #8b5cf6 100%);
            display: flex;
            align-items: center;
            justify-content: center;
            font-family: 'Arial', sans-serif;
            color: white;
        }
        .container {
            text-align: center;
            padding: 60px;
        }
        h1 {
            font-size: 72px;
            margin: 0 0 20px 0;
            font-weight: 800;
        }
        h2 {
            font-size: 36px;
            margin: 0 0 40px 0;
            opacity: 0.9;
            font-weight: 600;
        }
        .stats {
            font-size: 24px;
            line-height: 1.8;
            opacity: 0.85;
        }
        .cta {
            margin-top: 40px;
            font-size: 28px;
            font-weight: 700;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>ANKIT SHARMA</h1>
        <h2>Marketing Data Analyst | Aspiring Data Engineer</h2>
        <div class="stats">
            ✓ 30+ Dashboards | $9.4M Spend Tracked<br>
            ✓ Snowflake Expert | Python | SQL | Tableau<br>
            ✓ Data Engineering & Gen AI
        </div>
        <div class="cta">📊 View Portfolio →</div>
    </div>
</body>
</html>
```

**To Create Image:**
1. Save as `preview-template.html`
2. Open in browser
3. Take screenshot (1200x630)
4. Or use browser dev tools to set viewport size

---

## 📝 Adding Preview Image to Your Portfolio

### Step 1: Add Image to Repository
1. Save your preview image as `og-image.png`
2. Upload to your portfolio folder (same level as index.html)

### Step 2: Update HTML Meta Tags

Add these to `<head>` section of `index.html`:

```html
<!-- Open Graph / Social Media Preview -->
<meta property="og:type" content="website">
<meta property="og:url" content="https://your-username.github.io/portfolio/">
<meta property="og:title" content="Ankit Sharma - Data Analyst Portfolio">
<meta property="og:description" content="Marketing Data Analyst | Aspiring Data Engineer | Snowflake Expert. 30+ Dashboards, $9.4M Spend Tracked.">
<meta property="og:image" content="https://your-username.github.io/portfolio/og-image.png">

<!-- Twitter Card -->
<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:url" content="https://your-username.github.io/portfolio/">
<meta name="twitter:title" content="Ankit Sharma - Data Analyst Portfolio">
<meta name="twitter:description" content="Marketing Data Analyst | Aspiring Data Engineer | Snowflake Expert">
<meta name="twitter:image" content="https://your-username.github.io/portfolio/og-image.png">
```

### Step 3: Test Your Preview

**LinkedIn:**
1. Go to [LinkedIn Post Inspector](https://www.linkedin.com/post-inspector/)
2. Enter your portfolio URL
3. See preview

**Twitter:**
1. Go to [Twitter Card Validator](https://cards-dev.twitter.com/validator)
2. Enter your portfolio URL
3. See preview

**Facebook:**
1. Go to [Facebook Sharing Debugger](https://developers.facebook.com/tools/debug/)
2. Enter your portfolio URL
3. See preview and clear cache

---

## 🎯 Best Practices

### Image Specifications
- **Size:** 1200 x 630 pixels (standard)
- **Format:** PNG or JPG
- **File Size:** Under 1MB
- **Aspect Ratio:** 1.91:1

### Design Guidelines
✅ **Do:**
- Use high contrast (light text on dark background)
- Keep text large and readable
- Include your name prominently
- Add 2-3 key stats or skills
- Use professional colors
- Keep it simple and clean

❌ **Don't:**
- Use too much text
- Use small fonts
- Include personal photos (unless professional headshot)
- Use busy backgrounds
- Overcrowd with information

---

## 📊 Example Preview Texts

### Option 1: Stats-Focused
```
ANKIT SHARMA
Data Analyst | Aspiring Data Engineer

✓ 30+ Dashboards Managed
✓ $9.4M Spend Tracked
✓ 622M Impressions Analyzed
✓ Snowflake | Python | Tableau

View Portfolio →
```

### Option 2: Skills-Focused
```
ANKIT SHARMA
Marketing Data Analyst

Snowflake Expert • Python • SQL
Data Engineering • Gen AI
Business Intelligence

Open to Data Engineer & Analyst Roles

View Portfolio →
```

### Option 3: Achievement-Focused
```
ANKIT SHARMA
Transforming Data into Insights

$70M ARR Business Analytics
Data Pipeline Automation
Snowflake • Tableau • Python

Aspiring Data Engineer

View Portfolio →
```

---

## 🔄 Updating Your Preview

When you update your portfolio:
1. Create new preview image
2. Replace `og-image.png` in repository
3. Clear cache on social platforms
4. Test with validators

---

## ✅ Checklist

After creating preview image:
- [ ] Image is 1200 x 630 pixels
- [ ] File size under 1MB
- [ ] Saved as `og-image.png`
- [ ] Uploaded to repository
- [ ] Meta tags added to HTML
- [ ] Tested on LinkedIn
- [ ] Tested on Twitter
- [ ] Text is readable
- [ ] Professional appearance

---

## 🎨 Color Palette for Your Brand

Based on your portfolio:

```
Primary: #6366f1 (Indigo)
Secondary: #8b5cf6 (Violet)
Accent: #ec4899 (Pink)
Text: #ffffff (White)
Background: Linear gradient (Indigo to Violet)
```

---

**Your preview image will make your portfolio stand out on social media! 🎉**

Good luck with your job search! 🚀
