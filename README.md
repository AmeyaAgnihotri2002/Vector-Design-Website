# Vector Design Website

![Vector Design](https://img.shields.io/badge/Status-Active-success)
![Version](https://img.shields.io/badge/Version-1.0-blue)
![License](https://img.shields.io/badge/License-MIT-green)

A modern, futuristic portfolio website for Vector Design - a product engineering and prototyping company specializing in mechanical design, embedded systems, and electronics.

## 🚀 Live Demo

[View Live Website](#) <!-- Add your deployed URL here -->

## ✨ Features

### 🎨 Design & Animation
- **Futuristic UI**: Cyberpunk-inspired design with cyan and purple gradients
- **Particle Background**: Animated canvas with 60 interconnected particles
- **Floating Orbs**: Three gradient orbs with smooth floating animations
- **Custom Cursor**: Glowing cursor with outline effect (desktop only)
- **Smooth Scrolling**: Buttery-smooth scroll animations throughout
- **Card Animations**: 3D tilt effects and hover transformations
- **Background Images**: Blurred background images on feature cards for visual depth

### 📱 Responsive Design
- **Mobile-First**: Optimized for all screen sizes
- **Breakpoints**:
  - Desktop: 1920px+
  - Laptop: 1024px - 1920px
  - Tablet: 768px - 1024px
  - Mobile: 320px - 768px
- **Touch-Friendly**: Disabled 3D effects on mobile for better performance
- **Adaptive Layouts**: Grid systems that adapt to screen size

### 🎯 Sections
1. **Hero Section** - Eye-catching introduction with CTA buttons
2. **Workflow** - 4-phase engineering process visualization
3. **Choose Where to Engage** - Service offerings with background images
4. **Services** - Core technical capabilities
5. **Why Vector Design** - Value propositions
6. **Selected Work** - Project portfolio with SVG placeholders
7. **CTA Section** - Call-to-action for consultations
8. **Contact** - Multiple contact methods
9. **Footer** - Company information

### ⚡ Performance
- **Optimized Animations**: Hardware-accelerated CSS transforms
- **Lazy Loading**: Intersection Observer for on-scroll reveals
- **Debounced Events**: Optimized scroll and resize handlers
- **Reduced Particles**: 60 particles (down from 80) for better FPS
- **Efficient Rendering**: RequestAnimationFrame for smooth 60fps

## 🛠️ Technologies

- **HTML5** - Semantic markup
- **CSS3** - Advanced animations, gradients, and effects
- **JavaScript (Vanilla)** - No frameworks, pure performance
- **Google Fonts** - Oxanium & Geist typefaces

## 📁 File Structure

```
vector-design-website/
├── index.html          # Main HTML structure
├── styles.css          # All styling and animations
├── script.js           # Interactive functionality
├── images/             # Image assets
│   ├── VD_WHITE_CROP.png
│   ├── feasibility_assignment.png
│   ├── concept_to_cad.png
│   ├── prototype_building.png
│   ├── production_ready_handoff.png
│   ├── electronics_and_firmware.png
│   └── engineering_consulting.png
└── README.md           # This file
```

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- Basic understanding of HTML/CSS/JS (for customization)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/AmeyaAgnihotri2002/Vector-Design-Website.git
   cd Vector-Design-Website
   ```

2. **Add your images**
   - Place your logo in `images/VD_WHITE_CROP.png`
   - Add service images to the `images/` folder

3. **Open in browser**
   ```bash
   # Simply open index.html in your browser
   # Or use a local server:
   python -m http.server 8000
   # Then visit http://localhost:8000
   ```

## 🎨 Customization

### Colors
Edit CSS variables in `styles.css`:
```css
:root {
  --cyan: #00d9ff;        /* Primary color */
  --purple: #c084fc;      /* Accent color */
  --bg-dark: #050a14;     /* Background */
  --text-primary: #f8fafc;/* Text color */
}
```

### Content
Edit text directly in `index.html`:
- Company name and tagline
- Service descriptions
- Contact information
- Project titles

### Images
Replace placeholder images in the `images/` folder with your own:
- Logo: `VD_WHITE_CROP.png` (80x80px recommended)
- Service backgrounds: 1024x1024px recommended

### Animations
Adjust animation speeds in `styles.css`:
```css
/* Orb animation speed */
.orb-1 { animation-duration: 10s; }  /* Change this value */

/* Card hover transition */
.feature-card { transition: all .25s; }  /* Adjust timing */
```

## 📱 Browser Support

| Browser | Version | Support |
|---------|---------|---------|
| Chrome  | 90+     | ✅ Full |
| Firefox | 88+     | ✅ Full |
| Safari  | 14+     | ✅ Full |
| Edge    | 90+     | ✅ Full |
| Mobile  | All     | ✅ Full |

## 🐛 Known Issues

- Custom cursor disabled on mobile (intentional for UX)
- Particle canvas may lag on very old devices
- Background blur effects require modern browser support

## 🔧 Troubleshooting

### Animations not working on desktop
- Check browser console for JavaScript errors
- Ensure all files are in the same directory
- Clear browser cache and reload

### Images not loading
- Verify image paths in HTML match actual file locations
- Check that images are in the `images/` folder
- Ensure filenames match exactly (case-sensitive)

### Mobile menu not working
- Verify `script.js` is loaded correctly
- Check for JavaScript errors in mobile browser console

## 📄 License

This project is licensed under the MIT License - see below for details:

```
MIT License

Copyright (c) 2025 Vector Design

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## 👤 Author

**Ameya Agnihotri**
- GitHub: [@AmeyaAgnihotri2002](https://github.com/AmeyaAgnihotri2002)
- LinkedIn: [ameyaagnihotri](https://www.linkedin.com/in/ameyaagnihotri)
- Email: ameyaagnihotri@gmail.com
- Phone: +91 8767147642

## 🙏 Acknowledgments

- Font families from Google Fonts (Oxanium & Geist)
- Inspiration from modern cyberpunk UI design
- Built with performance and accessibility in mind

## 📝 Changelog

### Version 1.0 (Current)
- ✅ Initial release
- ✅ Fully responsive design
- ✅ Particle background animation
- ✅ Custom cursor effect
- ✅ All sections implemented
- ✅ Contact form integration ready
- ✅ SEO optimized
- ✅ Cross-browser compatible

## 🚀 Future Enhancements

- [ ] Add contact form backend integration
- [ ] Implement dark/light mode toggle
- [ ] Add project detail modals
- [ ] Integrate blog section
- [ ] Add testimonials carousel
- [ ] Implement multi-language support
- [ ] Add service booking system
- [ ] Create admin dashboard for content management

## 📞 Support

For questions or support, please contact:
- Email: ameyaagnihotri@gmail.com
- WhatsApp: [+91 8767147642](https://wa.me/918767147642)

---

**Built with ❤️ by Vector Design** | © 2025 All Rights Reserved
