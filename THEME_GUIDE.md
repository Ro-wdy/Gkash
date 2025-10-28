# Gkash Color Theme Guide

## 🎨 60-30-10 Color Rule Explained

The 60-30-10 rule is a professional design principle that creates visual harmony by distributing colors in specific proportions:

### The Rule
- **60%** = Dominant Color (Backgrounds, largest surfaces)
- **30%** = Secondary Color (Supporting elements, accents)
- **10%** = Accent Color (Call-to-action, highlights, special elements)

---

## 🌞 Light Mode Theme (Default)

### Color Distribution

#### 60% - Dominant White/Light
**Used for:**
- Main page backgrounds (`--bg-primary: #ffffff`)
- Card backgrounds (`--bg-secondary: #f8f9fa`)
- Large surface areas
- Content containers

**Why:** Creates a clean, professional, and easy-to-read interface. White provides maximum contrast for text and reduces eye strain.

#### 30% - Secondary Pink
**Used for:**
- Navigation buttons (`--color-secondary: #E91E63`)
- Section headings and titles
- Interactive elements (hover states)
- Links and CTAs
- Feature card top borders
- Icon colors

**Why:** The pink represents the Gkash brand identity and draws attention to important interactive elements without overwhelming the page.

#### 10% - Accent Gold
**Used for:**
- Hero title gradient (`--color-accent: #FFD700`)
- Important statistics
- Special highlights
- Success indicators
- Checkmarks in lists
- USSD code box

**Why:** Gold creates a premium feel and highlights the most critical elements that need immediate attention.

### Additional Colors
- **Text Primary**: #1a1a1a (Dark gray for readability)
- **Text Secondary**: #6c757d (Medium gray for less important text)
- **Borders**: #e0e0e0 (Subtle separation)
- **Shadows**: rgba(0, 0, 0, 0.1) (Depth and elevation)

---

## 🌙 Dark Mode Theme

### Color Distribution

#### 60% - Dominant Dark
**Used for:**
- Main page backgrounds (`--bg-primary: #1a1a1a`)
- Card backgrounds (`--bg-secondary: #2a2a2a`)
- Large surface areas
- Content containers

**Why:** Reduces eye strain in low-light conditions, saves battery on OLED screens, and provides a modern aesthetic.

#### 30% - Secondary Light Pink
**Used for:**
- Navigation buttons (`--color-secondary: #F48FB1`)
- Section headings and titles
- Interactive elements (hover states)
- Links and CTAs
- Feature card top borders

**Why:** Lighter pink maintains brand identity while ensuring visibility against dark backgrounds. Softer than the light mode pink to prevent harsh contrast.

#### 10% - Accent Gold
**Used for:**
- Same as light mode (`--color-accent: #FFD700`)
- Gold works in both themes
- Maintains consistency

**Why:** Gold has high contrast in both light and dark modes, making it perfect for maintaining visual hierarchy.

### Additional Colors
- **Text Primary**: #ffffff (White for readability)
- **Text Secondary**: #b0b0b0 (Light gray for less important text)
- **Borders**: #3a3a3a (Subtle separation in dark mode)
- **Shadows**: rgba(0, 0, 0, 0.3) (Depth and elevation)

---

## 🎯 Where Each Color Appears

### Navigation Bar
- **Background**: 60% (White/Dark)
- **Links**: Text color
- **Get Started Button**: 30% Pink gradient
- **Theme Toggle**: Border with hover effect

### Hero Section
- **Background**: 60% (White/Dark)
- **"Learn. Save. Invest."**: 10% Gold gradient
- **Subtitle**: 30% Pink
- **Primary Button**: 30% Pink gradient
- **Secondary Button**: 30% Pink border
- **Statistics Numbers**: 10% Gold

### Problem/Features/Impact Cards
- **Card Background**: 60% (White/Dark with slight tint)
- **Card Borders**: Subtle borders
- **Headings**: 30% Pink
- **Top Border Accent**: 30% Pink / 10% Gold (varies by card)
- **Checkmarks**: 10% Gold

### USSD Section
- **Background**: 60% (Secondary background)
- **Code Box**: 30% Pink gradient
- **Code Text**: White (high contrast)
- **Checkmarks**: 10% Gold
- **Note Box**: 10% Gold accent border

### CTA Section
- **Background**: 30% Pink gradient (exception - needs high impact)
- **Buttons**: 60% White background on pink
- **Text**: White

### Footer
- **Background**: 60% (Secondary background)
- **Headings**: 30% Pink
- **Links**: Text secondary
- **Hover**: 30% Pink

---

## 💡 Design Principles Applied

### Visual Hierarchy
1. **Most Important** (10% Gold): Hero title, stats, special highlights
2. **Important** (30% Pink): CTAs, headings, interactive elements
3. **Supporting** (60% White/Dark): Content, backgrounds, structure

### Consistency
- Pink always used for interactive elements
- Gold always used for premium highlights
- White/Dark always used for structure

### Balance
- No color overwhelms the design
- Each color has a clear purpose
- Easy to scan and navigate

### Accessibility
- High contrast ratios in both modes
- Text remains readable
- Important elements stand out

---

## 🔧 How to Modify Colors

### Change Primary Colors
Edit in `styles.css` (lines 3-27):

```css
:root {
    --bg-primary: #ffffff;        /* Change dominant color */
    --color-secondary: #E91E63;    /* Change secondary color */
    --color-accent: #FFD700;       /* Change accent color */
}
```

### Change Dark Mode Colors
Edit in `styles.css` (lines 29-49):

```css
[data-theme="dark"] {
    --bg-primary: #1a1a1a;         /* Change dark dominant */
    --color-secondary: #F48FB1;    /* Change dark secondary */
    --color-accent: #FFD700;       /* Change dark accent */
}
```

### Keep the 60-30-10 Rule
When changing colors:
1. **Dominant** should be neutral (white, gray, dark)
2. **Secondary** should be your brand color (bold, visible)
3. **Accent** should be contrasting and eye-catching

---

## 📊 Color Usage Statistics

Approximately in the design:
- **60%** = White/Dark backgrounds across all sections
- **30%** = Pink in buttons, borders, headings, CTAs
- **10%** = Gold in titles, stats, highlights, special elements

This creates a balanced, professional design that guides user attention effectively.

---

## 🎨 Quick Reference

### Light Mode
```
Dominant (60%):  ████████████████████████ White
Secondary (30%): ████████████ Pink
Accent (10%):    ████ Gold
```

### Dark Mode
```
Dominant (60%):  ████████████████████████ Dark
Secondary (30%): ████████████ Light Pink
Accent (10%):    ████ Gold
```

---

## ✅ Best Practices

1. **Always maintain the ratio** - Don't let one color dominate more than intended
2. **Use accent sparingly** - 10% should truly be special elements
3. **Keep text readable** - Ensure proper contrast ratios
4. **Test both modes** - Colors should work in light and dark
5. **Be consistent** - Use same colors for similar elements

---

**Remember**: The 60-30-10 rule is a guideline, not a strict law. The goal is visual harmony and clear hierarchy!
