# Vivek Singh - Personal Portfolio

A modern, responsive personal portfolio website for Vivek Singh, an AI and Machine Learning enthusiast.

## Project Structure

```
portfolio/
├── index.html               # Main HTML file
├── css/
│   └── style.css            # Main stylesheet
├── js/
│   └── main.js              # JavaScript functionality
├── assets/
│   ├── profile.jpg          # Profile image
│   ├── favicon.svg          # Vector favicon
│   └── favicon.png          # Bitmap favicon
└── README.md                # This documentation
```

## Features

- Responsive design that works on mobile, tablet, and desktop
- Clean, minimal interface focused on content
- Smooth scrolling navigation
- Mobile-friendly navigation menu
- "Back to top" button for easy navigation
- Organized sections for about, skills, projects, education, and contact info

## Technology Stack

- HTML5
- CSS3 (with CSS Variables)
- JavaScript (Vanilla JS)
- Font Awesome for icons

## How to Modify

### General Content

Edit the `index.html` file to update the content of your portfolio. The HTML is organized into clear sections that correspond to each part of the portfolio.

### Styling

All styles are contained in `css/style.css`. The file uses CSS variables (in the `:root` selector) for easy theming:

```css
:root {
  --bg-color: #0f172a;      /* Background color */
  --text-color: #e2e8f0;    /* Main text color */
  --accent-color: #3b82f6;  /* Accent color for highlights */
  --muted-color: #64748b;   /* Subdued text color */
  --border-color: #1e293b;  /* Border color */
  --card-bg: #1e293b;       /* Card background color */
  --transition: all 0.3s ease; /* Standard transition */
}
```

Change these variables to update the color scheme across the entire site.

### JavaScript Functionality

The `js/main.js` file contains all interactive elements:

- Mobile menu toggle
- Smooth scrolling for navigation links
- Back to top button behavior

### Assets

- Replace `assets/profile.jpg` with your own profile photo
- Update favicons as needed (both SVG and PNG versions for maximum compatibility)

## Development

To make changes to this portfolio:

1. Clone the repository
2. Make your desired edits to HTML, CSS, or JS files
3. Test locally by opening `index.html` in a browser
4. Deploy to your hosting service

## Deployment

This site can be deployed on any static web hosting service, including:

- GitHub Pages
- Netlify
- Vercel
- Amazon S3
- Any traditional web hosting

No build process is required since this is a static site with no dependencies.

## Browser Compatibility

This portfolio is designed to work on all modern browsers:

- Chrome
- Firefox
- Safari
- Edge

## License

This project is open source and available for personal use. 