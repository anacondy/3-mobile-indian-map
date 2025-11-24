# India Governance Map 2025

An interactive, responsive web application displaying political control and governance across Indian states and union territories. Built with modern glassmorphism design principles and optimized for both mobile and desktop experiences.

![Desktop View](https://github.com/user-attachments/assets/5416c659-de1a-43f2-b2ae-4e0a45a6e8f0)

## 🎯 Features

### Core Functionality
- **Interactive Map**: Click on any state to view detailed political information
- **Real-time Data**: Up-to-date information on Chief Ministers, ruling parties, and assembly composition
- **Color-Coded Visualization**: 
  - 🟠 **Saffron**: NDA (National Democratic Alliance) controlled states
  - 🔵 **Cyan**: INDIA Bloc controlled states
  - 🟡 **Yellow**: Regional/Independent parties
- **Responsive Sidebar**: 
  - Desktop: Slide-in panel from the right
  - Mobile: Bottom sheet with swipe-to-close gesture

### System Registry Module
- **Hidden Easter Egg**: Access system information by holding `C + O + 2` for 2 seconds
- **System Information**: Version, author, and module details
- **Glassmorphic Terminal Design**: Retro-futuristic aesthetic with neon accents

### Design Highlights
- **Glassmorphism UI**: Modern frosted glass effect with backdrop blur
- **Dark Theme**: Optimized for reduced eye strain
- **Smooth Animations**: Fluid transitions and interactive feedback
- **Mobile-First**: Fully responsive with touch-optimized interactions
- **Accessibility**: High contrast tooltips and readable typography

## 🚀 Quick Start

### Installation

No installation required! This is a static web application.

1. Clone the repository:
   ```bash
   git clone https://github.com/anacondy/3-mobile-indian-map.git
   cd 3-mobile-indian-map
   ```

2. Open `index.html` in your browser:
   ```bash
   # Using Python
   python3 -m http.server 8080
   
   # Using Node.js
   npx http-server
   
   # Or simply open index.html in your browser
   ```

3. Navigate to `http://localhost:8080` (or the appropriate port)

## 📱 Usage Guide

### Desktop Experience
1. **Hover** over states to see their names
2. **Click** on any state to view detailed information
3. The sidebar will slide in from the right with political data
4. **Click the background** or the map to close the sidebar

### Mobile Experience
1. **Tap** on any state to select it
2. A bottom sheet will slide up with state information
3. **Swipe down** on the bottom sheet to close it
4. **Tap the background** to deselect

### System Registry Access
- **Hold** the keys `C + O + 2` simultaneously for 2 seconds
- A terminal-style overlay will appear with system information
- **Press ESC** or **click [X]** to close the registry

## 🏗️ Project Structure

```
3-mobile-indian-map/
├── index.html           # Main application file (integrated with System Registry)
├── SystemRegistry.html  # Original standalone System Registry module
├── README.md           # This file
├── .gitignore          # Git ignore patterns
└── screenshots/        # Application screenshots (if added)
```

## 🔧 Technical Details

### Technologies Used
- **HTML5**: Semantic markup
- **CSS3**: Advanced styling with backdrop-filter, animations, and responsive design
- **JavaScript (ES6+)**: Modern JavaScript with async/await and event handling
- **Leaflet.js**: Open-source mapping library
- **GeoJSON**: India state boundaries data

### Browser Compatibility
- ✅ Chrome/Edge 88+ (recommended)
- ✅ Firefox 94+
- ✅ Safari 15.4+
- ✅ Mobile browsers (iOS Safari 15+, Chrome Mobile)

### Performance Optimizations
- **Passive Event Listeners**: Improved scroll and touch performance
- **RequestAnimationFrame**: Smooth animations
- **CSS Hardware Acceleration**: GPU-accelerated transitions
- **Minimal Dependencies**: Only Leaflet.js required

## 📊 Testing Information

### Last Tested
- **Date**: November 23, 2025
- **Environment**: Chrome 120+, Firefox 121+, Safari 17+, Mobile Chrome/Safari
- **Resolution**: Desktop (1920x1080), Tablet (768x1024), Mobile (375x667)

### Test Results

#### ✅ Working Features
- [x] Map rendering and tile loading
- [x] State selection and highlighting
- [x] Sidebar display (desktop slide-in, mobile bottom sheet)
- [x] Swipe-to-close gesture on mobile
- [x] State name tooltips on hover
- [x] Background click to close sidebar
- [x] Zoom to state on selection
- [x] System Registry activation (C+O+2 hold)
- [x] System Registry close (ESC and X button)
- [x] Responsive layout switching (mobile/desktop)
- [x] Touch event handling on mobile devices
- [x] Glassmorphism effects and backdrop blur

#### ⚠️ Known Limitations
- Requires internet connection for map tiles and GeoJSON data
- Backdrop-filter not fully supported in older browsers (graceful degradation)
- System Registry requires keyboard (not accessible on touch-only devices)

### Device Optimization
- **Optimized for**: Both mobile and desktop devices
- **Mobile Features**: 
  - Touch-friendly tap targets
  - Swipe gestures
  - Bottom sheet interface
  - Viewport-aware padding
  - No horizontal scroll
- **Desktop Features**:
  - Hover effects
  - Keyboard shortcuts
  - Right-side panel
  - Mouse interaction

### Data Accuracy
- Political data current as of November 2025
- Covers all 28 states and 8 union territories
- Includes Chief Minister names, ruling parties, and assembly seat counts

## 🔒 Security

### Security Measures
- **No External Form Submissions**: All interactions are client-side
- **No Data Collection**: Privacy-focused, no analytics or tracking
- **No Backend Dependencies**: Static files only
- **CSP Compatible**: Can be deployed with Content Security Policy
- **HTTPS Ready**: Works over secure connections

### Vulnerability Status
- ✅ No known security vulnerabilities
- ✅ No third-party authentication
- ✅ No server-side processing
- ✅ No user data storage
- ✅ Sanitized data rendering (template literals with static data)

## 🎨 Code Quality

### Code Standards
- **Comprehensive Comments**: Every function and section documented
- **Semantic HTML**: Proper use of HTML5 elements
- **BEM-like CSS**: Organized and maintainable styles
- **JSDoc Style**: Function documentation with parameter types
- **Consistent Formatting**: Readable indentation and spacing

### Accessibility
- Semantic HTML structure
- High contrast text
- Keyboard navigation support
- ARIA-friendly markup
- Screen reader compatible

## 🌐 Deployment

### GitHub Pages
This site is deployed at: [https://anacondy.github.io/3-mobile-indian-map/](https://anacondy.github.io/3-mobile-indian-map/)

### Manual Deployment
1. Upload all files to your web server
2. Ensure `index.html` is accessible
3. No server-side configuration required

### CDN Requirements
The following CDN resources are loaded:
- Leaflet.js (mapping library)
- Google Fonts (Inter, JetBrains Mono)
- CartoDB map tiles

## 📝 License

This project is open source and available under standard open-source terms.

## 👤 Author

**ANACONDY**
- Version: 6.0 (Integrated)
- Origin Date: November 23, 2025

## 🤝 Contributing

Contributions are welcome! Please feel free to submit issues or pull requests.

### Development Guidelines
1. Maintain code comment standards
2. Test on both mobile and desktop
3. Ensure backwards compatibility
4. Follow existing code style
5. Update README with any new features

## 📞 Support

For issues or questions:
1. Check existing GitHub issues
2. Review the code comments in `index.html`
3. Test in different browsers
4. Create a new issue with details

## 🔄 Version History

- **v6.0 (Integrated)** - November 23, 2025
  - Integrated System Registry module into main application
  - Added comprehensive code comments
  - Enhanced README with detailed documentation
  - Improved mobile responsiveness
  - Added security documentation

---

**Made with ❤️ for exploring India's political landscape**
