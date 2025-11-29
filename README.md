# mrzxn - Personal Portfolio Website

A stunning dark-themed portfolio website built with **pure HTML & CSS** (minimal JavaScript for games only).

---

## ✨ Features

### 🧭 Navigation Bar
- **Sticky Navigation** - Fixed at top, always accessible while scrolling
- **Smooth Scrolling** - Elegant transitions between sections
- **5 Navigation Links**:
  - **About** - Your bio and introduction
  - **Connect** - Social media links
  - **Projects** - Collaboration opportunities
  - **Gallery** - Your photo collection (4 images)
  - **Play** - Interactive games
- **Glassmorphism Effect** - Semi-transparent with backdrop blur
- **Hover Effects** - Links light up and lift on hover

### 🎨 Visual Effects
- **Rain Animation** - Falling rain across the screen
- **Grain Texture** - Cinematic film grain overlay
- **City Background** - Animated zoom effect on your cityscape
- **Rotating Ring** - Grey orbital ring around profile picture
- **Typewriter Effect** - Animated typing on name with cursor
- **Glassmorphism Cards** - Frosted glass effects throughout

### 🎭 Interactive Sections
- **🔗 Connect** - All 4 social platforms (Telegram, YouTube, TikTok, Discord)
- **🚀 Projects** - Collaboration message with call-to-action
- **📸 Gallery** - 4 photos in 2x2 grid with zoom hover effects:
  - 🎨 Anime Character Art
  - 📹 DJI Osmo Camera Setup
  - 👟 Nike Sneakers Collection
  - 🏖️ Beach Vibes
- **🎮 Play** - Two interactive games:
  - ❌⭕ Tic-Tac-Toe (full game with win detection)
  - 🎲 Guess the Number (1-100 with hints)

### 🌓 Theme Toggle
- **Dark Mode** (default) - Black/grey aesthetic, mature and professional
- **Light Mode** - Click moon/sun button (top-right) to switch
- **No Cringe Colors** - Clean monochrome design

---

## 🚀 How to Use

1. **Open** `index.html` in any modern browser
2. **Navigate** - Click links in the top navigation bar to jump to sections
3. **Expand Sections** - Click section headers (Connect ▼, Projects ▼, etc.) to expand
4. **Toggle Theme** - Click moon/sun button (top-right) for dark/light mode
5. **View Gallery** - Hover over images to see zoom effect and captions
6. **Play Games** - Expand Play section for Tic-Tac-Toe and Number Guessing

---

## 📦 File Structure

```
mrzxn-website/
├── index.html              # Main website file
├── images/
│   ├── profile.jpeg        # Your profile picture (black & white portrait)
│   ├── city-bg.jpg         # City skyline background
│   ├── gallery1.jpeg       # Anime character art
│   ├── gallery2.jpeg       # DJI Osmo camera
│   ├── gallery3.jpeg       # Nike sneakers
│   └── gallery4.jpeg       # Beach scene
└── README.md              # This file
```

---

## 🎨 Customization

### Change Colors
Edit the CSS variables in `<style>`:
```css
:root {
    --bg-main: #0a0a0a;                    /* Main background */
    --bg-card: rgba(30, 30, 30, 0.85);     /* Card background */
    --text-primary: #e0e0e0;               /* Primary text */
    --text-secondary: #909090;             /* Secondary text */
    --border: rgba(255, 255, 255, 0.08);   /* Borders */
    --accent: #404040;                     /* Accent color */
}
```

### Add More Gallery Images
1. Copy your image to the `images/` folder
2. Add a new gallery item in the HTML:
```html
<div class="gallery-item">
    <img src="images/your-image.jpeg" alt="Description">
    <div class="gallery-caption">🎨 Your Caption</div>
</div>
```

### Update Bio
Find the `<div id="about" class="profile-bio">` section and edit the text.

### Add Social Links
Add more links in the Connect section:
```html
<a href="https://your-link.com" target="_blank" class="social-link">
    🔗 Platform @username
</a>
```

### Add Navigation Links
To add a new section to the navigation:
1. Add a link in the navbar:
```html
<a href="#newsection" class="nav-link">New Section</a>
```
2. Add an ID to your section:
```html
<div id="newsection"></div>
```

