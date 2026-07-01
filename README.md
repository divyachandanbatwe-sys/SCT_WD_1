# SCT_WD_1
*README.md*
# Responsive Landing Page - SkillCraft Task 01

A modern, fully responsive landing page with an interactive fixed navigation menu built using HTML, CSS, and vanilla JavaScript.

## 🚀 Features

- **Fixed Navigation Bar**: Stays visible on all pages/sections while scrolling
- **Scroll Effect**: Navbar changes background color and padding when user scrolls >50px
- **Hover Animations**: Menu items change color and show animated underline on hover
- **Mobile Responsive**: Hamburger menu for screens <768px with slide-down animation
- **Smooth Scrolling**: Click nav links for smooth scroll to sections
- **Clean UI**: Dark theme with blue accents, modern typography
- **Single File**: No external dependencies - just HTML, CSS, and JS


## 🛠️ Tech Stack

- **HTML5**: Semantic structure
- **CSS3**: Flexbox, transitions, media queries, gradients
- **JavaScript**: DOM manipulation, scroll events, mobile menu toggle

## 📁 Project Structure

landing-page/
│
└── http://index.html    # Complete app - HTML + CSS + JS in one file

## 🔧 How to Run

1. Download or copy the `home01.html` file
2. Open it in any modern web browser
3. No build tools or installations needed

## 💡 How It Works

### Navbar Scroll Effect
```javascript
window.addEventListener('scroll', () => {
    if (window.scrollY > 50) {
        navbar.classList.add('scrolled');
    } else {
        navbar.classList.remove('scrolled');
    }
});
Adds `.scrolled` class to change navbar background from transparent to `#1e293b` after 50px scroll.

### Mobile Menu
hamburger.addEventListener('click', () => {
    navLinks.classList.toggle('active');
});
Toggles `.active` class to slide mobile menu down. Menu auto-closes when a link is clicked.

### Hover Effect
Uses CSS `::after` pseudo-element to create animated underline that expands from 0 to 100% width on hover.


### Change Breakpoint
Modify `@media (max-width: 768px)` to your preferred mobile breakpoint.
##Author
Divya kashiram chandanbatwe 

*SkillCraft Technology* | Task 01 - Responsive Landing Page
