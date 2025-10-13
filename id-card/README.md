# ID Card Solutions & Graphics Website

A simple, responsive HTML/CSS website for ID Card Solutions & Graphics business.

## Files

- `index.html` - Main HTML file with semantic structure
- `styles.css` - CSS file with mobile-first responsive design

## Customization Instructions

### Adding Images

Replace the image placeholders in the gallery section:

1. Find each `<div class="img-placeholder">Image</div>` element
2. Replace with `<img src="your-image.jpg" alt="Description of image">`
3. Recommended image dimensions: 300x200px (3:2 aspect ratio)

### Updating Contact Information

1. **Phone Number**: Update the phone number in the header and contact section
2. **Address**: Replace the address placeholder in the contact section with the full address
3. **Email**: Add email contact information if needed

### Modifying Content

1. **Company Name**: Update the brand name in the header
2. **Tagline**: Modify the hero section tagline
3. **Gallery Items**: Add or remove gallery items as needed
4. **Pricing**: Update pricing information in the pricing section

### Styling Customization

The CSS uses CSS custom properties (variables) for easy customization:

```css
:root {
  --bg: #fff;           /* Background color */
  --text: #111;         /* Text color */
  --muted: #666;        /* Muted text color */
  --accent: #0b78a2;    /* Accent color (blue) */
  --container: 1100px;  /* Max container width */
  --radius: 10px;       /* Border radius */
}
```

### Responsive Breakpoints

- Mobile: 320px - 479px (1 column gallery)
- Small Mobile: 480px - 719px (2 column gallery)
- Tablet: 720px - 1099px (3 column gallery)
- Desktop: 1100px - 1439px (4 column gallery)
- Large Desktop: 1440px+ (5 column gallery)

## Browser Support

- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile browsers
- CSS Grid and Flexbox support required

## Features

- Mobile-first responsive design
- Semantic HTML structure
- Accessible markup
- Clean, modern styling
- Easy to customize
- Lightweight (no frameworks)
- Google Fonts integration (Inter font family)
