# 📦 How to Get a DOI from Zenodo for This Course

## 🎯 Quick Overview

Zenodo is a free, open-access repository operated by CERN that assigns DOIs (Digital Object Identifiers) to research outputs, making them permanently citable and archived.

---

## 📋 Prerequisites

Before uploading to Zenodo, ensure you have:

✅ **GitHub repository** with all content:
   - 10 Jupyter notebooks
   - README.md
   - Manual PDF (if available)
   - .zenodo.json (metadata file)
   - CITATION.cff (citation file)
   - LICENSE file

✅ **ORCID iD** (optional but recommended):
   - Get free at: https://orcid.org/register
   - Links your publications permanently to you

---

## 🚀 Step-by-Step Process

### **Method 1: Automatic GitHub-Zenodo Integration (RECOMMENDED)**

This is the easiest method - Zenodo automatically archives every GitHub release.

#### **Step 1: Create Zenodo Account**
1. Go to https://zenodo.org
2. Click "Log in" → "Sign up"
3. Sign up with GitHub account (easier) or email

#### **Step 2: Enable GitHub Integration**
1. Log into Zenodo
2. Click your profile → "GitHub" (in dropdown)
3. Click "Sync now" to see your repositories
4. Toggle ON for "Research_Methodology" repository

#### **Step 3: Create GitHub Release**
1. Go to your GitHub repository
2. Click "Releases" → "Create a new release"
3. Fill in:
   - **Tag version:** v1.1.0
   - **Release title:** Research Methodology v1.1.0 - Complete Course with Experimental Designs
   - **Description:**
     ```
     ## Version 1.1.0 - January 2026
     
     ### ✨ What's New
     - Added Unit 2 Part 3: Experimental Designs & Sampling
     - Interactive CRD, RBD, and Factorial demonstrations
     - Sample size calculator and power analysis tools
     - Complete experimental design coverage
     
     ### 📚 Complete Course Contents
     - 10 comprehensive Jupyter notebooks
     - 60+ interactive visualizations
     - 35+ hands-on activities
     - Western Odisha biodiversity examples
     - Complete research design to ethics
     
     ### 🎓 For Educators and Students
     Perfect for undergraduate research methodology courses.
     All notebooks are Google Colab compatible - no installation required.
     ```
4. Click "Publish release"

#### **Step 4: Zenodo Automatically Creates Archive**
- Zenodo automatically detects the release
- Creates archive within minutes
- Assigns DOI automatically
- Uses metadata from .zenodo.json

#### **Step 5: Get Your DOI**
1. Go back to Zenodo
2. Click "Upload" → "GitHub"
3. Find your repository
4. Click on the version
5. Your DOI will be displayed: `10.5281/zenodo.XXXXXX`

---

### **Method 2: Manual Upload to Zenodo**

Use this if you don't want GitHub integration.

#### **Step 1: Prepare Archive**
1. Download your entire repository as ZIP from GitHub
2. OR create a ZIP file containing:
   - All 10 notebooks
   - README.md
   - Manual PDF
   - Any other important files

#### **Step 2: Upload to Zenodo**
1. Log into Zenodo
2. Click "Upload" → "New upload"
3. Drag and drop your ZIP file

#### **Step 3: Fill Metadata**

**Basic Information:**
- **Title:** Research Methodology: An Interactive Journey - From Mystery to Method
- **Authors:** Alok Patel (add ORCID if you have)
- **Affiliation:** Department of Zoology, Kuchinda College, Sambalpur University
- **Description:**
  ```
  A comprehensive, interactive course on research methodology for BSc Zoology students,
  featuring 10 Jupyter notebooks with hands-on demonstrations, regional examples from
  Western Odisha, and a unique philosophical approach bridging human mystery to 
  biological research. Includes complete coverage of experimental designs (CRD, RBD,
  Factorial), sample size determination, power analysis, and research ethics.
  ```

