# Gkash - Financial Literacy Platform

## 🚀 Learn. Invest. Grow.

A modern, responsive landing page for the Gkash mobile application - empowering Kenyan people with financial literacy, smart investment opportunities, and sustainable growth.

## 📌 Project Overview

Gkash is a fintech platform designed to address the financial challenges faced by Kenyan people. The landing page showcases the app's core features and mission to promote financial literacy and responsible money management.

## 🎨 Design Features

- **60-30-10 Color Rule**: Professional color distribution (60% white/light, 30% pink, 10% gold)
- **Dark Mode Support**: Toggle between light and dark themes with user preference saved
- **Modern UI/UX**: Clean, intuitive design with vibrant colors matching the mobile app
- **Responsive Layout**: Fully responsive design that works on all devices
- **Interactive Elements**: Smooth animations and hover effects
- **Mobile-First Approach**: Optimized for mobile viewing
- **Accessibility**: Clear typography and high contrast for better readability

## 🎯 Key Sections

1. **Hero Section**: Eye-catching introduction with the app's slogan
2. **Problem Statement**: Highlights the challenges being addressed
3. **Features**: Three core pillars - Learn, Save, Invest
4. **How It Works**: Step-by-step process guide
5. **Impact**: Showcases the platform's benefits
6. **USSD Platform**: Access for users without smartphones (*710*56789#)
7. **Call to Action**: Download links and engagement prompts

## 🛠️ Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Modern styling with custom properties and animations
- **JavaScript**: Interactive features and smooth scrolling
- **Google Fonts**: Poppins font family for modern typography

## 📂 Project Structure

```
Gkash/
│
├── index.html          # Main HTML file
├── styles.css          # CSS styling
├── script.js          # JavaScript functionality
├── README.md          # Project documentation
│
└── assets/            # Media assets
    ├── logo.svg       # Gkash logo
    ├── logo.png       # PNG version of logo
    ├── app-screen-1.svg  # Learning screen mockup
    ├── app-screen-2.svg  # Chat screen mockup
    └── app-screen-3.svg  # Wallet screen mockup
```

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- Basic web server (optional for local testing)

### Installation

1. Clone or download the project files
2. Open `index.html` in your web browser

### Local Development

To run a local server:

```bash
# Using Python 3
python3 -m http.server 8080

# Using Node.js (if http-server is installed)
npx http-server -p 8080

# Using PHP
php -S localhost:8080
```

Then navigate to `http://localhost:8080` in your browser.

## 🎨 Color Palette

### Light Mode (Default - 60-30-10 Rule)
- **60% Dominant**: #f5f7fa (Soft light background) with white cards
- **30% Secondary**: #E91E63 (Pink accents)
- **10% Accent**: #FFD700 (Gold highlights)

### Dark Mode
- **60% Dominant**: #1a1a1a (Dark background)
- **30% Secondary**: #F48FB1 (Light pink accents)
- **10% Accent**: #FFD700 (Gold highlights)

### Additional Colors
- **Success Green**: #4CAF50
- **Border**: #e0e0e0 (light) / #3a3a3a (dark)
- **Text**: #1a1a1a (light) / #ffffff (dark)

## ✨ Features

### Interactive Elements
- **Dark Mode Toggle**: Switch between light and dark themes with persistent preferences
- Smooth scroll navigation
- Mobile menu toggle
- Animated statistics counter
- App screen carousel
- Hover effects on cards
- Ripple effects on buttons

### Accessibility Features
- **USSD Platform Information**: Clear display of *710*56789# for non-smartphone users
- Light mode default with optional dark mode
- Keyboard navigation support
- Screen reader friendly markup

### Performance
- Optimized images (SVG format)
- Minimal JavaScript
- CSS animations for better performance
- Lazy loading ready

## 📱 Mobile Responsiveness

The landing page is fully responsive with breakpoints at:
- Desktop: > 768px
- Tablet: 768px
- Mobile: < 480px

## 🌓 Dark Mode

The landing page includes a built-in dark mode toggle that users can activate:
- Click the theme toggle button (🌓/☀️) in the navigation bar
- Theme preference is saved in browser localStorage
- Automatically applies user's choice on return visits
- Smooth transitions between themes

### Color Scheme
- **Light Mode**: Clean white background (60%), pink accents (30%), gold highlights (10%)
- **Dark Mode**: Dark background (60%), soft pink accents (30%), gold highlights (10%)

## 🚀 Waitlist Signup

The landing page includes a waitlist signup for early access:
- **Google Form**: https://forms.gle/EnaMCx77TfVJK5jQA
- **Location**: CTA section at bottom of page
- **Button**: "🚀 Join the Waitlist"
- **Opens**: In new tab with proper security attributes

### How It Works:
1. Users click "Join the Waitlist" button
2. Opens Google Form in new tab
3. Users fill out their information
4. Get notified when Gkash launches

## 📞 USSD Platform

For users without smartphones, Gkash is accessible via USSD:
- **Dial**: *710*56789#
- Works on any mobile network
- No internet connection required
- Access balance, savings, and financial tips

## 🔧 Customization

### Changing Colors
Edit the CSS custom properties in `styles.css`:

```css
:root {
    /* Light Mode Colors */
    --bg-primary: #ffffff;
    --color-secondary: #E91E63;  /* 30% - Pink accents */
    --color-accent: #FFD700;     /* 10% - Gold highlights */
    --text-primary: #1a1a1a;
}

[data-theme="dark"] {
    /* Dark Mode Colors */
    --bg-primary: #1a1a1a;
    --color-secondary: #F48FB1;
    --color-accent: #FFD700;
    --text-primary: #ffffff;
}
```

### Modifying Content
- Edit text content in `index.html`
- Update styles in `styles.css`
- Modify interactions in `script.js`

## 📈 Future Enhancements

- [ ] Add real app screenshots
- [ ] Integrate with backend API
- [ ] Add contact form
- [ ] Implement newsletter subscription
- [ ] Add testimonials section
- [ ] Include team members section
- [ ] Add blog/resources section
- [ ] Implement multi-language support

## 👥 Target Audience

- Kenyan university students
- Young professionals
- People seeking financial literacy
- Anyone interested in smart saving and investing

## 📄 License

This project is part of the Gkash financial literacy platform.

## 📞 Contact

For more information about Gkash:
- Email: itsgkash@gmail.com
- YouTube: https://www.youtube.com/@itsgkash
- Waitlist: https://forms.gle/EnaMCx77TfVJK5jQA

---

**Built with ❤️ for Kenyan Financial Empowerment**
