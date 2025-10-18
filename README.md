# 🍽️ Borchelle - Premium Tableware E-commerce

A modern, elegant e-commerce website for premium handcrafted tableware. Built with vanilla JavaScript, featuring a clean design with sage green and mustard yellow color scheme.

## 🌐 Live Demo

**[View Live Site](https://shayannab.github.io/Borchelle/)**

## ✨ Features

### 🛒 E-commerce Functionality
- **Product Catalog** - Beautiful product grid with SVG illustrations
- **Shopping Cart** - Add, remove, and update quantities
- **Wishlist** - Save favorite products for later
- **Product Quick View** - Modal preview with detailed information
- **Search Functionality** - Real-time product search
- **Contact Form** - Get in touch section

### 🎨 Design Features
- **Responsive Design** - Fully optimized for mobile, tablet, and desktop
- **Modern UI/UX** - Clean, minimalist design with smooth animations
- **Glassmorphism Effects** - Premium look with frosted glass buttons
- **Interactive Elements** - Hover effects and micro-interactions
- **Brand Colors** - Sage green (#9CAF88) and mustard yellow (#D4A017)

### 💻 Technical Features
- **Vanilla JavaScript** - No framework dependencies
- **CSS3 Animations** - Smooth transitions and effects
- **Font Awesome Icons** - Beautiful iconography
- **Google Fonts** - Playfair Display & Inter typography
- **Modular Code** - Separate HTML, CSS, and JS files
- **State Management** - In-memory cart and wishlist management

## 📁 Project Structure

```
borchelle/
│
├── index.html          # Main HTML file
├── styles.css          # All styles and responsive design
├── script.js           # JavaScript functionality (incomplete - see below)
├── README.md           # Project documentation
└── assets/             # Images and media (optional)
    └── logo.png        # Brand logo
```

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- A code editor (VS Code, Sublime Text, etc.)
- Optional: Live Server extension for development

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/YOUR_USERNAME/borchelle.git
   cd borchelle
   ```

2. **Open the project**
   - Simply open `index.html` in your browser, OR
   - Use a local development server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js (with http-server)
   npx http-server
   
   # Using VS Code Live Server extension
   Right-click index.html → Open with Live Server
   ```

3. **Customize**
   - Replace logo placeholder in `index.html`
   - Update product images with real product photos
   - Modify colors in `styles.css` (search for #9CAF88 and #D4A017)
   - Add your contact information in the contact section

## ⚠️ Important Note

**The `script.js` file is incomplete.** The previous artifact response was cut off. You'll need to complete the JavaScript functionality. Here's what's missing:

### To Complete:
1. Finish the `updateWishlistDisplay()` function
2. Add `closeSidebars()` function
3. Add `openProductModal()` function
4. Add `closeModal()` function
5. Add `renderProducts()` function
6. Add notification system functions
7. Add modal quantity controls
8. Complete contact form handler

### Quick Fix:
You can copy the complete JavaScript from the previous conversation or I can provide it separately.

## 🎨 Color Palette

| Color | Hex Code | Usage |
|-------|----------|-------|
| Sage Green | `#9CAF88` | Primary brand color, buttons, accents |
| Mustard Yellow | `#D4A017` | Secondary color, prices, highlights |
| Dark Gray | `#2c2c2c` | Text, headings |
| Light Gray | `#6b6b6b` | Body text |
| Off White | `#fdfcfa` | Background |
| Pure White | `#ffffff` | Cards, modals |

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: 480px - 767px
- **Small Mobile**: Below 480px

## 🛠️ Built With

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with Flexbox and Grid
- **JavaScript (ES6+)** - Vanilla JS for functionality
- **Font Awesome** - Icon library
- **Google Fonts** - Typography (Playfair Display, Inter)

## 📦 Dependencies

### CDN Links (already included):
```html
<!-- Font Awesome -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">

<!-- Google Fonts -->
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;500;600&family=Inter:wght@300;400;500&display=swap" rel="stylesheet">
```

## 🎯 Features Roadmap

### Current Features ✅
- [x] Responsive design
- [x] Product catalog
- [x] Shopping cart (add/remove/update)
- [x] Wishlist functionality
- [x] Product search
- [x] Product quick view modal
- [x] Contact form UI

### Planned Features 🚧
- [ ] Backend integration (checkout, payment)
- [ ] User authentication
- [ ] Product reviews and ratings
- [ ] Order tracking
- [ ] Email notifications
- [ ] Product filtering and sorting
- [ ] Related products suggestions
- [ ] Persistent cart (localStorage/backend)

## 💡 Usage Examples

### Adding Products
```javascript
// In script.js, modify the products array:
const products = [
    {
        id: 5,
        name: "Your Product Name",
        description: "Product description here",
        price: 99,
        image: `<svg>...</svg>` // or use <img src="...">
    }
];
```

### Customizing Colors
```css
/* In styles.css, search and replace: */
#9CAF88 → Your primary color
#D4A017 → Your secondary color
```

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**Your Name**
- GitHub: [@shayannab]([https://github.com/shayannab])
- X: [shayanna_0]([https://x.com/shayanna_0])
- Portfolio: [yourwebsite.com](https://yourwebsite.com)

## 🙏 Acknowledgments

- Design inspiration from modern DTC brands
- Font Awesome for the beautiful icons
- Google Fonts for typography
- The open-source community

## 📞 Support

For support, email your.email@example.com or open an issue in the GitHub repository.

## 🔗 Links

- **Live Demo**: [https://shayannab.github.io/Borchelle/]
- **Repository**: [https://github.com/shayannab/Borchelle]([https://github.com/shayannab/Borchelle])


---

<p align="center">Made with ❤️ for premium tableware lovers</p>
<p align="center">⭐ Star this repo if you found it helpful!</p>
