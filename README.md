# 🛍️ Product Card Component with Liquid Morph Button

A modern, responsive product card component featuring an animated "Add to Cart" button with a unique liquid morph hover effect.

## ✨ Features

- **Responsive Design** - Adapts to different screen sizes
- **Liquid Morph Animation** - Smooth, eye-catching hover effect on the button
- **Modern Styling** - Clean, professional design with proper spacing
- **Font Awesome Icons** - Integrated shopping cart icon
- **Smooth Transitions** - Polished cubic-bezier animations

## 🎨 Demo

Hover over the "Add to Cart" button to see the liquid morph effect in action:
- Button rotates slightly
- Animated conic gradient appears
- Smooth morphing transition

## 🚀 Quick Start

1. **Clone the repository**
```bash
git clone https://github.com/Rayflix55/product-card-component.git
cd product-card-component
```

2. **Open in browser**
```bash
# Simply open the HTML file in your browser
open index.html
```

## 📦 Usage

Include the HTML structure in your project:

```html
<button class="btn">
  <i class="fa-solid fa-cart-shopping"></i>
  &nbsp;
  Add to Cart
</button>
```

Make sure to include Font Awesome for the icons:

```html
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
```

## 🎯 Customization

### Colors

Change the button color by modifying the HSL values:

```css
.btn {
    background-color: hsl(158, 36%, 37%); /* Change these values */
}
```

### Animation Speed

Adjust the transition duration:

```css
.btn {
    transition: all 0.6s cubic-bezier(0.68, -0.55, 0.265, 1.55);
    /* Change 0.6s to your preferred speed */
}
```

### Rotation Angle

Modify the hover rotation:

```css
.btn:hover {
    transform: rotate(5deg); /* Adjust the degree */
}
```

## 🛠️ Technologies Used

- HTML5
- CSS3
- Font Awesome 6.4.0

## 📱 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)

## 💡 Features Breakdown

### Button Styling
- Custom green color scheme
- Rounded corners with border-radius
- Subtle box shadow for depth
- Bold, spaced lettering for readability

### Liquid Morph Effect
- Conic gradient animation
- Scale transformation
- Smooth cubic-bezier easing
- Layered z-index for proper stacking

## 🤝 Contributing

Contributions are welcome! Feel free to:

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**Your Name**
- GitHub: [@yourusername](https://github.com/Rayflix55)
- LinkedIn: [Your LinkedIn](www.linkedin.com/in/akpe-samuel-993971329)

## ⭐ Show your support

Give a ⭐️ if you like this project!

## 📝 Acknowledgments

- Inspired by modern e-commerce design trends
- Liquid morph effect concept from creative UI/UX patterns
- Font Awesome for the beautiful icons

---

Made with ❤️ and CSS