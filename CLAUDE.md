# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a training assessment platform for Acceleronix's Bangkok All Hands meeting (August 2025). The site presents three customer case studies designed to test BD and sales team knowledge of Acceleronix IoT and Connectivity platforms after a 4-day training program.

## Architecture

**Multi-page Static Website Structure:**
- `index.html` - Homepage with case study overview and navigation
- `assets/css/home.css` - Homepage-specific styling
- `assets/css/styles.css` - Shared styling for case study pages
- `cases/` directory containing individual case study pages

**Assessment Cases:**
1. **AccelTech** - Cold chain logistics tracking in Malaysia (Case A)
2. **MotoTrack** - Two wheeler fleet management in Vietnam (Case B)  
3. **PowerFlow** - Mobile energy storage solutions in India (Case C)

**Design System:**
- Color scheme: Purple gradient (#667eea to #764ba2) with neutral backgrounds
- Typography: Inter font family with consistent weight hierarchy
- Layout: CSS Grid for card layouts, Flexbox for navigation and stats
- Responsive: Mobile-first approach with breakpoints at 768px and 480px
- Interactive elements: Hover effects, smooth scrolling, click handlers

## Development Commands

**Preview the website:**
```bash
# Serve locally (recommended):
python3 -m http.server 8000
# Then visit http://localhost:8000

# Or using Node.js:
npx serve .
```

**Deploy to Vercel:**
```bash
# Via CLI:
npm i -g vercel
vercel

# Or connect GitHub repo to Vercel dashboard
```

**No build process required** - this is a static HTML/CSS/JS website.

## Content Guidelines

**Language:** All user-facing content should be in English

**Assessment Case Structure:**
Each assessment case follows the same template with sections:
- Hero with company stats
- Customer overview (4-card grid)
- Key features (5 feature cards)
- Technical specifications (2-card layout)
- Assessment challenges (4-card grid)
- Assessment questions section with specific tasks

**Navigation:**
- Homepage serves as assessment portal
- Case pages have "Back to Assessment" button
- All three cases are now fully accessible

**Training Context:**
- Designed for Acceleronix All Hands - APAC Bangkok, August 2025
- Tests 4-day training on IoT and Connectivity platforms
- Focus on BD and sales team evaluation
- Real customer scenarios requiring platform knowledge application

**Consistency Requirements:**
- Maintain the same visual hierarchy across all pages
- Use consistent terminology for technical concepts
- Keep the same card layouts and spacing
- Ensure responsive behavior on all pages

## File Structure Notes

- CSS files are separated by purpose (home vs case pages)
- All case study pages share the same CSS file for consistency
- Images/icons use emoji for simplicity (no external assets)
- Vercel.json provides deployment configuration and routing