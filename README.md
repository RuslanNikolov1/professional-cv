# Professional Resume - Ruslan Nikolov

A modern, responsive resume website with PDF generation capabilities.

## Features

- **Professional Design**: Clean, modern layout with professional typography
- **Responsive Layout**: Optimized for desktop, tablet, and mobile devices
- **PDF Generation**: One-click PDF export with proper formatting
- **Print-Friendly**: Optimized for both screen and print media
- **Accessibility**: Semantic HTML structure for better accessibility

## Usage

1. Open `index.html` in your web browser
2. Review the resume content
3. Click "Generate PDF" to download a professionally formatted PDF
4. Use Ctrl+P (or Cmd+P on Mac) as a keyboard shortcut for PDF generation

## Technical Details

- **HTML5**: Semantic structure with proper accessibility
- **CSS3**: Modern styling with flexbox and grid layouts
- **JavaScript**: PDF generation using html2pdf.js library
- **Responsive Design**: Mobile-first approach with breakpoints
- **Print Optimization**: Special print styles for clean PDF output

## Browser Support

- Chrome (recommended for PDF generation)
- Firefox
- Safari
- Edge

## File Structure

```
├── index.html          # Main HTML file
├── styles.css          # CSS styling
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## PDF Generation

The PDF generation uses the html2pdf.js library with the following optimizations:

- High-quality rendering (scale: 2)
- Proper page breaks
- Letter format (8.5" x 11")
- Optimized margins
- CORS support for external resources

## Customization

To modify the resume content:

1. Edit the HTML structure in `index.html`
2. Adjust styling in `styles.css`
3. Modify PDF options in `script.js` if needed

## Dependencies

- html2pdf.js (loaded via CDN)
- No additional dependencies required

## License

This project is for personal use. Please respect copyright and licensing requirements for any commercial use.

