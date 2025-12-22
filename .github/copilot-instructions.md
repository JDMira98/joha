# Copilot Instructions for Joha Repository

## Repository Overview

This is a personal repository containing a romantic web page dedicated to Johana. It's a single-page HTML application with animated hearts, a photo gallery, and interactive elements.

## Project Structure

- `index.html` - Main HTML file containing all structure, styles, and JavaScript
- `*.jpeg` - WhatsApp images used in the photo gallery
- `README.md` - Simple repository description

## Code Conventions

### HTML/CSS/JavaScript

- **Single-file architecture**: All HTML, CSS, and JavaScript are contained in `index.html` for simplicity
- **Inline styles**: CSS is embedded in a `<style>` tag in the HTML head
- **Inline scripts**: JavaScript is embedded in a `<script>` tag at the end of the body
- **Minified/compact code**: CSS and JavaScript use compact formatting to reduce file size
- **Spanish language**: All user-facing text is in Spanish
- **No external dependencies**: No frameworks or libraries - pure vanilla HTML/CSS/JS

### Styling Approach

- **CSS Custom Properties**: Color scheme defined in `:root` variables
- **Responsive design**: Uses `clamp()` for fluid typography and viewport-based sizing
- **Modern CSS**: Flexbox and Grid for layouts
- **Animations**: CSS animations for heart pulse effect and JavaScript for floating hearts
- **Glass-morphism**: Backdrop blur effects for modern UI aesthetic

### JavaScript Patterns

- **Vanilla JavaScript**: No jQuery or frameworks
- **Event handlers**: Direct DOM manipulation and event listener assignment
- **Animation timing**: Uses `setInterval` and `animate()` API for visual effects
- **ES6 features**: Arrow functions, template literals, and modern syntax

## Key Features to Maintain

1. **Animated heart pulse** - CSS animation on the main heart
2. **Floating hearts** - JavaScript-generated SVG hearts that float up and fade
3. **Photo gallery** - Grid layout with hover effects
4. **Lightbox** - Click to view full-size images with navigation
5. **Share functionality** - Uses Web Share API with fallback
6. **Interactive buttons**:
   - "Enviar" - Triggers burst of floating hearts
   - "Repetir" - Animates the main heart
   - "Compartir" - Shares the page

## Image Management

- Images are WhatsApp exports with dates in filenames
- Gallery images should maintain the current naming pattern
- When adding images, update both the gallery grid and lightbox functionality
- Keep image alt text descriptive in Spanish

## Language and Content

- **Primary language**: Spanish (es)
- **Tone**: Romantic and affectionate
- **Content focus**: Love expressions and shared memories

## Making Changes

- Keep the single-file structure unless there's a compelling reason to separate concerns
- Maintain backward compatibility with the existing features
- Test all interactive elements (buttons, lightbox, animations) after changes
- Ensure responsive behavior works on mobile and desktop
- Preserve the romantic theme and visual aesthetic

## Testing Approach

Since this is a simple static page:
- Open `index.html` in a browser to verify changes
- Test all buttons and interactive features manually
- Check responsive behavior at different screen sizes
- Verify animations and transitions work smoothly
- Test lightbox navigation with all gallery images

## Deployment

This is a static HTML page that can be:
- Opened directly in a browser
- Served via GitHub Pages
- Hosted on any static web hosting service

No build process or compilation required.
