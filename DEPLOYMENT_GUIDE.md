# 🕉️ Shri Mahavir Mandir Website - Complete Setup Guide

## ✅ What You Have
A fully functional, beautiful temple website with:
- Responsive design (works on mobile, tablet, desktop)
- Beautiful spiritual theme with animations
- All sections from your PowerPoint
- No external dependencies (works offline)
- Complete control - edit anything you want!

## 🌐 How to Get Your Website Online (3 Easy Options)

### OPTION 1: FREE Hosting with GitHub Pages (Recommended) ⭐
**100% FREE forever with your own URL**

1. Create a GitHub account at https://github.com (if you don't have one)
2. Create a new repository named `temple-website`
3. Upload the `hanuman_temple_website.html` file
4. Rename it to `index.html`
5. Go to Settings → Pages → Enable GitHub Pages
6. Your website will be live at: `https://yourusername.github.io/temple-website`
7. You can add a custom domain later (like www.mahavirmandirphusro.org)

**Full Control:** You can edit files anytime through GitHub's web interface or download and edit locally.

### OPTION 2: FREE Hosting with Netlify 🚀
**Easiest option with drag-and-drop**

1. Go to https://www.netlify.com
2. Sign up for free account
3. Drag and drop your `hanuman_temple_website.html` file
4. Rename it to `index.html` when prompted
5. Your site is live instantly!
6. Get a free URL like: `temple-phusro.netlify.app`
7. Can add custom domain easily

**Full Control:** Edit files anytime through Netlify dashboard or connect to GitHub for automatic updates.

### OPTION 3: Paid Hosting with Full Control 💪
**Best for complete control with email and database**

Popular affordable options:
- **Hostinger** (~₹49/month) - Indian company
- **Bluehost** (~₹199/month)
- **GoDaddy** (~₹99/month)

1. Buy hosting + domain (like mahavirmandirphusro.com)
2. Upload `hanuman_temple_website.html` via cPanel File Manager
3. Rename to `index.html`
4. Your website is live!

**Full Control:** Access via FTP, cPanel, or File Manager. Edit anytime.

## 📝 How to Edit Your Website (You Have FULL Control!)

### To Edit Text, Colors, Images:
1. Open `hanuman_temple_website.html` in any text editor (Notepad, VS Code, etc.)
2. All content is clearly labeled with comments
3. Change any text between `>` and `<` tags
4. Change colors in the `:root` section at the top
5. Save and re-upload

### Key Sections to Customize:

**1. Change Temple Name/Location:**
```html
Find: श्री महावीर मंदिर, फुसरो
Replace with: Your temple name
```

**2. Change Phone Number:**
```html
Find: +91 XXXXX XXXXX
Replace with: Your actual number
```

**3. Change Email:**
```html
Find: info@mahavirmandirphusro.org
Replace with: Your email
```

**4. Change Ritual Timings:**
```html
Find: 6:00 AM - 6:30 AM
Replace with: Your timings
```

**5. Add Google Maps:**
```html
Find: <div class="map-placeholder">
Replace the entire div with:
<iframe 
  src="YOUR_GOOGLE_MAPS_EMBED_URL" 
  width="100%" 
  height="400" 
  style="border:0; border-radius:15px;" 
  allowfullscreen="" 
  loading="lazy">
</iframe>
```
Get embed URL from: https://www.google.com/maps → Share → Embed a map

**6. Add Temple Photos to Gallery:**
Upload images and replace:
```html
<div class="gallery-item"></div>
With:
<div class="gallery-item">
  <img src="your-photo.jpg" style="width:100%; height:100%; object-fit:cover;">
</div>
```

**7. Add UPI Payment:**
```html
Find: temple@upi
Replace with: Your UPI ID
```

## 🎨 Customization Options

### Change Color Scheme:
In the `:root` section, modify:
```css
--saffron: #FF6B35;        /* Main orange color */
--temple-red: #C41E3A;     /* Red accents */
--gold: #FFB300;           /* Gold highlights */
```

### Change Fonts:
Replace font links in `<head>` section with fonts from https://fonts.google.com

### Add Login System:
For admin login functionality, you'll need to add backend (PHP/Node.js) or use services like:
- Firebase Authentication (free)
- Auth0 (free tier available)
- Supabase (free)

## 📱 Features Included

✅ Fully Responsive (mobile-friendly)
✅ Beautiful animations
✅ Hindi & English language support structure
✅ All sections from your PowerPoint:
  - Home with Hanuman Chalisa verses
  - Services (6 temple services)
  - Daily Rituals schedule
  - Music/Audio section
  - Gallery
  - Donation section
  - Contact information
  - About Us
  - Terms & Conditions link
  
✅ Interactive elements:
  - Smooth scrolling
  - Scroll-to-top button
  - Hover animations
  - Notification banner (rotating messages)
  - Donation buttons
  
✅ No dependencies - works offline!

## 🔐 Admin Panel (Coming Soon)

For content management, you can:
1. Use a CMS like WordPress and embed this design
2. Build a simple admin panel with PHP/Node.js
3. Use headless CMS like Contentful or Strapi (free tiers)
4. Use Google Firebase for data storage (free)

I can help you build an admin panel if needed!

## 🆘 Support & Help

### To Make Changes:
1. Download the HTML file
2. Open in any text editor
3. Make changes
4. Save
5. Re-upload to your hosting

### Need More Features?
Let me know what you'd like to add:
- Online puja booking system
- Event calendar
- Photo/video gallery with upload
- Blog section
- Newsletter signup
- Multi-language support
- Admin dashboard
- Live darshan streaming
- And more!

## 📞 Technical Support

If you need help with:
- Domain registration
- Hosting setup
- Adding features
- Custom modifications
- Admin panel development

Just let me know!

## 🎯 Next Steps

1. Download the `hanuman_temple_website.html` file
2. Choose a hosting option (GitHub Pages is easiest and free!)
3. Upload and deploy
4. Customize contact details, timings, photos
5. Share with devotees!

Your website is ready to go live! 🚩

**Jai Hanuman! 🙏**
