# Biker Zone 🏍️

A modern, responsive motorcycle showcase and sales platform built with cutting-edge web technologies. Explore and purchase premium motorcycles with an intuitive user interface.

**Live Demo:** [https://ahammad204.github.io/Biker-zone/](https://ahammad204.github.io/Biker-zone/)

---

## 📋 Table of Contents

- [About](#about)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Installation & Setup](#installation--setup)
- [Usage](#usage)
- [Key Sections](#key-sections)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)

---

## 🎯 About

**Biker Zone** is a premium motorcycle marketplace and information hub. It showcases the latest motorcycle models, customer testimonials, and provides valuable information to motorcycle enthusiasts. The platform is fully responsive and optimized for all devices, offering users an engaging experience whether they're browsing on desktop, tablet, or mobile devices.

---

## ✨ Features

- **🎠 Image Carousel**: Interactive slider showcasing featured motorcycles (up to 4 slides)
- **📱 Responsive Design**: Fully optimized for mobile, tablet, and desktop screens
- **🏍️ Latest Bikes Section**: Grid layout displaying three featured motorcycle models
- **⭐ Customer Testimonials**: Real customer reviews with star ratings and detailed feedback
- **❓ FAQ Section**: Comprehensive answers to common questions about motorcycle riding and safety
- **📱 Mobile App Integration**: Direct links to download Android and iOS mobile apps
- **🎨 Modern UI**: Clean, professional design with custom color schemes and animations
- **♿ Accessibility**: Semantic HTML and accessible component structure
- **🚀 Performance**: Optimized assets and CDN-based dependencies

---

## 🛠️ Tech Stack

| Technology | Purpose |
|-----------|---------|
| **HTML5** | Semantic markup and structure |
| **Tailwind CSS** | Utility-first CSS framework for rapid UI development |
| **DaisyUI** | Pre-built component library for Tailwind CSS |
| **JavaScript** | Interactive functionality and carousel logic |
| **Google Fonts** | Premium typography (Poppins font family) |

### Dependencies:
- Tailwind CSS v3 (via CDN)
- DaisyUI v3.3.1 (via CDN)
- Google Fonts (Poppins)

---

## 📁 Project Structure

```
Biker-zone/
├── index.html                 # Main HTML file
├── tailwind.config.js         # Tailwind CSS configuration
├── README.md                  # Project documentation (this file)
└── images/
    ├── slider/                # Carousel/slider images
    │   ├── bike1.png
    │   ├── bike2.png
    │   ├── bike3.png
    │   └── bike4.png
    ├── others/                # Other images
    │   ├── latest1.png        # Ducati XDIAVEL S-73
    │   ├── latest2.png        # Motorcycles & Scooters
    │   ├── latest3.png        # 2021 Honda CBR500R
    │   ├── user-1.png         # Customer testimonial 1
    │   ├── user-2.png         # Customer testimonial 2
    │   ├── user-3.png         # Customer testimonial 3
    │   ├── faq.png            # FAQ section image
    │   ├── android.png        # Android app badge
    │   └── ios.png            # iOS app badge
    └── icons/                 # Icon assets (if any)
```

---

## 🚀 Installation & Setup

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Text editor or IDE (VS Code recommended)
- Basic knowledge of HTML/CSS/JavaScript

### Steps

1. **Clone the Repository**
   ```bash
   git clone https://github.com/ahammad204/Biker-zone.git
   cd Biker-zone
   ```

2. **Open the Project**
   ```bash
   # Simply open index.html in your browser
   # Or use a local server for best results
   ```

3. **Using a Local Server (Recommended)**
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Python 2
   python -m SimpleHTTPServer 8000
   
   # Using Node.js (http-server)
   npm install -g http-server
   http-server
   ```

4. **Access the Site**
   - Open your browser and navigate to `http://localhost:8000`

---

## 💻 Usage

### Local Development

1. **Edit HTML Content**: Modify `index.html` to update text, links, and content
2. **Customize Styles**: Use Tailwind CSS classes or add custom CSS in the `<style>` tag
3. **Update Images**: Replace or add new images in the `images/` directory
4. **Test Responsiveness**: Use browser developer tools (F12) to test different screen sizes

### Building for Production

1. Build Tailwind CSS (if using CLI):
   ```bash
   npx tailwindcss -i ./input.css -o ./output.css --watch
   ```

2. Optimize images using tools like:
   - TinyPNG
   - ImageOptim
   - Squoosh

3. Test across all browsers and devices before deployment

---

## 📄 Key Sections

### 1. **Navigation Header**
- Logo/Brand name
- Responsive menu (hamburger on mobile)
- Desktop navigation links (Home, Shop, News, Contact)
- Login button

### 2. **Hero Carousel**
- 4-slide image carousel featuring R15 V4 motorcycles
- Call-to-action "Purchase" buttons
- Manual navigation controls (previous/next buttons)
- Responsive layout (single column on mobile, two columns on desktop)

### 3. **Latest Bikes**
- 3-column grid layout (responsive)
- Bike cards with images and descriptions
- Featured models:
  - Ducati XDIAVEL S-73
  - Motorcycles & Scooters
  - 2021 Honda CBR500R
- "Read More" action buttons

### 4. **Customer Testimonials**
- 3-column testimonial cards
- Customer photos and names
- Star rating system (4/5 stars)
- Professional testimonials
- Job titles (e.g., Banker)

### 5. **FAQ Section**
- Accordion-style expandable questions
- Topics covered:
  - Bike riding safety tips
  - Helmet maintenance and replacement
  - Post-storage motorcycle safety
- Accompanying FAQ image

### 6. **Footer**
- Copyright information
- Mobile app download links (Android & iOS)
- Responsive footer layout

---

## 🎨 Customization

### Color Scheme

Custom colors are defined in the HTML `<script>` tag:

```javascript
colors: {
  clifford: '#da373d',
  'bike-primary': '#E76F51',
  'bike-primary-bg': 'rgba(231, 111, 81, 0.10)',
  'text-color': '#23A6F0',
}
```

**To change colors:**
1. Locate the Tailwind config script in `index.html`
2. Modify the hex values
3. Update class references throughout the HTML

### Typography

- **Font Family**: Poppins (loaded from Google Fonts)
- **Font Weights**: 400, 500, 600, 700, 800

**To change fonts:**
1. Update the Google Fonts link in the `<head>`
2. Modify the `.font-poppins` class

### Responsive Breakpoints

Tailwind CSS breakpoints used:
- `sm`: 640px
- `md`: 768px
- `lg`: 1024px
- `xl`: 1280px
- `2xl`: 1536px

---

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome for Android)

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork the Repository**
   ```bash
   git clone https://github.com/yourusername/Biker-zone.git
   ```

2. **Create a Feature Branch**
   ```bash
   git checkout -b feature/AmazingFeature
   ```

3. **Make Your Changes**
   - Update content, styles, or functionality
   - Test thoroughly

4. **Commit Your Changes**
   ```bash
   git commit -m 'Add AmazingFeature'
   ```

5. **Push to the Branch**
   ```bash
   git push origin feature/AmazingFeature
   ```

6. **Open a Pull Request**
   - Describe your changes clearly
   - Ensure all tests pass

---

## 📊 Performance Optimization

### Current Optimizations:
- ✅ CDN-based CSS/JS libraries
- ✅ Poppins font pre-connecting
- ✅ Responsive image sizing
- ✅ CSS utility framework (reduced file size)

### Recommended Future Improvements:
- Implement lazy loading for images
- Minify CSS and JavaScript
- Add service worker for PWA capabilities
- Implement image compression
- Add caching strategies

---

## 🛠️ Development Tips

### Adding New Sections:
1. Create a new `<section>` tag
2. Use Tailwind classes for styling
3. Test on mobile and desktop
4. Ensure accessibility

### Modifying Carousel:
- Add/remove slides by duplicating/removing `carousel-item` divs
- Update slide numbers in the navigation links
- Ensure circular navigation (first slide links to last, vice versa)

### Adding New Components:
- Reference DaisyUI documentation: [https://daisyui.com](https://daisyui.com)
- Use appropriate semantic HTML elements
- Maintain mobile-first responsive design

---

## 📞 Support & Contact

For issues, questions, or suggestions:
- **GitHub**: [ahammad204/Biker-zone](https://github.com/ahammad204/Biker-zone)
- **Live Site**: [https://ahammad204.github.io/Biker-zone/](https://ahammad204.github.io/Biker-zone/)

---

## 📜 License

This project is open source and available under the MIT License. See the LICENSE file for more details.

---

## 🎉 Acknowledgments

- **Tailwind CSS** - Utility-first CSS framework
- **DaisyUI** - Component library built on Tailwind CSS
- **Google Fonts** - Premium typography
- **Community Contributors** - Thanks to all who've contributed!

---

## 🚀 Deployment

This project is deployed on GitHub Pages. To deploy your own version:

1. **Enable GitHub Pages** in repository settings
2. **Set branch** to `main` or `gh-pages`
3. **Wait for deployment** (usually < 1 minute)
4. **Access** at `https://yourusername.github.io/Biker-zone/`

---

**Happy riding! 🏍️**
