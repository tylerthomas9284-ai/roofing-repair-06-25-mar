# TopShield Roofing - HTML/CSS/JS Conversion

## Completed Files

### Core Files
1. **`/public/styles.css`** - Complete CSS stylesheet with all styling
2. **`/public/scripts.js`** - All JavaScript functionality including:
   - Mobile menu toggle
   - FAQ accordion
   - Contact form handling
   - Active nav link highlighting
   - Smooth scrolling

3. **`/public/index.html`** - Home page (COMPLETE)

## Additional HTML Pages to Create

All pages follow the same structure with these sections:
- Header (with top bar, navigation, mobile menu)
- Main content (unique to each page)
- Footer (company info, links, contact, legal links)
- Mobile call button

### Common Header HTML (use in all pages)
```html
<header>
  <div class="top-bar">
    <div class="container">
      <div class="top-bar-left">Licensed & Insured | 24/7 Emergency Service</div>
      <a href="tel:215-594-5828" class="top-bar-right">
        <svg class="icon-sm" viewBox="0 0 24 24"><path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6 19.79 19.79 0 0 1-3.07-8.67A2 2 0 0 1 4.11 2h3a2 2 0 0 1 2 1.72 12.84 12.84 0 0 0 .7 2.81 2 2 0 0 1-.45 2.11L8.09 9.91a16 16 0 0 0 6 6l1.27-1.27a2 2 0 0 1 2.11-.45 12.84 12.84 0 0 0 2.81.7A2 2 0 0 1 22 16.92z"></path></svg>
        <span>215-594-5828</span>
      </a>
    </div>
  </div>
  <div class="main-nav">
    <div class="container">
      <a href="index.html" class="logo">TopShield Roofing</a>
      <nav class="desktop-nav">
        <a href="index.html" class="nav-link">Home</a>
        <a href="about.html" class="nav-link">About Us</a>
        <a href="services.html" class="nav-link">Services</a>
        <a href="faq.html" class="nav-link">FAQ</a>
        <a href="contact.html" class="nav-link">Contact</a>
        <a href="tel:215-594-5828" class="cta-button">Get Free Estimate</a>
      </nav>
      <button id="mobile-menu-button" class="mobile-menu-button">
        <svg id="menu-icon" class="icon-lg" viewBox="0 0 24 24"><line x1="3" y1="12" x2="21" y2="12"></line><line x1="3" y1="6" x2="21" y2="6"></line><line x1="3" y1="18" x2="21" y2="18"></line></svg>
        <svg id="close-icon" class="icon-lg" style="display: none;" viewBox="0 0 24 24"><line x1="18" y1="6" x2="6" y2="18"></line><line x1="6" y1="6" x2="18" y2="18"></line></svg>
      </button>
    </div>
  </div>
  <div id="mobile-menu" class="mobile-menu">
    <nav>
      <a href="index.html" class="nav-link">Home</a>
      <a href="about.html" class="nav-link">About Us</a>
      <a href="services.html" class="nav-link">Services</a>
      <a href="faq.html" class="nav-link">FAQ</a>
      <a href="contact.html" class="nav-link">Contact</a>
      <a href="tel:215-594-5828" class="cta-button">Get Free Estimate</a>
    </nav>
  </div>
</header>
```

### Common Footer HTML (use in all pages)
[See index.html for complete footer code]

## File List

Create these HTML files in `/public/`:
1. ✅ index.html (Complete)
2. about.html
3. services.html
4. contact.html
5. faq.html
6. terms.html
7. privacy.html
8. disclaimer.html
9. cookie-policy.html

## Instructions

Each HTML file should:
1. Include DOCTYPE, html, head, and body tags
2. Link to `styles.css` in the head
3. Include proper meta tags and title
4. Use the common header structure
5. Include unique main content
6. Use the common footer structure
7. Include mobile call button
8. Link to `scripts.js` before closing body tag

## Quick Start Template

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="[PAGE DESCRIPTION]">
  <title>[PAGE TITLE] - TopShield Roofing</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <!-- Header (see common header above) -->
  
  <!-- Main Content -->
  <main>
    <!-- Page-specific content here -->
  </main>
  
  <!-- Footer (see common footer in index.html) -->
  
  <!-- Mobile Call Button -->
  <a href="tel:215-594-5828" class="mobile-call-button">
    <svg class="icon-lg" viewBox="0 0 24 24"><path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6 19.79 19.79 0 0 1-3.07-8.67A2 2 0 0 1 4.11 2h3a2 2 0 0 1 2 1.72 12.84 12.84 0 0 0 .7 2.81 2 2 0 0 1-.45 2.11L8.09 9.91a16 16 0 0 0 6 6l1.27-1.27a2 2 0 0 1 2.11-.45 12.84 12.84 0 0 0 2.81.7A2 2 0 0 1 22 16.92z"></path></svg>
  </a>
  
  <script src="scripts.js"></script>
</body>
</html>
```

## Testing

To test locally:
1. Open any HTML file in a web browser
2. Test navigation between pages
3. Test mobile menu on small screens
4. Test contact form submission
5. Test FAQ accordion on FAQ page
6. Verify all links work properly

## Deployment

All files in `/public/` directory are ready for deployment to any web server. Simply upload the entire `/public/` folder contents to your web hosting.

## Browser Support

- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile responsive
- No JavaScript frameworks required
- Pure HTML, CSS, and vanilla JavaScript
