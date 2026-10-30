# Accessibility Audit Report - index.html

**Page:** About Me - Claire Wairimu

**Date:** October 27, 2026

**Tools used:** Chrome DevTools Lighthouse + WAVE

## Audit Checklist

### 1. Images: Add alt text
- **Status:** PASS with improvement
- **Issue Found:** `alt="My Photo"` is present but more descriptive enough for screen readers
- **How I Fixed:** Changed to more descriptive alt
- **Before:** `<img src="https://placehold.co/300*300" alt="My photo">`
- **After** `<img src="https://placehold.co/300*300" alt="Portrait photo of Claire Wairimu">`

### 2. Headings: Proper hierachy (h1, h2, h3)
- **Status:** PASS
- **Issue Found:** None. Structure is correct:
    -h1: Claire Wairimu (only one)
    -h2: My Hobbies, Favorite Website, Contact
- No h3 needed as there are no sub-sections, which is correct.

### 3. Links: Descriptive link text
- **Status:** PASS
- **Issue Found:** None major.
    - "MDN Web Docs" is descriptive - good.
    - Email link shows email address - acceptable, but improved to be clearer.
- **How I Improved:**
- **After:** `<a href="malito:gakuruclaire39@gmail.com">`Email me: gakuruclaire39@gmail.com</a>

### 4. Languages: lang attribute
- **Status** PASS
- **Issue Found:** None. `<html lang="en">` is correctly presented

 ### 5. Form labels
 - **Status:** N/A - PASS
 - **Issue Found:** No forms on this about page, so no labels needed. This will be covered in contact.html where all inputs have associated <label>.

### Final Lighthouse Accessibility Score
- **Before:** 92/100 (alt text could be more descriptive)
- **After:** 100/100
- **WAVE Tool:** 0 Errors, 0 Contrast Erroes

### Fixes index.html version
I updated the image alt and email link text to be more descriptive for screen readers.
  

  
 
