# QC3E Ventures - Image Assets

## Current Status: Placeholders

This directory will contain image assets for the QC3E Ventures website.

## Required Images

### Team Headshots
1. **Jake Eisaguirre**: 
   - Source: `code/terrafirma-website/images/jake-eisaguirre.jpeg` 
   - Status: Needs to be copied to this directory
   - Recommended size: 240x240px (square format)

2. **Lew Eisaguirre**: 
   - Status: Professional headshot needed
   - Recommended size: 240x240px (square format)
   - Style: Professional, business attire

3. **Joseph Eisaguirre**: 
   - Status: Professional headshot needed
   - Recommended size: 240x240px (square format)
   - Style: Professional, business attire

### Logo Assets
- **QC3E Logo**: Quarter circle cattle brand graphic
  - Status: To be provided by Jake
  - Recommended sizes: 200x60px (header), 400x120px (high res)
  - Formats: SVG preferred, PNG backup
  - Variants: Dark logo for light backgrounds, Light logo for dark backgrounds

### Optional Enhancements
- Company hero background (subtle, professional)
- Portfolio company logos (if available)
- About section background imagery

## Image Specifications

### Team Photos
- **Dimensions**: 240x240px minimum
- **Format**: JPG or PNG
- **Quality**: High resolution, professional
- **Background**: Neutral or removed
- **Lighting**: Even, professional

### Logo
- **Format**: SVG (preferred) or PNG
- **Background**: Transparent
- **Variants**: Dark and light versions
- **Usage**: Header navigation, footer, documents

## Implementation Notes

### Current CSS Setup
The CSS is already configured to handle images:
```css
.team-member img {
    width: 120px;
    height: 120px;
    border-radius: 50%;
    object-fit: cover;
    margin-bottom: var(--spacing-md);
}
```

### Placeholder System
Currently using CSS-generated placeholders:
```css
.placeholder-avatar {
    width: 120px;
    height: 120px;
    border-radius: 50%;
    background: var(--color-slate-light);
    /* ... styling for initials ... */
}
```

### Easy Replacement
To replace placeholders with actual images:
1. Add images to this directory
2. Update HTML in `team.html`:
   ```html
   <!-- Replace this -->
   <div class="placeholder-avatar">JE</div>
   
   <!-- With this -->
   <img src="images/jake-eisaguirre.jpg" alt="Jake Eisaguirre">
   ```

## File Naming Convention
- `jake-eisaguirre.jpg`
- `lew-eisaguirre.jpg` 
- `joseph-eisaguirre.jpg`
- `qc3e-logo.svg`
- `qc3e-logo-light.svg` (for dark backgrounds)

---

*Update this file as images are added*