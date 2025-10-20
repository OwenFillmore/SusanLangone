# Susan Langone Portfolio Website

A visually stunning, modern portfolio website for Susan Langone - Artist, Designer, and Director of The Center For Resiliency.

## Features

### Design Highlights
- **Preserved Border Implementation**: The original floral border code has been preserved exactly as specified, with all border functionality intact
- **"Hello, My Name Is" Sticker**: Fun, elegant name tag with interactive hover effects
- **Responsive Design**: Fully optimized for desktop, tablet, and mobile devices
- **Modern Aesthetics**: Clean, elegant design with smooth animations and transitions
- **Accessibility**: WCAG compliant with skip links, ARIA labels, and keyboard navigation

### Sections

#### 1. Hero Section
- Features Susan's portrait from `SusanPicture.jpeg`
- Center For Resiliency logo prominently displayed
- Compelling headline and call-to-action buttons
- Responsive two-column layout

#### 2. Gallery
- Displays all artwork from `SusansFiles/Artwork/` folder:
  - Green Flowers
  - Purple Flowers
  - Red Flowers
  - Transform
  - Wonderful
- Responsive grid layout
- Hover effects with smooth transitions
- Lazy loading for performance

#### 3. About / Bio
- Comprehensive information about Susan's work
- Two-column responsive layout
- Services overview with icons
- Mission statement highlight box
- Content about The Center For Resiliency

#### 4. Contact
- Functional contact form with validation
- Contact information card
- Email integration
- Form submission with visual feedback

### Technical Features

#### Border Implementation (Preserved)
The following code has been preserved exactly from the original:
- `.frame-img` - Fixed position border image
- `.frame-fallback` - SVG fallback border
- `.oval-window` - Content container
- Parallax scroll effect
- Border fit controls (Fill, Fit, Zoom)
- Error handling for missing images

#### Interactive Elements
- **Dark Mode Toggle**: Persistent theme switching with localStorage
- **Border Controls**: Adjustable border display mode
- **Smooth Scrolling**: Enhanced navigation experience
- **Intersection Observer**: Fade-in animations as sections appear
- **Form Validation**: Real-time validation with user feedback

#### Performance Optimizations
- Lazy loading for images
- RequestAnimationFrame for scroll animations
- Reduced motion support for accessibility
- Optimized CSS with modern techniques

## File Structure

```
SusanLangone-13/
├── index.html                          # Main website file
├── border.png                          # Border image
├── SusansFiles/
│   ├── CenterForResiliencyLogo.png    # Logo
│   ├── SusanPicture.jpeg              # Portrait
│   ├── Artwork/                        # Gallery images
│   │   ├── GreenFlowers.jpeg
│   │   ├── PurpleFlowers.png
│   │   ├── RedFlowers.png
│   │   ├── Transform.png
│   │   └── Wonderful.png
│   ├── Forms/                          # PDF forms
│   └── Writing Materials/              # Bio documents
```

## Color Palette

- **Rose**: `#C24A6B` - Primary accent
- **Leaf**: `#4E7B51` - Secondary accent
- **Gold**: `#D4A574` - Warm accent
- **Purple**: `#8B6B9E` - Creative accent
- **Teal**: `#5B9AA0` - Fresh accent

## Typography

- **Headings**: Playfair Display (Google Fonts)
- **Body**: System font stack for optimal performance

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Accessibility

- WCAG 2.1 AA compliant
- Keyboard navigation support
- Screen reader friendly
- Skip to content link
- ARIA labels and landmarks
- Focus indicators
- Reduced motion support

## Usage

Simply open `index.html` in any modern web browser. No build process or server required.

### Customization

1. **Update Content**: Edit the HTML in `index.html`
2. **Change Colors**: Modify CSS variables in the `:root` selector
3. **Add Gallery Items**: Add images to `SusansFiles/Artwork/` and update the `galleryData` array in the JavaScript
4. **Adjust Border**: Use the floating controls or modify CSS for `.frame-img`

## Credits

Design and Development: Custom built with modern web standards
Fonts: Playfair Display from Google Fonts
Icons: Emoji-based for universal support

---

© 2025 Susan Langone. All rights reserved.
