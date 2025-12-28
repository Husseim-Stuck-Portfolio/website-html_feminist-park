# website-html_feminist-park www.feminist-park.org with the assistance of AI
Explore feminist history through code. Responsive HTML/CSS/JS website celebrating women &amp; public spaces. Built with semantic HTML5, accessible design principles, CSS Grid/Flexbox &amp; mobile-first methodology. Portfolio project demonstrating web fundamentals + purpose-driven development.

##Feminist Park - Technical Breakdown
**Live**: [www.feminist-park.org](https://www.feminist-park.org) | **Tech**: Tailwind CSS • GTM Analytics • Dynamic SVG • JS SPA

**Key Features**:
  - **Knockout Text + SVG Backdrops**: Theme-adaptive geometric park visuals
  - **Responsive SPA**: 12+ pages, 0.8s transitions, mobile-first Tailwind
  - **Custom CSS Vars**: Pink/blue/orange feminist color system
  - **Google Tag Manager**: Event tracking for activism KPIs
<img width="700" height="392" alt="Screenshot 2025-12-28 at 20 43 51" src="https://github.com/user-attachments/assets/fd9cc81e-a389-41c0-9997-48b90fb21841" />  

**Clean Export**: Google Sites → HTML with zero bloat. Ready for GitHub Pages migration.
[Source Code](https://github.com/Husseim-Stuck-Portfolio/website-html_feminist-park/blob/main/html_code) | [Demo](https://github.com/Husseim-Stuck-Portfolio/website-html_feminist-park/blob/main/README.md)

**Project Overview**
Feminist Park is a responsive, interactive website that serves as a digital monument to women's contributions to public spaces, civic life, and community building throughout history. This project reimagines the concept of a "park" as both a physical sanctuary and a digital space for reflection, education, and celebration of feminist history.
The website explores the intersection of urban planning, social justice, and women's history by highlighting how feminist activists, architects, urban planners, and community organizers have shaped the public spaces we inhabit today—often against significant resistance and erasure from historical narratives.

**Project Purpose & Mission**
Why a Feminist Park?
Public spaces have historically been designed by and for men, often excluding or limiting women's access, safety, and participation. From parks that lacked adequate lighting for evening safety, to the absence of public restrooms, to hostile architecture that discourages mothers with children—urban design has reflected and reinforced gender inequalities.

This digital park serves multiple purposes:

-Historical Recognition: Documenting women who fought for equitable public spaces
-Educational Resource: Teaching visitors about feminist urban planning and design principles
-Digital Accessibility: Creating an inclusive online space that models the accessibility often missing from physical parks
-Inspiration: Showcasing how intentional design can create safer, more inclusive communities
-Call to Action: Encouraging visitors to advocate for better public spaces in their own communities through a survey

**About the Website**
The HTML code for feminist-park.org is a sophisticated single-page application (SPA) built with Tailwind CSS, Google Tag Manager, Lucide icons, and dynamic JavaScript for smooth page transitions. It exports cleanly from Google Sites while adding modern frontend techniques like CSS custom properties, knockout text effects, and theme-adaptive SVG backdrops

**Code Architecture**
Modern SPA structure with semantic HTML5: sticky header, dynamic main content (#page-container), fixed SVG backdrop (#park-backdrop-container), and responsive footer. JavaScript-driven navigation renders 12+ pages (Home, Podcast, Survey, Team) from PAGEDATA JSON array without page reloads—using renderContent(pageName) with 0.8s opacity transitions. Mobile-first with Tailwind classes (md:grid-cols-2, lg:px-8).
​
**Technical Highlights**
CSS Custom Properties: Root variables (--color-primary: #1D2F6F, --color-accent-pink: #FF1053) enable themeable dark blue/pink/orange palette. Knockout text effect (background-clip: text; -webkit-text-fill-color: transparent) reveals dynamic SVG backgrounds through headings. Dynamic SVG Backdrops: createParkSVG(theme) generates geometric park scenes (polygons for paths/grass, theme-specific details like swings/ponds) that morph per page (e.g., orange figures for "survey"). Z-index layering creates parallax depth. Analytics Integration: Google Tag Manager loads asynchronously for GA4 event tracking (button clicks, page views)—perfect for your KPI dashboards. Performance Optimizations: CDN-loaded Tailwind (https://cdn.tailwindcss.com), Lucide icons (unpkg.com/lucide), Font Awesome. Lazy-loaded Spotify embeds. Smooth hovers (transform: scale(1.15) on social icons).
