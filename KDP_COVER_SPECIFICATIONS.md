# Journal 3 - Amazon KDP Cover Specifications

## Overview
This document outlines the complete cover design specifications for Journal 3 according to Amazon Kindle Direct Publishing (KDP) print guidelines.

## Physical Specifications

### Trim Size
- **Dimensions:** 6" × 9" (inches)
- **In pixels (300 DPI):** 1800 × 2700 pixels
- **Aspect Ratio:** 2:3

### Resolution & Color
- **Resolution:** 300 DPI minimum (mandatory for print quality)
- **Color Mode:** CMYK for best print results (RGB will be converted by KDP)
- **File Format:** PDF (preferred) or high-resolution image files

### Bleed & Safe Areas
- **Bleed Area:** 0.125" (37.5px @ 300 DPI) on all sides
  - Content extending to bleed area will be cut during production
  - Use for full-bleed backgrounds and images
  
- **Safe Area:** 0.25" (75px @ 300 DPI) from all edges
  - Keep all critical content (text, logos) within this area
  - Ensures no content is accidentally cut off

- **Safe Area Calculation:**
  - Top/Bottom: 0.25" from edge = 75px from top and bottom
  - Left/Right: 0.25" from edge = 75px from left and right

### Cover Components

#### Front Cover (6" × 9")
- **Title:** "Journal 3"
- **Subtitle:** "My Reflections"
- **Tagline:** "A Year of Growth, Gratitude & Purpose"
- **Design Elements:**
  - Gradient background (dark blue to slate)
  - Decorative gold accent lines
  - Professional typography hierarchy
  - Color scheme: Navy/slate background with white and gold accents

#### Back Cover (6" × 9")
**Required Elements:**
- Author description or about section
- Testimonials or benefits list
- ISBN barcode placement (2" × 2", typically in bottom-right corner)
- Barcode needs 0.25" white space around it
- Optional: Author photo, tagline, call-to-action

#### Spine
- **Width Calculation:** (Total Page Count × Paper Thickness) + 0.02"
  - For 365 pages with 80 gsm paper: ~0.27"
  - For 200 pages with 80 gsm paper: ~0.15"
- **Spine Text:** Oriented vertically (spine text should be readable when spine faces up)
- **Required Spacing:** 0.125" from edges on spine

## File Requirements

### PDF Specifications
- **Embed all fonts** - Do not use system fonts
- **Color Profile:** Adobe RGB or sRGB (will be converted to CMYK by KDP)
- **Compression:** Minimal to maintain quality
- **File Size:** Under 100MB recommended

### File Submission
1. Create PDF with proper dimensions including bleed
2. Name file: `Journal3_Cover.pdf`
3. Upload through Amazon KDP dashboard
4. Use KDP's cover previewer to verify appearance
5. Request review if needed

## Design Guidelines

### Typography
- **Fonts Used:** Georgia (serif), Professional sans-serif for subtitles
- **Font Sizes:**
  - Title: 120pt bold
  - Subtitle: 32pt uppercase
  - Tagline: 28pt italic
  - Footer: 14-18pt
- **Line Spacing:** 1.2-1.4 for readability
- **Font Weight:** Vary weights (light, regular, bold) for hierarchy

### Color Palette (CMYK Print)
- **Primary:** Navy Blue (#2c3e50) = C: 75%, M: 60%, Y: 20%, K: 60%
- **Secondary:** Slate Blue (#34495e) = C: 70%, M: 55%, Y: 15%, K: 45%
- **Accent:** Gold/Orange (#f39c12) = C: 0%, M: 30%, Y: 100%, K: 5%
- **Text:** White/Off-white (#ecf0f1) = C: 5%, M: 3%, Y: 5%, K: 0%
- **Support:** Light Gray (#bdc3c7) = C: 15%, M: 10%, Y: 10%, K: 0%

### Layout
- **Centered composition** for professional appearance
- **Vertical hierarchy:** Subtitle → Title → Number → Tagline
- **White space:** Generous margins and breathing room
- **Visual balance:** Symmetrical design with decorative elements

## Quality Checklist

Before submitting to KDP:

- [ ] File is 6" × 9" (1800 × 2700px at 300 DPI)
- [ ] 0.125" bleed area on all sides included
- [ ] All critical content within 0.25" safe area
- [ ] Resolution is minimum 300 DPI
- [ ] File is in PDF format
- [ ] All fonts are embedded
- [ ] Color is in CMYK or RGB (will convert to CMYK)
- [ ] Text is not pixelated or fuzzy
- [ ] ISBN barcode area is reserved (back cover)
- [ ] Cover is tested with KDP previewer
- [ ] No overlapping text or images
- [ ] File size is under 100MB
- [ ] Back cover content is clear and readable
- [ ] Spine text (if applicable) is properly oriented

## Troubleshooting

### Common Issues

**Issue: Content appears cut off in preview**
- Solution: Move content further into safe area (at least 0.25" from edges)

**Issue: Colors look different than expected**
- Solution: Ensure CMYK color profile; different monitors display RGB vs CMYK differently

**Issue: Text appears blurry in print**
- Solution: Ensure 300 DPI resolution; use raster text at native resolution

**Issue: Fonts not displaying correctly**
- Solution: Embed all fonts in PDF; test on multiple systems before upload

## References

- [Amazon KDP Specifications](https://kdp.amazon.com/en_US/help/topic/G202151810)
- [Print Book Trim Sizes](https://kdp.amazon.com/en_US/help/topic/G201834540)
- [Print Book Setup Guide](https://kdp.amazon.com/en_US/help/topic/G201895840)
- [Image Guidelines](https://kdp.amazon.com/en_US/help/topic/G202135320)

## Next Steps

1. **Edit the HTML file** (`journal-3-cover.html`) to customize:
   - Title, subtitle, and tagline text
   - Color scheme (modify CSS)
   - Add author information for back cover
   - Adjust fonts and sizing

2. **Convert to PDF:**
   - Open HTML in browser
   - Use "Print to PDF" (Ctrl+P → Save as PDF)
   - Or use professional design software (Canva, Adobe InDesign, Affinity Publisher)

3. **Verify in KDP Previewer:**
   - Upload to Amazon KDP
   - Use their cover previewer tool
   - Check for any cutoff or quality issues

4. **Add Back Cover & Spine:**
   - Extend design to include back cover
   - Calculate and include spine width
   - Add ISBN barcode area on back cover

## Contact & Support

For questions about specific Amazon KDP requirements, visit the [KDP Help Center](https://kdp.amazon.com/en_US/help).