**Additional Details:**
- **Version:** 1.1.0
- **Publication date:** 2026-01-02
- **Language:** English
- **Keywords:** research methodology, zoology education, experimental design, statistical power, sample size, jupyter notebooks, interactive learning, science education, India, Odisha, emergence, CRD, RBD, factorial design, ethics
- **License:** Creative Commons Attribution 4.0 International (CC BY 4.0)
- **Upload type:** Lesson

**Related Identifiers:**
- **GitHub Repository:** https://github.com/The-Pattern-Hunter/Research_Methodology

#### **Step 4: Submit**
1. Preview your upload
2. Click "Publish"
3. DOI is assigned immediately!

---

## 📝 After Getting Your DOI

### **1. Update README.md**

Add DOI badge at the top:

```markdown
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.XXXXXX.svg)](https://doi.org/10.5281/zenodo.XXXXXX)
```

Replace `XXXXXX` with your actual Zenodo number.

### **2. Update Citation Section**

Add to your README:

```markdown
## 📖 Citation

If you use this course, please cite:

**APA:**
Patel, A. (2026). Research Methodology: An Interactive Journey - From Mystery to Method (Version 1.1.0) [Computer software]. Zenodo. https://doi.org/10.5281/zenodo.XXXXXX

**BibTeX:**
@software{patel_2026_research,
  author       = {Patel, Alok},
  title        = {Research Methodology: An Interactive Journey - From Mystery to Method},
  year         = 2026,
  publisher    = {Zenodo},
  version      = {1.1.0},
  doi          = {10.5281/zenodo.XXXXXX},
  url          = {https://doi.org/10.5281/zenodo.XXXXXX}
}
```

### **3. Add Citation File**

GitHub now shows a "Cite this repository" button automatically if you have CITATION.cff!

---

## ✨ Benefits of Zenodo DOI

✅ **Permanent Archive:** Content preserved forever, even if GitHub goes down  
✅ **Citable:** Proper academic citation with DOI  
✅ **Discoverable:** Listed in academic search engines  
✅ **Version Control:** Each release gets its own DOI  
✅ **Free:** Completely free, no limits  
✅ **Trusted:** Operated by CERN, used by researchers worldwide  
✅ **Usage Statistics:** See how many people cite/download your work  

---

## 🔄 Updating After First DOI

**For new versions:**
1. Make updates to GitHub
2. Create new release (v1.2.0, v1.3.0, etc.)
3. Zenodo automatically creates new version
4. Each version gets its own DOI
5. Concept DOI remains the same (always points to latest)

**Two types of DOIs:**
- **Version DOI:** Specific to one version (e.g., v1.1.0)
- **Concept DOI:** Always points to latest version

**Use concept DOI** in your README so it always points to the newest version!

---

## 💡 Pro Tips

1. **Create release for major updates only** - Don't create a release for every small fix
2. **Write good release notes** - Helps users understand what changed
3. **Use semantic versioning:**
   - v1.0.0 → v1.1.0 (new features)
   - v1.1.0 → v1.1.1 (bug fixes)
   - v1.1.0 → v2.0.0 (major changes)

4. **Add ORCID** - Links all your work together permanently
5. **Share widely** - Tweet, email colleagues, share on LinkedIn
6. **Update CV** - Add DOI to your publications list

---

## 📞 Support

**Zenodo Help:**
- Documentation: https://help.zenodo.org
- Contact: support@zenodo.org

**GitHub Releases:**
- Guide: https://docs.github.com/en/repositories/releasing-projects-on-github

---

## ✅ Checklist Before Upload

- [ ] All 10 notebooks uploaded to GitHub
- [ ] README.md complete and updated
- [ ] Manual PDF available (if you have it)
- [ ] .zenodo.json file in repository
- [ ] CITATION.cff file in repository
- [ ] LICENSE file in repository
- [ ] GitHub repository is public
- [ ] Created Zenodo account
- [ ] (Optional) Created ORCID account
- [ ] Ready to create GitHub release!

---

**Good luck! Your course will have a permanent, citable home! 🎉📚**
