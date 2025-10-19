# Flux Programming Language Website

This is a professional website for downloading and learning about the Flux programming language.

## Files Included

- `index.html` - Main website page
- `styles.css` - Professional styling and responsive design
- `script.js` - Interactive functionality and download handling
- `flux-lang.zip` - Complete Flux language source code package (~700KB)

## How to Run

### Option 1: Simple HTTP Server (Recommended)

If you have Python installed:
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

Then open: http://localhost:8000

### Option 2: Node.js HTTP Server

If you have Node.js installed:
```bash
# Install global HTTP server
npm install -g http-server

# Run server
http-server -p 8000
```

### Option 3: Live Server (VS Code)

1. Install the "Live Server" extension in VS Code
2. Right-click `index.html`
3. Select "Open with Live Server"

### Option 4: Direct File Access

Simply double-click `index.html` to open in your browser. Note: Download functionality may be limited due to CORS restrictions when accessing files directly.

## Website Features

- **Responsive Design** - Works on desktop, tablet, and mobile
- **Download Integration** - Click to download flux-lang.zip
- **Smooth Animations** - Professional UI with hover effects
- **Code Examples** - Interactive syntax highlighting
- **Navigation** - Smooth scrolling between sections

## Website Sections

1. **Hero** - Main introduction and download button
2. **Features** - Key language features with icons
3. **Examples** - Code samples showing Flux syntax
4. **Documentation** - Getting started guide
5. **Download** - Detailed download section with file info

## Technical Details

- Pure HTML5, CSS3, and vanilla JavaScript
- No external dependencies (besides Google Fonts)
- Modern CSS Grid and Flexbox layouts
- Intersection Observer API for animations
- File download via programmatic link creation

## Browser Compatibility

- Chrome/Edge 88+
- Firefox 85+
- Safari 14+
- Mobile browsers (iOS Safari, Chrome Mobile)

The website showcases the Flux programming language with a professional, modern design that would be suitable for any programming language project.