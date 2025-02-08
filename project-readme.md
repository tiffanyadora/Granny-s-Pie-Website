# Granny's Pies Website

A responsive website for Granny's Pies featuring a homepage with the company story, featured recipes, and a detailed recipe page for their famous Lemon Meringue Pie.

## Project Structure

```
grannys-pies/
├── index.html
├── index.css
├── pie.html
├── recipe.css
└── assets/
    ├── grandma-rose.jpg
    ├── lemon-meringue-pie.jpg
    ├── classic-apple-pie.jpg
    └── southern-pecan-pie.jpg
```

## Features

- Responsive design that works on desktop and mobile devices
- Dark mode support through CSS media queries
- Accessible design with proper heading hierarchy and descriptive alt text
- Clean, traditional aesthetic that matches the brand
- Detailed recipe page with ingredients and step-by-step instructions

## Setup Instructions

1. Clone or download this repository to your local machine
2. Ensure all image files are placed in an `assets` directory
3. Make sure all CSS files are in the same directory as the HTML files
4. Open `index.html` in a web browser to view the homepage

## Testing

### Desktop Testing
1. Open `index.html` in different browsers (Chrome, Firefox, Safari)
2. Verify that:
   - All images load properly
   - Layout is consistent across browsers
   - Navigation links work correctly
   - The story section displays image and text side by side
   - Recipe cards are arranged in a grid

### Mobile Testing
1. Use browser developer tools to test responsive design
2. Test at various breakpoints:
   - Below 768px: Content should stack vertically
   - Story image should appear above text
   - Recipe cards should display in a single column

### Dark Mode Testing
1. Enable dark mode in your operating system
2. Verify that:
   - Colors switch to dark theme
   - Text remains readable
   - Accent color maintains brand consistency

### Accessibility Testing
1. Use a screen reader to navigate the site
2. Verify that:
   - All images have descriptive alt text
   - Heading hierarchy makes sense
   - Links have clear purposes
   - Color contrast meets WCAG standards

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Notes

- The website uses CSS variables for easy theme customization
- Font fallbacks are included for better cross-browser compatibility
- Images should be optimized before deployment
- The recipe page includes print-friendly styling

For any questions or issues, please open a GitHub issue or contact the development team.
