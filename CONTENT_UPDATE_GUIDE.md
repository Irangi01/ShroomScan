# ShroomScan - Content Update Quick Reference

Use this guide to quickly locate and update all dummy content on your website.

## Directory Map

```
📁 ShroomScan/
  📄 index.html (Home Page)
  📁 pages/
    📄 domain.html (Research Domain)
    📄 milestones.html (Project Milestones)
    📄 documents.html (Documentation)
    📄 slides.html (Presentations)
    📄 about.html (Team Members)
    📄 contact.html (Contact Info)
  📁 assets/
    📁 css/
      📄 styles.css (Styling)
    📁 images/ (Add your images here)
```

---

## Page-by-Page Update Guide

### 🏠 HOME PAGE (`index.html`)

**Hero Section:**
- Project Title: "ShroomScan" ✓ (already updated)
- Project Subtitle: "Advanced Mushroom Disease Detection..." ✓ (already updated)

**Content Sections:**
- Update card descriptions with actual project details
- Add relevant project statistics

---

### 🔬 DOMAIN PAGE (`pages/domain.html`)

**Section: Literature Survey**
- [ ] Update with your actual literature findings
- [ ] Add real research papers and references

**Section: Research Gap**
- [ ] Replace dummy gap analysis with actual findings
- [ ] Add specific research gaps you identified

**Section: Research Problem**
- [ ] Update problem statement
- [ ] Modify sub-objectives

**Section: Research Objectives**
- [ ] Update primary and secondary objectives

**Section: Methodology**
- [ ] Replace dummy methodology with your actual approach
- [ ] Update research process steps

**Section: Technologies Used**
- [ ] Update technologies you're actually using
- [ ] Remove/add as needed

---

### 📅 MILESTONES PAGE (`pages/milestones.html`)

**Update Dates:**
| Component | Current Date | Your Date |
|-----------|--------------|-----------|
| Project Proposal | April 3rd, 2023 | __________ |
| Progress 1 | May 25th, 2023 | __________ |
| Progress 2 | September 7th, 2023 | __________ |
| Final Assessment | October 30th, 2023 | __________ |

**Update Marks:**
- [ ] Project Proposal: 5% → ____%
- [ ] Progress 1: 10% → ____%
- [ ] Progress 2: 18% → ____%
- [ ] Final Assessment: 25% → ____%
- [ ] Additional: 42% → ____%

**Update Descriptions:**
- [ ] Proposal presentation description
- [ ] Progress presentation 1 details
- [ ] Progress presentation 2 details
- [ ] Final assessment description

---

### 📚 DOCUMENTS PAGE (`pages/documents.html`)

**Core Documents:**
- [ ] Project Charter - update link
- [ ] Proposal Document - update link

**Status Documents:**
- [ ] Status Document 1 - update date and link
- [ ] Status Document 2 - update date and link

**Checklists:**
- [ ] Update checklist titles and links
- [ ] Add any missing checklists

**Final Reports:**
- [ ] Update report names
- [ ] Add links to actual documents
- [ ] Update descriptions

---

### 🎬 SLIDES PAGE (`pages/slides.html`)

**Presentations to Update:**

1. **Proposal Presentation**
   - Date: __________ (current: April 3rd, 2023)
   - Description: ____________________
   - Link: __________________________

2. **Progress Presentation 1**
   - Date: __________ (current: May 25th, 2023)
   - Description: ____________________
   - Link: __________________________

3. **Progress Presentation 2**
   - Date: __________ (current: September 7th, 2023)
   - Description: ____________________
   - Link: __________________________

4. **Final Presentation**
   - Date: __________ (current: October 30th, 2023)
   - Description: ____________________
   - Link: __________________________

---

### 👥 ABOUT PAGE (`pages/about.html`)

**Team Members - Update All:**

**Member 1**
- Name: Member Name 1 → __________________
- Role: ML Engineer & Backend Developer → __________________
- Email: member1@student.sliit.lk → __________________
- Description: Update with actual focus areas

**Member 2**
- Name: Member Name 2 → __________________
- Role: Frontend Developer & UI/UX Designer → __________________
- Email: member2@student.sliit.lk → __________________
- Description: Update with actual focus areas

**Member 3**
- Name: Member Name 3 → __________________
- Role: Database Designer & DevOps Engineer → __________________
- Email: member3@student.sliit.lk → __________________
- Description: Update with actual focus areas

