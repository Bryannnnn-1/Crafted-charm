# Crafted Charm Website Documentation

Crafted Charm is an artisan e-commerce website offering handmade pottery, paintings, jewelry, 
and other creative works. This static site showcases products, tells the brand story, and allows users to browse categories, view a featured project, and navigate to cart/login pages.

**Pages and Structure**

# 1. "index.html" (Home Page)
- Main landing page with:
  - Brand intro
  - Embedded video (YouTube iframe)
  - Product categories
  - Featured project
  - Customer testimonials
  - Footer with contact & social info

# 2. Linked Pages
- `/pages/cart.html`
- `/pages/login.html`
- `/pages/paintings.html`
- `/pages/pottery.html`
- `/pages/jewellery.html`
- `/pages/page404.html` (placeholder or "Our Story" page)

# Technologies Used
- **HTML5** – Semantic structure
- **CSS** – Custom styles via `styles/home-page.css`
- **Google Fonts** – Material Symbols for icons
- **External Media** – YouTube embedded video
- **Images** – Local assets (`/images/`)



# Overview

**Styling and Appearance**
The Crafted Charm website uses modern CSS techniques to create an elegant, artisanal, and visually appealing user experience. 
One of the defining visual features of the design is the frosted glass effect, which gives the site a soft, sophisticated 
look while maintaining readability and focus on content.

**Frosted Glass Effect (Backdrop Blur)**
The website extensively uses a glass styling through the CSS property backdrop-filter: blur(...) combined with 
semi-transparent backgrounds (rgba colors with partial opacity).
This effect creates a frosted glass look, where backgrounds appear blurred behind translucent containers, 
lending depth and layering to the design without heavy shadows or solid blocks.

# Fonts
- Custom font-face defined for 'Cormorant Garamond' but the main font
used throughout is "PlayfairDisplay-Regular", a serif font that lends an artistic and classical look.
- The font is loaded from local /fonts/ directory with .woff and .woff2 formats for optimized performance.

# Color Palette
- Primary color: A translucent white (rgba(255, 255, 255, 0.521)) used for backgrounds to create a soft frosted glass effect.
- Secondary color: Rich red (#cf0808) used for highlights, buttons, navigation hover states, and accents.
- Text color: Pure black (#000000) for strong contrast and readability.


**Layout and Structure**
The site uses a flexible layout with the header fixed at the top and content padding adjusted to avoid overlap.
The header includes a logo, search bar, cart icon with dynamic count badge, and user profile icon arranged with Flexbox.
Navigation bar with evenly spaced category links, styled with rounded corners and subtle backdrop blur.
Sections such as introduction, video, categories, featured items, testimonials, and footer use generous padding and centered content.
Background image is fixed and covers the entire viewport for visual interest.


**Responsiveness**
Media queries target screen widths under 768px, adjusting flex direction, padding, font sizes, and grid layouts.