---

## 💻 Technical Details

### Technologies
- **HTML5** - Semantic markup with smooth scrolling
- **CSS3** - Advanced animations, gradients, glassmorphism
- **JavaScript** - Minimal (only for game logic)
- **No Dependencies** - No frameworks, no libraries, no build tools

### Browser Compatibility
- ✅ Chrome/Edge (Recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Opera
- ✅ All modern mobile browsers

### Performance
- **Lightning Fast** - No external resources or API calls
- **Lightweight** - Optimized CSS and minimal JavaScript
- **Smooth 60fps Animations** - Hardware-accelerated CSS transforms
- **Mobile Responsive** - Adapts to all screen sizes

---

## 📱 Mobile Responsive

The website automatically adapts to:
- 📱 **Phones** (< 768px) - Single column, stacked gallery
- 💻 **Tablets** (768px - 1024px) - Optimized spacing
- 🖥️ **Desktops** (> 1024px) - Full layout with 2x2 gallery grid

---

## 🎮 Game Instructions

### ❌⭕ Tic-Tac-Toe
- Click any empty cell to place your mark
- Players alternate between X and O
- Get 3 in a row to win (horizontal, vertical, or diagonal)
- Click "Reset Game" to start over

### 🎲 Guess the Number
- Enter a number between 1-100
- Click "Guess" or press Enter
- Follow the hints (too high/too low)
- Try to guess in the fewest attempts
- Click "New Game" to restart

---

## 🎯 Your Information

- **Name**: mrzxn
- **Title**: Developer & Producer 🎵💻
- **Bio**: Vibe coder at the intersection of code and creativity
- **Interests**: Crypto projects, music production, gaming, development
- **Social Links**:
  - 📱 **Telegram**: @Noodle_cup
  - ▶️ **YouTube**: @AnotherLightbro
  - 🎵 **TikTok**: @mrzxn6
  - 💬 **Discord**: @onezdev

---

## 🌟 Complete Feature List

| Feature | Status | Description |
|---------|--------|-------------|
| Sticky Navigation | ✅ | Fixed navbar with smooth scrolling |
| Rain Animation | ✅ | 15 animated raindrops falling continuously |
| Grain Texture | ✅ | Film grain overlay with subtle animation |
| City Background | ✅ | Grayscale cityscape with zoom animation |
| Profile Ring | ✅ | Rotating grey gradient ring around photo |
| Typewriter Effect | ✅ | Name types out with blinking cursor |
| Dark/Light Toggle | ✅ | Switch between themes with moon/sun button |
| Collapsible Sections | ✅ | Smooth expand/collapse animations |
| Social Links | ✅ | 4 platforms with hover effects |
| Gallery | ✅ | 4 photos with zoom and caption overlays |
| Tic-Tac-Toe | ✅ | Full game with win detection |
| Number Guessing | ✅ | 1-100 game with hints and attempts |
| Responsive Design | ✅ | Mobile-friendly adaptive layout |
| Pure CSS UI | ✅ | All visual effects are CSS-only |

---

## 🔧 Troubleshooting

**Navigation not scrolling?**
- Make sure JavaScript is enabled (for smooth scroll behavior)
- Try refreshing the page (Ctrl+F5 or Cmd+Shift+R)

**Images not loading?**
- Ensure `images/` folder is in the same directory as `index.html`
- Check that image files are named correctly

**Animations not smooth?**
- Try Chrome or Edge for best performance
- Close other tabs to free up resources
- Disable browser extensions that might interfere

**Games not working?**
- Make sure JavaScript is enabled in your browser
- Try a different browser if issues persist

---

## 🎉 Credits

**Design & Development**: Custom-built for mrzxn  
**Tech Stack**: HTML5, CSS3, Vanilla JavaScript (games only)  
**Style**: Dark cyberpunk aesthetic with glassmorphism  
**Profile Picture**: Artistic black & white portrait with cat  
**Background**: Nighttime city skyline  

---

## 📄 License

Personal use only. All rights reserved by mrzxn.

---

**Made with ❤️ for mrzxn - The Vibe Coder**

*"Creating cool stuff and pushing boundaries in tech and music"* 🚀
