# Project: Jordan Jumpman 2021 PF | Interactive Showcase

<div align="center">
  
![Jordan Shoes](https://img.shields.io/badge/Jordan-Jumpman_2021-EB0000?style=for-the-badge&logo=nike&logoColor=white)
![Status](https://img.shields.io/badge/Status-Live-00C853?style=for-the-badge)
![Version](https://img.shields.io/badge/Version-1.0.0-blue?style=for-the-badge)

**🏀 Premium Interactive E-Commerce Experience**

[🌐 Live Demo](https://thearchitect099.github.io/jurdan-jumpman/) • [📖 Documentation](#features)

</div>

---

## 🛠️ Tech Stack

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-222222?style=for-the-badge&logo=github&logoColor=white)

---

## ✨ Features

### 🎬 Interactive Slider System
- **5 Color Variants** with unique product data (Red, Blue, White, Green, Purple)
- **Auto-play functionality** with smooth 5-second transitions
- **Smart pause** on user interaction
- **Dynamic content updates** - price, title, description, badge changes per slide
- **Multiple navigation methods:**
  - 🖱️ Navigation dots (right side)
  - ⬅️➡️ Arrow buttons (keyboard & on-screen)
  - 👆 Touch swipe gestures (mobile-optimized)
  - 🎨 Color selector integration

### 🛒 Shopping Cart Experience
- **Add to Cart** with visual feedback and notifications
- **Dynamic cart counter** with animated badge
- **Product info display** in cart notifications
- **Quick Buy** modal window with checkout simulation
- **Persistent cart state** tracking

### 🎨 Advanced Visual Effects
- **Parallax scrolling** - elements respond to mouse movement
- **Ripple effect** on button clicks
- **Sequential page load** animations
- **Smooth transitions** between all states
- **Glow effects** on interactive elements
- **Scale & pulse** animations on hover

### 📱 Responsive Design
- **100% viewport** coverage - full-screen experience
- **Proportional scaling** across all screen sizes
- **Mobile-optimized** touch controls
- **Adaptive typography** using `clamp()` functions
- **Flexible layouts** with CSS Grid & Flexbox

### 🎯 User Experience
- **Toast notifications** system (success, info, warning)
- **Modal windows** for checkout process
- **Loading animations** for smooth page entry
- **Scroll progress indicator** at top of page
- **Keyboard accessibility** - arrow keys navigation
- **Visual feedback** on all interactions

---

## 🎨 Visual Design

### Color Palette
```css
Primary Red:    #EB0000, #E70000
Background:     #FFFFFF
Text:           #FFFFFF
Accents:        #000000
Shadow:         rgba(0, 0, 0, 0.15)
```


## 📸 Screenshots

<img width="1917" height="1080" alt="jordan" src="https://github.com/user-attachments/assets/5d2bc0e0-7a22-4b21-bbab-cf4a822b4671" />


### Typography
- **Headings & Navigation:** Bebas Neue (Monument Extended alternative)
- **Body Text:** Roboto
- **Badges:** Roboto Condensed

### Design Features
- **Dark dramatic backgrounds** with premium product photography
- **Smooth CSS transitions** with cubic-bezier easing
- **Backdrop blur effects** for modern glass-morphism
- **CSS filters** for color variations (hue-rotate, saturate, brightness)
- **Box shadows** for depth and elevation
- **Gradient overlays** for premium feel

---

## 🎯 Product Variants

| Color | Name | Price | Badge | Description |
|-------|------|-------|-------|-------------|
| 🔴 Red | JORDAN JUMPMAN 2021 PF | $134 | exclusive | Original design inspired by latest Air Jordan game shoe |
| 🔵 Blue | JORDAN JUMPMAN 2021 BLUE | $139 | limited | Stunning blue edition for standout court presence |
| ⚪ White | JORDAN JUMPMAN 2021 CLASSIC | $129 | bestseller | Timeless white edition combining classic & modern |
| 🟢 Green | JORDAN JUMPMAN 2021 FRESH | $144 | new | Fresh green with eco-friendly materials |
| 🟣 Purple | JORDAN JUMPMAN 2021 ROYAL | $149 | exclusive | Royal purple for premium craftsmanship |

---

## 🚀 Performance Features

### Optimizations
- **Hardware-accelerated animations** (transform, opacity)
- **RequestAnimationFrame** for smooth parallax
- **Debounced events** for performance
- **Minimal DOM manipulation** for speed
- **Efficient event delegation**
- **Lazy loading ready** structure

### Browser Support
- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

---

## 📱 Responsive Breakpoints

```css
Desktop (1920px+):    Maximum size limits applied
Standard (1024-1920): Perfect proportions maintained  
Tablet (768-1024):    Adaptive element sizing
Mobile (<768px):      Touch-optimized interface
```

---

## 🎮 Interactive Controls

### Keyboard Shortcuts
- `←` Previous slide
- `→` Next slide

### Touch Gestures
- **Swipe Left:** Next slide
- **Swipe Right:** Previous slide

### Mouse Controls
- **Hover:** Pause auto-play
- **Click dots:** Navigate to specific slide
- **Click arrows:** Navigate slides
- **Click shoes:** Jump to color variant

---

## 🌟 Animation Catalog

| Animation | Usage | Duration |
|-----------|-------|----------|
| fadeInDown | Header entrance | 0.8s |
| fadeInUp | Product info, buttons | 1s |
| fadeInLeft | Color selector | 1s |
| fadeInRight | Pricing, nav dots | 1s |
| scaleIn | Badges, modals | 0.5s |
| pulse | Button hover state | 0.6s |
| slideIn/Out | Notifications | 0.3s |
| ripple | Button clicks | 0.6s |

---

## 📂 Project Structure

```
jurdan-jumpan/
│
├── index.html              # Main HTML structure
├── .gitignore             # Git exclusions
│
├── css/
│   └── styles.css         # All styles (863 lines)
│
├── js/
│   └── script.js          # All functionality (597 lines)
│
└── images/                # Assets
    ├── background.png     # Main product photo
    ├── avatar-22f719.png  # User avatar
    ├── jumpman-logo.svg   # Jordan brand logo
    ├── nike-logo.svg      # Nike swoosh
    ├── search-icon.svg    # Search functionality
    ├── cart-icon.svg      # Shopping cart
    ├── navigation-bar.svg # UI element
    └── shoes-colors.svg   # Color selection strip
```

---

## 🎯 Future Enhancements

- [ ] Backend integration for real cart functionality
- [ ] User authentication system
- [ ] Product comparison feature
- [ ] 360° product view
- [ ] Size selection system
- [ ] Wishlist functionality
- [ ] Product reviews & ratings
- [ ] Related products carousel
- [ ] Search functionality
- [ ] Filter & sort options

---

## 📄 License

This project is a showcase/portfolio piece inspired by Nike Jordan brand design.

---

## 👨‍💻 Developer

Created with ❤️ for the love of premium web experiences and basketball culture.

**Jordan Jumpman 2021 PF** - Where design meets performance on the digital court.

---

<div align="center">

**[⬆ Back to Top](#project-jordan-jumpman-2021-pf--interactive-showcase)**

Made with 🏀 and ⚡

</div>

