# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a training assessment platform for Acceleronix's Bangkok All Hands meeting (August 2025). The site presents three customer case studies designed to test BD and sales team knowledge of Acceleronix IoT and Connectivity platforms after a 4-day training program.

## Architecture

**Multi-page Static Website Structure:**
- `index.html` - Homepage with case study overview and navigation
- `assets/css/home.css` - Homepage-specific styling
- `assets/css/styles.css` - Shared styling for case study pages
- `assets/css/greenride-theme.css` - Green/gold theme for GreenRide Vietnam case
- `assets/css/solarpulse-theme.css` - Green/orange theme for SolarPulse India case
- `assets/images/` - Banner images for case studies (Cold-Chain.jpg, two_wheeler.jpg, powerstation.png)
- `cases/` directory containing individual case study pages

**Assessment Cases:**
1. **AccelTech** - Cold chain logistics tracking in Malaysia (Case A)
2. **GreenRide Vietnam** - Smart e-bike IoT solutions in Vietnam (Case B)  
3. **SolarPulse India** - Mobile solar energy storage solutions in India (Case C)

**Design System:**
- Base color scheme: Purple gradient (#667eea to #764ba2) with neutral backgrounds
- Case-specific themes:
  - **AccelTech**: Purple/blue gradient (maintains base theme)
  - **GreenRide Vietnam**: Green/gold gradient (#4CAF50 to #FF9800) - environmental theme
  - **SolarPulse India**: Orange/green gradient (#FF9933 to #138808) - India flag colors
- Typography: Inter font family with consistent weight hierarchy
- Layout: CSS Grid for card layouts, Flexbox for navigation and stats
- Responsive: Mobile-first approach with breakpoints at 768px and 480px
- Interactive elements: Hover effects, smooth scrolling, click handlers, hero banner images

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

- CSS files are separated by purpose (home vs case pages vs themes)
- Base `styles.css` provides consistent foundation across all case pages
- Theme-specific CSS files override colors and styling for branding alignment
- Hero banner images stored in `assets/images/` for visual impact
- Vercel.json provides deployment configuration and routing (fixed for modern Vercel)

## Case Study Details

**Case A - AccelTech (Malaysia):**
- Cold chain logistics and tracking solution
- NB-IoT connectivity focus
- Quectel module information hidden for assessment purposes
- Features: Temperature monitoring, trajectory playback, OTA updates
- Assessment: IoT platform architecture, connectivity optimization, fleet management

**Case B - GreenRide Vietnam:**
- Smart electric bike with IoT integration
- Founded 2019, supporting Vietnam's Green City initiative
- Products: Smart e-Bike 500X (120km range, 40km/h, 7" touchscreen)
- Pricing: 60M VND base ($2,400), 250k VND/month subscription ($10)
- Features: WiFi/BLE connectivity, OTA updates, anti-theft, charging network
- Assessment: Sustainable mobility IoT, battery management, market expansion

**Case C - SolarPulse India:**
- Mobile solar energy storage solutions
- Founded 2020 Bangalore, supporting National Solar Mission 2030
- Products: PowerHub 1-5kWh capacity, LFP battery, 2000+ cycles
- Pricing: INR 45,000 base ($570), INR 500/month subscription ($6)
- Features: Solar optimization, grid feed-in control, WiFi/BLE app integration
- Assessment: Solar IoT architecture, climate adaptation, subscription services

## Security Notes

- AccelTech case has sanitized technical specifications (no specific module details)
- All cases use realistic but non-sensitive company and pricing information
- Assessment questions focus on platform capabilities rather than proprietary solutions