# NrityaKala

NrityaKala is a static website dedicated to Indian classical dance heritage. It presents a visually rich landing page, individual pages for major classical dance forms, and supporting gallery, events, and about sections.

## Overview

The site is built with plain HTML, CSS, and JavaScript, with Bootstrap and Bootstrap Icons loaded from CDN. It is designed as a multi-page experience focused on storytelling, cultural context, and dance-form discovery.

## Pages

- `index.html`: Homepage and main entry point
- `bharatanatyam.html`: Bharatanatyam overview
- `kathak.html`: Kathak overview
- `kathakali.html`: Kathakali overview
- `kuchipudi.html`: Kuchipudi overview
- `manipuri.html`: Manipuri overview
- `mohiniyattam.html`: Mohiniyattam overview
- `odissi.html`: Odissi overview
- `sattriya.html`: Sattriya overview
- `gallery.html`: Image gallery page
- `events.html`: Events page
- `about.html`: About page

## Project Structure

```text
.
|-- about.html
|-- animations.js
|-- bharatanatyam.html
|-- events.html
|-- gallery.html
|-- images/
|-- index.html
|-- kathak.html
|-- kathakali.html
|-- kuchipudi.html
|-- manipuri.html
|-- mohiniyattam.html
|-- odissi.html
|-- sattriya.html
`-- styles.css
```

## Tech Stack

- HTML5
- CSS3
- JavaScript
- Bootstrap 5
- Bootstrap Icons
- Google Fonts

## Run Locally

Because this is a static site, no build step is required.

1. Open `index.html` directly in a browser, or
2. Serve the folder with a local static server for better navigation behavior

Example with VS Code Live Server or any static file server:

```bash
# Python
python -m http.server 8000

# Node.js
npx serve .
```

Then open `http://localhost:8000`.

## Features

- Responsive multi-page layout
- Dedicated pages for major Indian classical dance forms
- Animated homepage sections and carousel behavior
- Shared visual styling through `styles.css`
- Image-driven presentation with cultural storytelling content

## Notes

- External assets such as Bootstrap, icons, fonts, and some images are loaded from CDN or remote URLs.
- Local media assets are stored in the `images/` directory.

## Future Improvements

- Add a consistent navigation/footer partial strategy to reduce duplication across pages
- Optimize image sizes and formats for faster page loads
- Replace inline page-specific styles with shared component styles
- Add deployment instructions for GitHub Pages or Netlify
  
