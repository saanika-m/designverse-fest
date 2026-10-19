DesignVerse 2026 Website

An interactive, responsive landing page for DesignVerse 2026—a two-day Student Design & Innovation Fest hosted at IGDTUW Campus, New Delhi.

The website showcases festival highlights, schedule timelines, detailed event catalogs, and modal-driven event registration portals.


🎨 Theme & Styling

The site is built with Tailwind CSS using a custom dark theme palette:

Primary Background (navyBg): #0B132B

Card Container (navyCard): #1C2541

Borders / Accents (navyLight): #3A506B

Primary Text (iceBlue): #E0FBFC

CTA Highlights (amberAccent): #FF9F1C

Secondary Accent (yellowAccent): #FFD166


🚀 Key Features

Split-Screen Hero Layout: Side-by-side presentation highlighting event dates, venue details, and primary call-to-actions.

Interactive Slide-Out Drawer: Mobile-friendly navigation menu toggled via JavaScript.

Chronological Timeline: Vertical schedule listing two-day fest activities.

In-Depth Event Catalog: Includes collapsible <details> accordions providing deeper insights into guest speakers, workshop materials, and competition tracks.

Participation Hub Modal: Quick selection modal directing visitors to Google Forms for:

Fluid Art Workshop Registration

4-Hour Design-a-Thon Registration

Creator & Food Stall Booking


📁 File Structure & Assets Required

To ensure proper rendering of local images, make sure the following static assets are placed in the root directory alongside index.html:

.
├── index.html         # Main source HTML file
├── logo.jpeg          # Custom DesignVerse event logo
├── goodies.jpeg       # Image for The Bazaar Marketplace section
└── README.md          # Documentation file


🛠️ Usage & Local Setup

Clone or Download the project repository.

Ensure logo.jpeg and goodies.jpeg exist in the root folder alongside index.html.

Open index.html in any web browser (or use Live Server in VS Code).

Note: The project utilizes Tailwind CSS via CDN (https://cdn.tailwindcss.com), requiring an active internet connection to render styled components.
