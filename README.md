# Sherry Walker for Guilford County School Board - Campaign Website

A professional, mobile-friendly campaign website for Sherry Walker's school board campaign.

## Files Included

- `index.html` - Home page with hero section and key messaging
- `about.html` - About page with bio and platform details
- `style.css` - Professional styling with responsive design

## How to Deploy to Netlify

### Method 1: Drag and Drop (Easiest)

1. Download all three files (index.html, about.html, style.css) to a folder on your computer
2. Log in to your Netlify account at https://app.netlify.com
3. Click "Add new site" → "Deploy manually"
4. Drag and drop the entire folder containing the three files
5. Your site will go live immediately with a URL like: `random-name-123.netlify.app`

### Method 2: Via GitHub

1. Create a new repository on GitHub
2. Upload all three files to the repository
3. In Netlify, click "Add new site" → "Import an existing project"
4. Connect to GitHub and select your repository
5. Click "Deploy site"

## Customizing the Site

### Update Contact Information
In both `index.html` and `about.html`, find and replace:
- `campaign@sherrywalker.com` with the actual campaign email

### Update Election Date
In `index.html`, find:
- `November 5, 2025` and update to the actual election date

### Add Social Media Links
In `index.html`, find the social links section and update the `#` with actual URLs:
```html
<a href="#" class="social-btn">Facebook</a>
<a href="#" class="social-btn">Twitter</a>
```

### Change Colors
In `style.css`, you can modify the main colors:
- Primary blue: `#1e3a8a`
- Accent gold: `#fbbf24`
- Background gray: `#f3f4f6`

### Add a Photo
To add Sherry's photo:
1. Upload the photo file to the same folder
2. In `index.html`, add this after the opening `<section class="hero">` tag:
```html
<img src="your-photo-name.jpg" alt="Sherry Walker" style="max-width: 200px; border-radius: 50%; margin-bottom: 2rem;">
```

## Custom Domain

Once deployed, you can add a custom domain (like sherrywalker.com):
1. In Netlify dashboard, go to "Domain settings"
2. Click "Add custom domain"
3. Follow instructions to connect your domain

## Support

For questions or modifications, contact the web developer who set this up.

---

**Paid for by Committee to Elect Sherry Walker**
