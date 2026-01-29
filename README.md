# Poopy Scoopy 🐕💩

Milwaukee's #1 Dog Waste Removal Service website.

## Overview

A professional, responsive website for Poopy Scoopy - a dog poop removal service serving the greater Milwaukee, Wisconsin area.

## Features

- **Responsive Design**: Looks great on desktop, tablet, and mobile
- **Modern UI**: Clean, professional design with baby blue brand colors
- **Fast Loading**: Optimized images and minimal dependencies
- **SEO Ready**: Semantic HTML with proper meta tags
- **Interactive Elements**: FAQ accordion, smooth scrolling, form validation
- **Cloud Run Ready**: Dockerized for easy deployment to Google Cloud Run

## Tech Stack

- HTML5
- CSS3 (Custom properties, Flexbox, Grid)
- Vanilla JavaScript
- Nginx (for serving)
- Docker (for deployment)

## Local Development

### Option 1: Open directly
Simply open `index.html` in your browser.

### Option 2: Use a local server
```bash
# Python
python -m http.server 8080

# Node.js (if you have npx)
npx serve
```

### Option 3: Docker
```bash
docker build -t poopy-scoopy .
docker run -p 8080:8080 poopy-scoopy
```

Then visit http://localhost:8080

## Deployment

This site is configured for Google Cloud Run deployment.

1. Push to GitHub repository
2. Cloud Build automatically builds the Docker image
3. Cloud Run deploys the new version

## File Structure

```
├── index.html          # Main HTML file
├── styles.css          # All styles
├── script.js           # JavaScript functionality
├── Dockerfile          # Docker configuration
├── nginx.conf          # Nginx server configuration
├── images/             # Image assets
│   ├── logo.png
│   ├── hero-truck.png
│   ├── worker-yard.png
│   ├── worker-equipment.png
│   ├── worker-dogs.png
│   └── office.png
└── README.md           # This file
```

## Brand Colors

- Primary Blue: `#38b6ff`
- Primary Dark: `#2196d4`
- Primary Light: `#7dcfff`

## Contact

For questions about this website, contact the Poopy Scoopy team.

---

*We scoop so you don't have to!* 🐾