**Member 4**
- Name: Member Name 4 → __________________
- Role: Data Scientist & Research Analyst → __________________
- Email: member4@student.sliit.lk → __________________
- Description: Update with actual focus areas

**Supervisors:**

**Supervisor 1**
- Name: Dr. Supervisor Name 1 → __________________
- Title: Project Supervisor → __________________
- Email: supervisor1@sliit.lk → __________________

**Supervisor 2**
- Name: Dr. Supervisor Name 2 → __________________
- Title: Co-Supervisor → __________________
- Email: supervisor2@sliit.lk → __________________

**Advisor**
- Name: Prof. Advisor Name → __________________
- Title: Project Advisor → __________________
- Email: advisor@sliit.lk → __________________

---

### 📞 CONTACT PAGE (`pages/contact.html`)

**Contact Information:**
- [ ] Institution: "Sri Lanka Institute of Information Technology (SLIIT)" ✓
- [ ] Faculty: "Faculty of Computing" ✓
- [ ] General Phone: "+94 (0) 11 203 5000" → __________________
- [ ] Project Email: "shroomscan@sliit.lk" → __________________
- [ ] Office Hours: Update if different

**Team Contacts - Update:**

1. **Project Supervisor**
   - Name: Dr. Supervisor Name → __________________
   - Email: supervisor@sliit.lk → __________________
   - Phone: +94 (0) 11 203 5000 (Ext: 3001) → __________________

2. **Co-Supervisor**
   - Name: Dr. Co-Supervisor Name → __________________
   - Email: cosupervisor@sliit.lk → __________________
   - Phone: +94 (0) 11 203 5000 (Ext: 3002) → __________________

3. **Development Lead**
   - Name: Member Name 1 → __________________
   - Email: member1@student.sliit.lk → __________________

4. **UI/UX Lead**
   - Name: Member Name 2 → __________________
   - Email: member2@student.sliit.lk → __________________

---

## Color References (If Changing)

**Current Brand Colors:**
- Primary: `#8a6a48` (Dark Brown)
- Secondary: `#c8b296` (Light Tan)

To change colors:
1. Open `assets/css/styles.css`
2. Find: `#8a6a48` and replace with your primary color
3. Find: `#c8b296` and replace with your secondary color
4. Save and refresh browser

---

## File Links to Update

**Document Download Links** in `pages/documents.html`:
```html
<!-- Change from: -->
<a href="#">Download PDF</a>

<!-- To: -->
<a href="path/to/your/document.pdf">Download PDF</a>
```

**Presentation Download Links** in `pages/slides.html`:
```html
<!-- Change from: -->
<a href="#">⬇️ Download PDF</a>

<!-- To: -->
<a href="path/to/your/presentation.pdf">⬇️ Download PDF</a>
```

---

## Adding Images

1. Place images in: `assets/images/`
2. Reference in HTML:
   ```html
   <img src="../assets/images/your-image.png" alt="Description">
   ```

---

## Quick Find & Replace

Use your text editor's Find & Replace feature (Ctrl+H):

| Find | Replace With |
|------|---------------|
| Member Name 1 | Your actual name |
| member1@student.sliit.lk | Your email |
| April 3rd, 2023 | Your date |
| Dr. Supervisor Name | Actual supervisor |

---

## Content Checklist

- [ ] All team member names updated
- [ ] All email addresses updated
- [ ] All dates updated to actual project dates
- [ ] All supervisor information updated
- [ ] Document links pointing to actual files
- [ ] Presentation links working
- [ ] Contact information current
- [ ] No dummy content remaining
- [ ] All links tested
- [ ] Site tested on mobile devices

---

## Testing Checklist

After updating content:
- [ ] Home page loads correctly
- [ ] All navigation links work
- [ ] All pages display properly
- [ ] CSS styles loaded
- [ ] Images display (if added)
- [ ] Contact form functional
- [ ] Mobile responsive working
- [ ] No broken links
- [ ] No console errors

---

## Next Steps

1. **Print this guide** or keep it handy
2. **Go through each page** and update content
3. **Test all links** after updates
4. **Deploy to hosting** when ready
5. **Share URL** with stakeholders

---

**Need Help?**
- Check README.md for more details
- Check HOSTING_GUIDE.md for deployment help
- Check specific page comments for editing hints

Last Updated: April 2024
