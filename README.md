# 🎉 2026: Our Year to Shine

A beautiful, interactive celebration webpage commemorating 2025's journey and welcoming 2026 with hope, resilience, and positivity. Created by **sean_tech_hub**.

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Status](https://img.shields.io/badge/status-active-success.svg)

## 🌟 Features

### 🎨 Visual Excellence
- **Animated Hero Section** with glowing gradient text
- **Real-time Countdown** to January 1, 2026
- **Interactive Highlight Cards** with hover effects and floating emojis
- **Scroll-triggered Animations** for timeline and achievement sections
- **Particle Effects & Balloons** creating a celebratory atmosphere
- **Rotating Shine Effect** on the vision section
- **Floating Sparkles** throughout the page

### 🎵 Audio Experience
- **Background Music Player** with Jimmy Cliff's "Shelter of Your Love"
- **Auto-play Support** with user-friendly overlay
- **Smart Audio Management** - music pauses when video plays
- **Persistent Player Controls** always accessible

### 🎆 New Year Celebration
- **Automatic Fireworks Display** triggers at midnight on January 1, 2026
- **Canvas-based Animation** with realistic particle physics
- **Celebratory Message** with golden glow effects
- **Session-based Display** - shows once per browser session
- **Client-side Detection** - works on static hosting

### 👤 Social Integration
- **Profile Section** with animated avatar
- **TikTok Integration** - clickable link to @tech_hub599
- **Gradient Border** with pulsing glow effect
- **Hover Animations** for enhanced interactivity

### 📱 Responsive Design
- **Fully Mobile Optimized** for all screen sizes
- **Tablet Support** with adaptive layouts
- **Landscape Mode** optimization
- **Touch-friendly** interfaces
- **Performance Optimized** - disabled heavy animations on mobile

### ♿ Accessibility
- **Screen Reader Support** with ARIA labels
- **Reduced Motion Support** for users with motion sensitivity
- **Semantic HTML** structure
- **Keyboard Navigation** friendly

## 🚀 Quick Start

### Installation

1. **Clone or Download** the repository
2. **Place your files** in the project directory:
   - `2026.html` - Main webpage
   - `img.jpeg` - Your profile picture
   - `Jimmy Cliff - Shelter of your Love - lisashenmaid.mp3` - Background music
   - `video.mp4` - (Optional) Memory video

3. **Customize** (optional):
   - Update TikTok link in the JavaScript section
   - Replace profile image
   - Change background music
   - Modify text content

### Deployment

#### Static Hosting (Render, Netlify, Vercel, GitHub Pages)
```bash
# Simply upload all files to your hosting service
# No build process required - pure HTML/CSS/JS
```

#### Local Preview
```bash
# Open 2026.html in any modern browser
# Or use a local server:
python -m http.server 8000
# Then visit: http://localhost:8000/2026.html
```

## 📁 File Structure

```
2025/
├── 2026.html                          # Main webpage
├── img.jpeg                           # Profile picture
├── Jimmy Cliff - Shelter of your Love - lisashenmaid.mp3  # Background music
├── video.mp4                          # (Optional) Video memories
├── README.md                          # This file
├── CHANGELOG.md                       # Version history
└── LICENSE                            # MIT License
```

## 🎯 Usage

### Customization Guide

#### 1. Update Your Profile
```html
<!-- Line ~950 in HTML -->
<img src="your-image.jpg" alt="Your Name" class="profile-image">
<span class="profile-name">Your Name</span>
```

#### 2. Change TikTok Link
```javascript
// Line ~1270 in JavaScript
window.open('https://www.tiktok.com/@your_handle', '_blank');
```

#### 3. Replace Background Music
- Replace the MP3 file with your chosen song
- Update the filename in the audio source tag:
```html
<source src="your-music.mp3" type="audio/mpeg">
```

#### 4. Modify Content
All text content can be edited directly in the HTML:
- Hero section messages
- Timeline stories
- Achievement descriptions
- Vision 2026 content

### Fireworks Feature

The fireworks automatically trigger when:
- User's local time reaches January 1, 2026, 00:00
- Within the first 5 minutes of the new year
- Only displays once per browser session

To test the fireworks manually:
```javascript
// Add this to browser console:
startFireworks();
```

## 🛠️ Technical Details

### Technologies Used
- **HTML5** - Semantic structure
- **CSS3** - Advanced animations and effects
  - Flexbox & Grid layouts
  - CSS animations & transitions
  - Backdrop filters & gradients
  - Media queries for responsiveness
- **Vanilla JavaScript** - No frameworks
  - Canvas API for fireworks
  - Intersection Observer for scroll animations
  - Audio API for music control
  - Date/Time calculations

### Browser Support
- ✅ Chrome/Edge (90+)
- ✅ Firefox (88+)
- ✅ Safari (14+)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

### Performance Features
- Lazy loading animations
- Efficient particle systems
- Mobile-optimized (animations disabled on mobile)
- Minimal dependencies (zero external libraries)

## 🎨 Design Philosophy

This project celebrates:
- **Resilience** - Honoring the struggles of 2025
- **Growth** - Recognizing personal development
- **Hope** - Looking forward to 2026 with optimism
- **Community** - Sharing encouragement with others

Design principles:
- Clean, modern aesthetic
- Vibrant gradient colors (pink, red, gold)
- Smooth, purposeful animations
- User-friendly interactions
- Accessible to all

## 📝 Content Sections

1. **Hero** - Welcome message with countdown
2. **2025 Journey** - Highlight cards celebrating the year
3. **Timeline** - Struggles, breakthroughs, and growth
4. **Victories** - Achievement cards
5. **Vision 2026** - Inspirational message for the new year

## 🤝 Contributing

While this is a personal project, suggestions and improvements are welcome!

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**sean_tech_hub**
- TikTok: [@tech_hub599](https://www.tiktok.com/@tech_hub599)
- Project: 2026: Our Year to Shine

## 🙏 Acknowledgments

- Music: "Shelter of Your Love" by Jimmy Cliff
- Inspiration: Everyone who persevered through 2025
- Design: Modern web design trends and glass-morphism

## 📞 Support

For questions or issues:
1. Check the [CHANGELOG](CHANGELOG.md) for version updates
2. Review this README for usage instructions
3. Reach out via TikTok @tech_hub599

## ⭐ Show Your Support

If this project inspired you:
- Give it a star ⭐
- Share it with others 🌟
- Follow on TikTok 📱
- Create your own version 🎨

---

**Made with ❤️ by sean_tech_hub**

*Let's make 2026 legendary! 🚀*
