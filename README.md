# Metaltela Parque Industrial

A static website for Metaltela Ltda., a Santa Cruz, Bolivia-based company specializing in manufacturing meshes, screens (zarandas), and expanded metal sheets. This project is designed for simplicity, performance, and easy deployment using GitHub Pages.

## Badges

[![Static Website](https://img.shields.io/badge/Website-Static-green.svg)](https://github.com)
[![GitHub Pages](https://img.shields.io/badge/Deploy-GitHub%20Pages-blue.svg)](https://pages.github.com/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

## Installation

Since this is a static website, no build process is required. Simply clone the repository and open `index.html` in your browser:

```bash
  git clone https://github.com/your-username/metaltela-parque-industrial_gh.git
  cd metaltela-parque-industrial_gh
```

Then open `index.html` in your web browser, or serve it using a local web server:

```bash
  # Using Python
  python -m http.server 8000
  
  # Using Node.js (if you have http-server installed)
  npx http-server
```

## Deployment

This project is configured for automatic deployment to GitHub Pages using GitHub Actions.

### Setting up GitHub Pages

1. **Enable GitHub Pages in repository settings:**
   - Go to your repository on GitHub
   - Navigate to **Settings** → **Pages**
   - Under **Source**, select **"GitHub Actions"** (not "Deploy from a branch")
   - Save the settings

2. **Push your code:**
   - The workflow will automatically trigger on push to `main` or `master` branch
   - You can also manually trigger it from the **Actions** tab → **Deploy to GitHub Pages** → **Run workflow**

3. **Check deployment status:**
   - Go to the **Actions** tab to see the workflow status
   - Once successful, your site will be available at:
     - `https://[your-username].github.io/metaltela-parque-industrial_gh/`
     - Or `https://[your-org].github.io/metaltela-parque-industrial_gh/` if it's an organization repository

4. **Troubleshooting:**
   - Ensure GitHub Pages is set to use **"GitHub Actions"** as the source (not a branch)
   - Check the Actions tab for any workflow errors
   - Wait a few minutes after the workflow completes for DNS propagation
   - Clear your browser cache if you see a 404 error

## Appendix

### Technology Stack

- **HTML5** - Semantic markup and structure
- **Tailwind CSS** (CDN) - Utility-first CSS framework for styling
- **JavaScript (Vanilla)** - Client-side interactivity and functionality
- **Bootstrap 5** - Additional UI components and utilities
- **Bootstrap Icons** - Icon library
- **Flowbite** - Component library built on top of Tailwind CSS
- **Popper.js** - Tooltip and popover positioning
- **js-cookie** - Cookie handling utility
- **Lodash.js** - JavaScript utility library
- **browser-image-compression** - Client-side image compression
- **Swiper.js** - Touch slider and carousel library
- **Dunosis Analytics** - Web analytics tracking
- **Google Analytics** - Web analytics tracking (optional)
- **GitHub Pages** - Static site hosting and deployment

### Project Structure

```
metaltela-parque-industrial_gh/
├── assets/
│   ├── catalog/
│   │   └── metaltela-catalogo.pdf    # Product catalog PDF
│   ├── fonts/
│   │   └── [Futura font files]      # Custom Futura font family
│   ├── images/
│   │   ├── home/                     # Home page images and photos
│   │   │   ├── mt-home-tienda.jpg
│   │   │   ├── mt-products-*.jpg
│   │   │   └── whatsapp-icon.png
│   │   ├── logos/                    # Brand logos and favicons
│   │   │   └── metaltela-logo.png
│   │   ├── 404.png                   # 404 error page image
│   │   └── ratelimiter-doggy.png
│   └── json/
│       └── phone-codes.json          # Phone code data
├── css/
│   ├── blog.css                      # Blog page specific styles
│   ├── index.css                     # Home page specific styles
│   └── styles.css                    # Global styles
├── js/
│   ├── apis/
│   │   └── blog.js                   # Blog API integration
│   ├── inquiry/
│   │   └── inquiry.js                # Contact/order form handling
│   ├── utils/
│   │   ├── common.js                 # Common utility functions
│   │   ├── constants.js              # Application constants
│   │   ├── elements.js               # DOM element utilities
│   │   └── images.js                 # Image handling utilities
│   ├── base.js                       # Base application logic
│   ├── home.js                       # Home page specific scripts
│   └── trix.js                       # Trix editor integration
├── index.html                        # Main homepage
└── README.md                         # Project documentation
```

## Authors

- [@dunosis](https://www.dunosis.com) - Made by Dunosis

