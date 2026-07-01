# The Tea House

A premium landing page for **The Tea House**, a retail supplier of high-quality tea and botanical solutions. This website showcases featured tea products, customer feedback, news, and subscription services, built with a modern design and clean utility classes.

## Live Demo
Check out the live website here:
🔗 **[Live Demo Link]([https://your-live-demo-link.com](https://my-tea-house-bd.netlify.app/))**

## About / Purpose
The Tea House landing page is designed to attract customers and present a luxurious yet minimalist brand image for a boutique tea provider. It functions as a complete responsive showcase featuring:
- A dynamic banner with ratings and call-to-actions.
- A featured products grid showcasing Milk, Black, Lemon, and Green tea.
- A brand values section highlighting premium quality and unique taste.
- A "Super Clients" testimonial section with stacked, overlapping cards.
- A "News & Events" blog-style layout to share updates.
- A multi-column footer with quick links, service listings, social handles, and a newsletter sign-up form.

## Learning Goals
This project was built to master the following frontend development practices:
- **Semantic Markup**: Structuring the document with standard HTML5 elements (`<header>`, `<main>`, `<section>`, `<footer>`).
- **Utility-First Styling**: Utilizing Tailwind CSS to rapidly style layouts and UI components directly within markup.
- **Responsive Layout Design**: Crafting responsive components using Tailwind's breakpoint prefixes (`sm:`, `md:`, etc.) that render beautifully on mobile devices, tablets, and desktops.
- **Complex Layouts & Stacking**: Using relative positioning, absolute positioning, translate transforms, and custom grid spanning to achieve overlay effects (like client badges and overlapping testimonial cards).
- **External Asset Integration**: Importing custom Google Fonts (`Manrope`) and Font Awesome icon sets, and linking stylesheet files.

## Folder Structure
```
tea-house/
├── css/
│   └── styles.css              # Custom styling (imports Google Fonts and defines font families)
├── tea-house-resources/
│   ├── images/                 # Image assets (cup, banner, products, news, clients, etc.)
│   └── tea-house.fig           # Original Figma design mockup file
├── index.html                  # Main webpage containing the landing page structure
├── tailwind.config.js          # Tailwind configuration file (empty by default)
└── README.md                   # Project documentation
```

## How to Run
This is a static HTML/CSS web application that does not require any build tools or complex compilation. You can run it locally in any of the following ways:

### Method 1: Direct Execution
1. Navigate to the project folder.
2. Double-click `index.html` to open it directly in your default web browser.

### Method 2: Live Server (Recommended)
If you are using **VS Code**:
1. Install the **Live Server** extension by Ritwick Dey.
2. Open the project folder in VS Code.
3. Right-click on `index.html` and select **Open with Live Server**.
4. The page will open on a local host (default: `http://127.0.0.1:5500/index.html`) with live-reload enabled.

### Method 3: Static Server via CLI
You can launch a simple local HTTP server from your terminal inside the project root directory:
- **Node.js (npx)**:
  ```bash
  npx serve .
  ```
- **Python 3**:
  ```bash
  python -m http.server 8000
  ```
  Open `http://localhost:8000` in your web browser.

## Technologies Used
* **HTML5**: Semantic tags for modern, accessible web architecture.
* **Tailwind CSS v4 (browser script CDN)**: Fast utility-first styling.
* **Google Fonts (Manrope)**: Tailored typography.
* **Font Awesome v7 (CDN)**: High-quality icons for UI enrichment.
* **CSS3 Custom Rules**: Custom font imports and helpers.

## Topics Covered
* **Tailwind Utility CSS**: Fluid spacing (margins/padding), colors, text sizing, border radius, and flexbox/grid layout systems.
* **Overlapping UI Positioning**: Absolute positioning and translate offsets to overlay components seamlessly.
* **Responsive Breakpoints**: Designing components that scale smoothly across mobile, tablet, and desktop layouts.
* **Figma to Code Implementation**: Translating a complete design file (`.fig`) into a responsive web layout.
* **Interactive Element Styling**: Styling buttons with gradient hover effects, input elements with bottom borders, and transitions.
