# ShroomScan - Research Website

## Project Overview
ShroomScan is a comprehensive research project website for publishing documentation, presentations, team information, and project milestones related to mushroom disease detection research.

## Website Structure

```
ShroomScan/
│
├── index.html                 # Home Page
├── assets/
│   ├── css/
│   │   └── styles.css        # Main stylesheet with brand colors
│   └── images/               # Directory for project images
│
├── pages/
│   ├── domain.html           # Research domain & background
│   ├── milestones.html       # Project milestones & timeline
│   ├── documents.html        # Project documents & reports
│   ├── slides.html           # Presentations & slides
│   ├── about.html            # Team members & supervisors
│   └── contact.html          # Contact information & form
│
└── README.md                 # This file
```

## Brand Colors
- **Primary Color**: #8a6a48 (Dark Brown)
- **Secondary Color**: #c8b296 (Light Tan)

## Pages Overview

### 1. **Home** (`index.html`)
- General project introduction
- Project overview with key features
- Quick links to main sections
- Attractive hero section

### 2. **Domain** (`pages/domain.html`)
- Literature Survey
- Research Gap Analysis
- Research Problem Statement
- Research Objectives
- Methodology
- Technologies Used

### 3. **Milestones** (`pages/milestones.html`)
- Project timeline with interactive timeline view
- Milestone details with dates and marks allocation
- Assessment summary
- Marks distribution table

### 4. **Documents** (`pages/documents.html`)
- Core documentation (Project Charter, Proposal)
- Status documents & progress reports
- Checklists & guidelines
- Final reports & deliverables
- Document categorization

### 5. **Slides** (`pages/slides.html`)
- Proposal presentation
- Progress presentations (1 & 2)
- Final presentation
- Supplementary materials
- Presentation schedule table

### 6. **About Us** (`pages/about.html`)
- Project overview
- Team members with roles and contact details
- Supervisors & advisors
- Key achievements
- Technical expertise showcase

### 7. **Contact Us** (`pages/contact.html`)
- Contact information
- Contact form
- Direct team contacts
- Email inquiry template
- FAQs
- Additional resources

## Features

### Design & Layout
- ✅ Consistent navigation throughout all pages
- ✅ Responsive design for mobile and desktop
- ✅ Clean, professional aesthetic with brand colors
- ✅ Easy-to-navigate menu structure
- ✅ Sticky navigation header

### Content Organization
- ✅ Cards and grid layouts for visual appeal
- ✅ Interactive timeline for milestones
- ✅ Document listing with download links
- ✅ Team member profiles with contact details
- ✅ Organized document categories

### User Experience
- ✅ Clear page titles and sections
- ✅ Breadcrumb navigation (via consistent menu)
- ✅ Quick links between related pages
- ✅ Contact information accessible on every page
- ✅ Footer with copyright and institution details

## Getting Started

### Local Development
1. Clone or download the project files
2. Open `index.html` in a web browser
3. Navigate through different pages using the menu
4. All pages are linked and functional

### Structure Tips for Future Development
- Keep all HTML files in the root or `pages/` directory
- Maintain the `assets/` folder structure for CSS and images
- Use relative paths for linking between pages
- Always update navigation when adding new pages

## File Paths Reference

### From Root (index.html)
```
- Link to pages: pages/domain.html
- Link to CSS: assets/css/styles.css
```

### From Pages Directory
```
- Link to home: ../index.html
- Link to other pages: domain.html (same directory)
- Link to CSS: ../assets/css/styles.css
```

## Customization Guide

### Update Content
1. Open the respective HTML file in a text editor
2. Find the section with dummy content
3. Replace with actual content
4. Save the file

### Change Colors
1. Open `assets/css/styles.css`
2. Replace color codes:
   - `#8a6a48` - Dark Brown (primary)
   - `#c8b296` - Light Tan (secondary)

### Add Team Members
1. Go to `pages/about.html`
2. Duplicate the team member card structure
3. Update name, role, and email
4. Save the file

### Add New Pages
1. Create a new HTML file in the `pages/` directory
2. Copy the header/footer structure from an existing page
3. Update the page content and title
4. Add navigation links in all pages

## Technologies Used
- **HTML5** - Structure
- **CSS3** - Styling and responsive design
- **Vanilla JavaScript** - Interactivity (if needed)

## Browser Compatibility
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Deployment

### For Hosting
1. Upload all files to your web server
2. Ensure the folder structure is maintained
3. Test all links after uploading
4. Update contact information before going live

### Recommended Hosting Options
- GitHub Pages (free static hosting)
- Netlify (free with great performance)
- Vercel (free for static sites)
- Traditional web hosting services

## Important Notes

### Dummy Content
All content in the current version is placeholder/dummy content. Replace with actual project information:
- Team member names and emails
- Actual presentation dates and details
- Real document links
- Actual contact information
- Project-specific details

### Links
Document download links currently point to `#` and need to be updated with actual file paths:
```html
<!-- Update from: -->
<a href="#">Download PDF</a>

<!-- To: -->
<a href="path/to/document.pdf">Download PDF</a>
```

### Form Submission
The contact form is currently HTML-only. To make it functional, add backend processing:
- Use a form service like Formspree or Netlify Forms
- Set up a backend API endpoint
- Implement email notifications

## Future Enhancements
- Add JavaScript form validation
- Implement form submission functionality
- Add image gallery for project images
- Create blog/news section
- Add search functionality
- Implement database for documents
- Add user authentication for document access
- Mobile app integration

## Support & Maintenance
For questions or issues:
1. Check the contact page for team emails
2. Review documentation in the `Documents` section
3. Refer to the FAQ section in `Contact Us`

## License & Attribution
© 2024 ShroomScan Research Project. All rights reserved.
Faculty of Computing | Sri Lanka Institute of Information Technology (SLIIT)

---

**Last Updated**: April 2024
**Project Status**: Active Development
**Version**: 1.0 (Initial Structure)