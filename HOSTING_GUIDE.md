# ShroomScan Website - Hosting & Deployment Guide

## Quick Start

Your ShroomScan website is now ready! Follow this guide to get it online.

## Step 1: Test Locally

Before deploying, test your website locally:

1. **Open in Browser**
   - Navigate to your project folder: `d:\Y4S2\ShroomScan`
   - Open `index.html` with your browser
   - Click through all pages to ensure everything works

2. **Check for Issues**
   - Verify all links work correctly
   - Ensure styling loads properly
   - Test on different browsers (Chrome, Firefox, Edge)

## Step 2: Update Dummy Content

Before hosting, replace placeholder content:

### In `pages/about.html`:
- [ ] Replace "Member Name 1, 2, 3, 4" with actual team member names
- [ ] Replace "member@student.sliit.lk" with actual emails
- [ ] Replace supervisor names with actual supervisors
- [ ] Update roles and descriptions

### In `pages/contact.html`:
- [ ] Update "General Phone" number with SLIIT contact
- [ ] Update "Project Email" address
- [ ] Update supervisor contact details
- [ ] Replace "Dr. Supervisor Name" with actual names

### In `pages/domain.html`, `milestones.html`, `documents.html`:
- [ ] Replace dummy dates with actual project dates
- [ ] Update document descriptions with real information
- [ ] Add actual marks and weightages

## Step 3: Add Document Links

Update the document download links in `pages/documents.html`:

```html
<!-- Change from: -->
<a href="#" class="document-link">View/Download</a>

<!-- To: -->
<a href="path/to/your/document.pdf" class="document-link">View/Download</a>
```

## Recommended Hosting Solutions

### Option 1: GitHub Pages (FREE - Recommended for Students)

**Advantages:**
- Free hosting
- Easy version control with Git
- Perfect for project portfolios
- HTTPS included
- GitHub integration

**Steps:**
1. Create a GitHub account at github.com
2. Create a new repository named `ShroomScan`
3. Upload your project files
4. Go to Settings → Pages → Select main branch
5. Your site will be live at: `https://yourusername.github.io/ShroomScan`

**Time to Deploy:** 5-10 minutes

### Option 2: Netlify (FREE - Recommended for Best Performance)

**Advantages:**
- Very fast performance
- Free SSL certificate
- Easy deployment
- Good UI
- Automatic deployments with Git

**Steps:**
1. Go to netlify.com
2. Click "Sign up"
3. Connect your GitHub account
4. Select your ShroomScan repository
5. Click "Deploy"
6. Your site will be live within minutes

**Time to Deploy:** 3-5 minutes

### Option 3: Vercel (FREE - Excellent Performance)

**Advantages:**
- Excellent performance
- Easy Git integration
- Free hosting
- Good for static sites
- Analytics included

**Steps:**
1. Go to vercel.com
2. Click "Sign Up"
3. Connect GitHub
4. Import your repository
5. Deploy
6. Site is live

**Time to Deploy:** 2-3 minutes

### Option 4: Traditional Web Hosting

**Recommended Providers:**
- Bluehost ($2.95/month)
- HostGator ($2.75/month)
- GoDaddy (varies)
- SiteGround ($3.99/month)

**Steps:**
1. Purchase hosting plan
2. Get FTP credentials
3. Use FileZilla or similar FTP client
4. Upload all files maintaining folder structure
5. Site is live

**Time to Deploy:** 10-30 minutes

## File Structure for Hosting

When uploading, maintain this structure:

```
your-domain.com/
│
├── index.html
├── assets/
│   ├── css/
│   │   └── styles.css
│   └── images/
│
└── pages/
    ├── domain.html
    ├── milestones.html
    ├── documents.html
    ├── slides.html
    ├── about.html
    └── contact.html
```

**Important:** If your files are in a subdirectory (like GitHub Pages), update the paths:

```html
<!-- In index.html -->
<link rel="stylesheet" href="assets/css/styles.css">

<!-- Becomes (if using subdirectory): -->
<link rel="stylesheet" href="/ShroomScan/assets/css/styles.css">
```

## Post-Deployment Checklist

After hosting your site:

- [ ] Test all page links (from different browsers)
- [ ] Verify CSS styling loads correctly
- [ ] Check responsive design on mobile devices
- [ ] Test contact form (if you add backend)
- [ ] Update document download links
- [ ] Share the URL with stakeholders
- [ ] Monitor site performance
- [ ] Keep content updated

## Making Updates

### If Using GitHub Pages / Netlify

1. Update files locally
2. Commit changes: `git add .`
3. Commit: `git commit -m "Update content"`
4. Push: `git push`
5. Site updates automatically (usually within 1-2 minutes)

### If Using Traditional Hosting

1. Update files locally
2. Upload via FTP
3. Changes appear immediately

## Next Steps

### Phase 2: Enhance the Website

1. **Add Images**
   - Add project logos to `assets/images/`
   - Update team member images
   - Include project screenshots

2. **Add Content**
   - Replace all dummy content with real data
   - Upload actual documents and presentations
   - Add real team member photos (optional)

3. **Add Functionality**
   - Implement working contact form
   - Add document search functionality
   - Create news/blog section
   - Add project gallery

### Phase 3: Advanced Features

1. **Setup Contact Form**
   - Use Formspree for free form handling
   - Or setup backend API
   - Configure email notifications

2. **Add Analytics**
   - Setup Google Analytics
   - Track visitor behavior
   - Monitor popular pages

3. **SEO Optimization**
   - Add meta descriptions
   - Setup Google Search Console
   - Submit sitemap

## Troubleshooting

### Issue: CSS not loading
- Check file paths are correct
- Ensure folder structure matches links
- Clear browser cache

### Issue: Links not working
- Verify relative paths
- Check for typos in file names
- Ensure all files are uploaded

### Issue: Images not showing
- Confirm images are in `assets/images/`
- Check image file paths in HTML
- Ensure image file names match exactly (case-sensitive)

### Issue: Mobile responsive not working
- Check viewport meta tag in HTML
- Verify CSS media queries
- Test in mobile browser dev tools

## Domain Name (Optional)

If you want a custom domain (instead of github.io):

1. Buy domain from: GoDaddy, Namecheap, or similar
2. Update DNS settings to point to hosting service
3. Wait 24-48 hours for DNS to propagate
4. Your site will be at your custom domain

Popular domains:
- `shroomscan.lk` (~$5-10/year)
- `shroomscan.com` (~$10-15/year)

## Security Notes

- [ ] Use HTTPS (all recommended hosting provides this)
- [ ] Keep software updated
- [ ] If using contact form, validate user input
- [ ] Backup your files regularly
- [ ] Use strong passwords for hosting accounts

## Support Resources

### Hosting Help:
- GitHub Pages: docs.github.com/pages
- Netlify: netlify.com/docs
- Vercel: vercel.com/docs

### HTML/CSS Help:
- MDN Web Docs: developer.mozilla.org
- W3Schools: w3schools.com
- CSS-Tricks: css-tricks.com

## Estimated Timeline

- **Local testing**: 10-15 minutes
- **Update content**: 30-60 minutes
- **Deploy to hosting**: 5-30 minutes (depends on platform)
- **Total time**: 1-2 hours

## Questions?

If you encounter any issues:
1. Check this guide's troubleshooting section
2. Check the README.md file
3. Visit hosting provider's documentation
4. Contact your supervisor

---

**Ready to Deploy?** 
Pick your hosting option and follow the steps above. Your ShroomScan website will be online in minutes!

**Last Updated**: April 2024
