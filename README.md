# Precision-and-Craft

# Advanced CSS Hero - Design Craftsmanship

> A stunning, interactive landing page showcasing advanced CSS techniques, pure CSS animations, and modern web design principles. Built with zero dependencies—just HTML, CSS, and vanilla JavaScript.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## ✨ Features

### 🎨 **Advanced CSS Techniques**
- **CSS Grid & Flexbox**: Responsive two-column hero layout that adapts seamlessly from mobile to desktop
- **Custom CSS Variables**: Complete theming system with monochromatic purple color palette
- **CSS Animations**: Smooth keyframe animations for all interactive elements
- **Pure CSS Shapes**: Floating orbs created entirely with CSS gradients and blur filters
- **SVG Integration**: Animated geometric illustrations with rotating and pulsing effects

### 🚀 **Interactive Elements**
- **Gradient Text Effects**: Eye-catching animated gradient text with underline reveal
- **Hover Animations**: Smooth transitions and scale effects on all interactive elements
- **Shimmer Effects**: Subtle light reflections across buttons and cards
- **Floating Animations**: Organic movement patterns for decorative elements

### 📱 **Testimonials Carousel**
- **Auto-scrolling**: Infinite horizontal scroll with smooth looping
- **Pause on Hover**: Accessibility-friendly interaction
- **Gradient Masks**: Elegant fade effects on carousel edges
- **Responsive Cards**: Optimized layouts for all screen sizes
- **Animated Backgrounds**: Dynamic diagonal glow effects with rotating radial patterns

### ♿ **Accessibility First**
- **Semantic HTML**: Proper heading hierarchy and ARIA labels
- **Reduced Motion Support**: Respects user preferences with `prefers-reduced-motion`
- **Keyboard Navigation**: Fully accessible interactive elements
- **High Contrast**: Readable text with proper color contrast ratios

### 📐 **Responsive Design**
- **Mobile-First Approach**: Optimized for all devices from 320px to 4K displays
- **Fluid Typography**: `clamp()` functions for perfect scaling
- **Adaptive Layouts**: Grid columns adjust based on viewport size
- **Touch-Friendly**: Optimized tap targets for mobile users

## 🎯 Demo

![Hero Section Preview](https://via.placeholder.com/1200x600/8b5cf6/ffffff?text=Hero+Section+Preview)

*[Add a screenshot or GIF of your landing page here]*

## 🚀 Quick Start

### Prerequisites
- Any modern web browser (Chrome, Firefox, Safari, Edge)
- No build tools or dependencies required!

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/ritesh-sinha29/precision-and-craft.git
   cd precesion-and-craft
   ```

2. **Open in browser**
   ```bash
   # Simply open the HTML file
   open index.html
   # Or on Linux
   xdg-open index.html
   # Or on Windows
   start index.html
   ```

That's it! No npm install, no build process—just open and explore.

## 📂 Project Structure

```
precision-and-craft/
│
├── index.html              # Main HTML file with inline CSS and JS
├── README.md              # This file
└── assets/                # (Optional) Add your images/screenshots here
```

## 🎨 Customization

### Color Palette

All colors are defined as CSS variables in the `:root` selector. Easy to customize:

```css
:root {
  --primary: #8b5cf6;        /* Main purple */
  --accent: #a78bfa;         /* Light purple */
  --secondary: #6d28d9;      /* Deep purple */
  --tertiary: #c4b5fd;       /* Very light purple */
  --bg-dark: #1e1b2e;        /* Background dark */
  --bg-light: #2d2640;       /* Background light */
}
```

### Typography

Adjust font sizes using the spacing system:

```css
:root {
  --font-size-base: 1rem;
  --font-size-lg: 1.125rem;
  --font-size-xl: 1.5rem;
  --font-size-2xl: 2rem;
  --font-size-3xl: 3rem;
}
```

### Spacing

Consistent spacing throughout:

```css
:root {
  --spacing-xs: 0.5rem;
  --spacing-sm: 1rem;
  --spacing-md: 1.5rem;
  --spacing-lg: 2rem;
  --spacing-xl: 3rem;
  --spacing-2xl: 4rem;
}
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup with accessibility features
- **CSS3**: Advanced features including Grid, Flexbox, custom properties, and keyframe animations
- **Vanilla JavaScript**: Minimal JS for button interactions
- **SVG**: Inline vector graphics for scalable illustrations

## 📖 Learning Resources

This project demonstrates:

1. **CSS Grid Layout**: Two-column responsive layouts
2. **CSS Custom Properties**: Theming and design systems
3. **CSS Animations**: Keyframes, transitions, and transforms
4. **CSS Gradients**: Linear and radial gradients for depth
5. **CSS Filters**: Blur effects for glassmorphism
6. **CSS Masks**: Gradient masks for carousel effects
7. **Pure CSS Shapes**: Creating complex shapes without images
8. **SVG Animation**: Animated vector graphics
9. **Responsive Design**: Mobile-first approach with media queries
10. **Accessibility**: ARIA labels and reduced motion support

## 🌟 Browser Support

| Browser | Version |
|---------|---------|
| Chrome  | Latest 2 versions |
| Firefox | Latest 2 versions |
| Safari  | Latest 2 versions |
| Edge    | Latest 2 versions |

*Note: CSS Grid and custom properties are required. No IE11 support.*

## 📝 Code Highlights

### Animated Gradient Text
```css
.hero__title-gradient {
  background: linear-gradient(135deg, var(--primary) 0%, var(--tertiary) 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
}
```

### Floating Orb Animation
```css
@keyframes floatOrb {
  0%, 100% { transform: translate(0, 0) scale(1); }
  25% { transform: translate(15px, -20px) scale(1.05); }
  50% { transform: translate(-10px, 10px) scale(0.95); }
  75% { transform: translate(20px, 15px) scale(1.02); }
}
```

### Infinite Carousel Scroll
```css
@keyframes scrollReviews {
  from { transform: translateX(0); }
  to { transform: translateX(-50%); }
}
```

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Contribution Ideas
- Add more animation variations
- Create alternative color schemes
- Improve accessibility features
- Add more testimonial cards
- Create additional sections (About, Services, Contact)
- Optimize performance

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

```
MIT License

Copyright (c) 2024 [Your Name]

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
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
```

## 👤 Author

**[Ritesh Sinha]**
- GitHub: [@ritesh-sinha29](https://github.com/ritesh-sinha29)
- Website: [precision-and-craft](https://precision-and-craft-three.vercel.app/)

## 🙏 Acknowledgments

- Inspired by modern web design trends and Dribbble designers
- Color palette inspired by Tailwind CSS's purple shades
- Typography using system font stack for optimal performance
- SVG animations inspired by the CSS-Tricks community

## 📊 Project Stats

- **Lines of CSS**: ~800+
- **CSS Animations**: 15+
- **No dependencies**: 0 npm packages
- **Load time**: < 1 second
- **File size**: ~45KB (uncompressed)

## 🔮 Future Enhancements

- [ ] Add dark/light theme toggle
- [ ] Implement more color scheme options
- [ ] Add contact form with validation
- [ ] Create additional page sections
- [ ] Add scroll-triggered animations
- [ ] Implement lazy loading for performance
- [ ] Add more interactive elements
- [ ] Create TypeScript version

---

<div align="center">

**If you find this project helpful, please consider giving it a ⭐ star!**

Made with 💜 and lots of CSS

</div>
