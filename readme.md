# 😂 Jokster

**Your Daily Dose of Laughter** - A premium joke application with a sleek, cinematic dark interface built with vanilla JavaScript.

![Version](https://img.shields.io/badge/version-2.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![JavaScript](https://img.shields.io/badge/javascript-ES6+-yellow.svg)

## 🌟 Overview

Jokster is a modern, feature-rich web application that delivers jokes with style. Designed with a minimal, user-friendly interface inspired by contemporary design principles, it offers a premium experience for joke enthusiasts.

## ✨ Features

### Core Functionality
- **🎲 Random Joke Generator** - Instant laughs with one click
- **📂 Category Filtering** - Browse jokes by type (General, Programming, Knock-Knock, Dad Jokes)
- **⭐ Favorites System** - Save your favorite jokes for later enjoyment
- **🔍 Search Favorites** - Quickly find saved jokes with instant search
- **📜 View History** - Track your recently viewed jokes (last 10)
- **📊 Statistics Tracking** - Monitor jokes viewed and favorites count

### Advanced Features
- **🔊 Text-to-Speech** - Listen to jokes with customizable voice options
- **📋 Copy to Clipboard** - Share jokes easily with one click
- **📱 Native Share** - Use device sharing on supported platforms
- **👍👎 Rating System** - Rate jokes with thumbs up/down feedback
- **⌨️ Keyboard Shortcuts** - Navigate efficiently with hotkeys
- **💾 Session Storage** - Data persists during your browsing session

## 🎨 Design Philosophy

### Premium Cinematic Experience
- **Minimal & Clean** - Distraction-free interface focused on content
- **Dark Theme** - Eye-friendly design optimized for extended viewing
- **Smooth Animations** - Fluid transitions and micro-interactions
- **Apple-Inspired** - Modern design language following industry leaders
- **Fully Responsive** - Seamless experience across all devices

### Technical Excellence
- **Zero Dependencies** - Pure vanilla JavaScript (no frameworks)
- **Lightweight** - ~100KB total file size
- **Fast Loading** - Sub-second load times
- **Modern APIs** - Leverages Web Speech, Clipboard, and Share APIs
- **Progressive Enhancement** - Works on older browsers with graceful fallbacks

## 🚀 Quick Start

### Installation

1. **Clone or Download**
   ```bash
   git clone https://github.com/yourusername/jokster.git
   cd jokster
   ```

2. **Open in Browser**
   ```bash
   # macOS
   open index.html
   
   # Linux
   xdg-open index.html
   
   # Windows
   start index.html
   ```

That's it! No build process, no npm install, no dependencies.

### Project Structure
```
jokster/
├── index.html          # Main HTML structure
├── styles.css          # Complete styling (cinematic theme)
├── script.js           # Application logic (400+ jokes included)
├── README.md           # This file
└── LICENSE             # MIT License
```

## ⌨️ Keyboard Shortcuts

Boost your productivity with these keyboard shortcuts:

| Shortcut | Action |
|----------|--------|
| `Enter` | Get a new random joke |
| `F` | Toggle favorite on current joke |
| `C` | Copy current joke to clipboard |
| `S` | Share current joke |
| `T` | Read joke aloud (Text-to-Speech) |
| `→` | Cycle to next category |
| `?` | Show keyboard shortcuts help |

## 📖 Usage Guide

### Getting Started
1. **View a Joke** - Click "Get New Joke" button or press `Enter`
2. **Filter by Category** - Select a category from the dropdown menu
3. **Add to Favorites** - Click the heart icon (♥) or press `F`
4. **Listen to Jokes** - Click the speaker icon (🔊) to hear jokes read aloud

### Managing Favorites
- **Add/Remove** - Click heart icon on any joke
- **Search** - Type in the search box to filter favorites instantly
- **View** - Click any favorite to display it
- **Remove** - Click the × button on individual favorites
- **Clear All** - Use "Clear All" button to remove all favorites at once

### History Feature
- **Automatic Tracking** - Last 10 jokes are saved automatically
- **Quick Access** - Click any joke in history to view it again
- **Session-Based** - History resets when browser tab is closed

### Voice Options
- **Customizable** - Choose from available system voices
- **Language Support** - Voices available in multiple languages
- **Voice Selection** - Dropdown appears after first TTS use

## 🛠️ Technical Details

### Technologies Used
- **HTML5** - Semantic markup for accessibility
- **CSS3** - Custom properties, Grid, Flexbox, animations
- **Vanilla JavaScript** - ES6+ features, modern syntax
- **Web Speech API** - Text-to-Speech functionality
- **Clipboard API** - One-click copy functionality
- **Web Share API** - Native device sharing

### Browser Compatibility

| Browser | Version | Support |
|---------|---------|---------|
| Chrome/Edge | Latest | ✅ Full support |
| Firefox | Latest | ✅ Full support |
| Safari | Latest | ✅ Full support |
| Opera | Latest | ✅ Full support |

**Note:** Text-to-Speech and Share features may have limited support on older browsers.

### Data Storage
The application uses **in-memory storage** during your session:

- **Favorites** - Your saved jokes (session-only)
- **History** - Last 10 viewed jokes
- **Statistics** - Jokes viewed count

**Important:** All data is cleared when you close the browser tab. This is by design to ensure privacy and fresh sessions.

## 🎨 Customization

### Changing the Color Scheme

Edit CSS variables in `styles.css`:

```css
:root {
    /* Primary Colors */
    --accent: #0071e3;        /* Main accent color */
    --success: #30d158;       /* Success states */
    --danger: #ff453a;        /* Delete/remove actions */
    
    /* Backgrounds */
    --bg-main: #000000;       /* Main background */
    --bg-card: #1c1c1e;       /* Card backgrounds */
    --bg-elevated: #2c2c2e;   /* Elevated surfaces */
    
    /* Text Colors */
    --text-primary: #ffffff;     /* Primary text */
    --text-secondary: #ffffffb3; /* Secondary text */
    --text-tertiary: #ffffff80;  /* Tertiary text */
}
```

### Adding New Jokes

Add jokes to the `jokes` array in `script.js`:

```javascript
{
    "type": "general",           // Category
    "setup": "Why did the...?",  // Setup/question
    "punchline": "Because..."    // Punchline/answer
}
```

### Supported Categories
- `general` - General jokes for all audiences
- `programming` - Tech and programming humor
- `knock-knock` - Classic knock-knock jokes
- `dad` - Family-friendly dad jokes

### Adding New Categories

1. Add jokes with your new category type
2. Categories populate automatically from joke data
3. No additional code changes needed!

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

### Ways to Contribute
1. **Add More Jokes** - Expand the joke database
2. **New Features** - Implement new functionality
3. **Bug Fixes** - Report and fix issues
4. **Documentation** - Improve guides and comments
5. **Translations** - Add multi-language support
6. **Themes** - Create new color schemes

### Contribution Process

1. **Fork** the repository
2. **Create** a feature branch
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. **Commit** your changes
   ```bash
   git commit -m 'Add some AmazingFeature'
   ```
4. **Push** to the branch
   ```bash
   git push origin feature/AmazingFeature
   ```
5. **Open** a Pull Request

### Code Style Guidelines
- Use ES6+ JavaScript features
- Follow existing naming conventions
- Comment complex logic
- Test across multiple browsers
- Keep functions small and focused

## 📝 License

This project is licensed under the **MIT License**.

```
MIT License

Copyright (c) 2025 Prince Kumar Jha

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
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## 🐛 Known Issues

- **Voice Loading** - TTS voices may load slowly on first use
- **Desktop Sharing** - Web Share API not supported on desktop browsers
- **Session Storage** - Data clears when browser tab closes (by design)
- **Mobile Keyboards** - Keyboard shortcuts limited on mobile devices

## 🔮 Roadmap & Future Enhancements

### Planned Features
- [ ] **Persistent Storage** - Optional localStorage for data persistence
- [ ] **Dark/Light Toggle** - User-selectable theme switching
- [ ] **Joke Submission** - Community joke contribution system
- [ ] **API Integration** - Connect to external joke APIs
- [ ] **Daily Notifications** - Optional daily joke reminders
- [ ] **Category Expansion** - More joke categories
- [ ] **Multi-language** - Interface translation support
- [ ] **User Accounts** - Cloud sync across devices
- [ ] **Analytics Dashboard** - Rating trends and statistics
- [ ] **Social Features** - Share and discover popular jokes

### Under Consideration
- PWA support for offline functionality
- Audio jokes and sound effects
- Joke of the day feature
- Custom joke collections
- Export favorites to file
- Dark/light/auto theme modes

## 📊 Project Statistics

- **Total Jokes:** 400+
- **Categories:** 4 (General, Programming, Knock-Knock, Dad)
- **File Size:** ~100KB (total)
- **Load Time:** < 1 second
- **Dependencies:** 0 (pure vanilla JavaScript)
- **Lines of Code:** ~1,500
- **Browser Support:** All modern browsers

## 💡 Tips & Tricks

### For Best Experience
- **Use Keyboard Shortcuts** - Much faster than clicking
- **Try Different Voices** - Some voices are funnier for certain jokes
- **Rate Jokes** - Help remember which ones you liked
- **Search Favorites** - Quickly find that joke you want to share
- **Category Filter** - Focus on your favorite joke types

### Performance Tips
- **Clear History** - Refresh page to reset history if needed
- **Manage Favorites** - Remove old favorites to keep list manageable
- **Voice Selection** - Choose faster voices for quicker playback

## 🙏 Acknowledgments

- **Icons** - [Font Awesome](https://fontawesome.com/) for beautiful icons
- **Design Inspiration** - Apple, Spotify, and Netflix design systems
- **Joke Database** - Compiled from various public domain sources
- **Community** - Thanks to all contributors and users

## 📞 Support & Contact

### Get Help
- **Issues** - [GitHub Issues](https://github.com/yourusername/jokster/issues)
- **Discussions** - [GitHub Discussions](https://github.com/yourusername/jokster/discussions)
- **Email** - support@jokster.app

### Connect
- **Twitter** - [@joksterapp](https://twitter.com/joksterapp)
- **Website** - [jokster.app](https://jokster.app)

## ⚡ Performance

### Optimization Features
- **Lazy Loading** - Minimal initial load
- **CSS Animations** - Hardware-accelerated transitions
- **Event Delegation** - Efficient event handling
- **Debounced Search** - Optimized search performance
- **Minimal DOM** - Efficient rendering

### Lighthouse Scores (Target)
- Performance: 95+
- Accessibility: 100
- Best Practices: 95+
- SEO: 100

---

**Made with 😂 by the Jokster Team**

*Keep laughing, keep sharing!*

---

## 🎯 Quick Links

- [Report a Bug](https://github.com/yourusername/jokster/issues/new?template=bug_report.md)
- [Request a Feature](https://github.com/yourusername/jokster/issues/new?template=feature_request.md)
- [View Changelog](CHANGELOG.md)
- [Contributing Guide](CONTRIBUTING.md)

---

**Version 2.0.0** | **Last Updated: December 2024** | **License: MIT**
