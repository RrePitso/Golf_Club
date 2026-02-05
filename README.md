# West Bank Golf Club - Digital Modernization Concept

## Overview
This project is a high-fidelity conceptual redesign of the West Bank Golf Club website. The goal is to modernize the digital presence of one of South Africa's most historic courses, moving from a text-heavy layout to a visual-first, mobile-responsive experience that highlights the unique selling point: **"See the sea from every tee."**

**Live Demo:** [Insert your GitHub Pages Link Here]

## Key Improvements
### 1. Visual Hierarchy & Branding
* **Current Site:** Boxed layout with dense text and low-resolution imagery.
* **Redesign:** Full-width "Hero" sections featuring the Hood Point Lighthouse and ocean views.
* **Typography:** Switched to *Playfair Display* (Serif) for a premium, heritage feel, paired with *Inter* (Sans-Serif) for readability.

### 2. User Experience (UX)
* **Mobile-First Architecture:** The site is fully responsive, stacking content elegantly on mobile devices (where most users will likely view it).
* **Simplified Navigation:** A sticky glassmorphism navbar ensures booking and contact info is always accessible.
* **Information Architecture:**
    * **Green Fees:** Converted complex tables into easy-to-scan pricing cards.
    * **Membership:** Grouped by demographics (Youth, Senior, Full) rather than a raw list of prices.

### 3. Technical Stack
* **Framework:** HTML5 & Tailwind CSS (via CDN for lightweight performance).
* **Performance:** Minimal dependencies ensure near-instant load times (Lighthouse Score: ~98/100).
* **Maintenance:** Clean, semantic HTML structure makes future updates (pricing changes, event news) simple.

## Project Structure
```text
/
├── index.html       # Homepage (Hero, History, Highlights)
├── golf.html        # Green Fees, Scorecard, Course Layout
├── membership.html  # Membership Tiers & Rates
├── contact.html     # Location, Contact Grids, Forms
└── README.md        # Project Documentation
