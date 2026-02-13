# 🌈⚡ Cyberpunk Smart Alarm Clock ⚡🌈

A **fully-featured smart alarm clock** with cyberpunk aesthetics, weather tracking, financial data, animated companions, and more! Built as a single HTML file for easy deployment to GitHub Pages.

![Cyberpunk Aesthetic](https://img.shields.io/badge/Style-Cyberpunk-ff006e?style=for-the-badge)
![Screen Size](https://img.shields.io/badge/Screen-480x800-00f5ff?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Production-39ff14?style=for-the-badge)

---

## ✨ Features

### ⏰ **Alarm Clock** (New!)
- **Set unlimited alarms** with custom times and labels
- **Snooze function** (5 minutes)
- **Toggle alarms on/off** with cyberpunk switches
- **Persistent storage** - alarms survive page refresh
- **Full-screen ringing overlay** with audio alert
- Uses Nedry "ah ah ah!" sound (ahahah.mp3)

### 🕐 **Time & Date**
- Large cyberpunk clock display (68px Orbitron font)
- 12/24 hour format toggle
- RGB chromatic aberration effect
- Animated holographic gradients
- Date display with neon green styling

### 🌤️ **Weather**
- **Live weather data** via OpenWeatherMap API
- Current temperature and conditions
- 5-day forecast with weather icons
- **Live weather radar** (click-to-load)
- Weather-based visual effects (rain, snow, wind)
- **Emergency weather alerts** with audio warnings
- ZIP code customizable

### 💰 **Financial Data**
- **Bitcoin price** (CoinGecko API)
- **Stock prices** (AlphaVantage + Yahoo Finance fallback)
- Real-time updates (1-minute intervals)
- Customizable stock symbol (default: NVDA)
- Large, readable prices (20px font)

### 🛰️ **Weather Radar**
- **Interactive map** with RainViewer overlay
- Click 🛰️ button to load
- Auto-refreshes every 5 minutes when active
- Purple neon border with "RADAR SCAN" label
- Cyberpunk color-shifted map

### 🎮 **Games & Entertainment**
- **Tetris** - Full playable game with scoring
- **Wolfenstein 3D** - Embedded classic FPS
- **Matrix effect** - Falling code animation
- **Carrot rain** - Easter egg effect
- **Nedry Easter Egg** - "Ah ah ah!" GIF + audio

### 🦊🐰🐕 **Animated Companions**
- **Fox** - Walks, wags tail, animated legs
- **Bunny** - Hops with twitching ears
- **Dog** - Bounces with floppy ears
- **Give treats** - All companions celebrate together!
- Hover for speech bubbles
- Floating treat emojis (🥤🥕🦴)

### 📰 **News & Media**
- **Google News ticker** - Scrolling headlines
- **CNBC Live Stream** - Click 📺 to watch
- **Spotify Player** - Embedded music (Juice WRLD playlist)

### 🎨 **Visual Effects**
1. **CRT Scan Lines** - Retro monitor effect
2. **Chromatic Aberration** - RGB color split on clock
3. **Data Particles** - Floating binary code (30 particles)
4. **Cyberpunk Corners** - Neon bracket accents on panels
5. **Holographic Borders** - Rainbow animated borders
6. **Glass Panels** - Frosted glass overlays on sections
7. **VHS Distortion** - Edge color bleeding

### 🌙 **Night Mode (E-Ink Display)**
- **Black background, white text** for easy night reading
- High contrast (pure #000000 / #ffffff)
- **Removes all effects** (no scan lines, particles, glows)
- Grayscale inverted icons and companions
- Perfect for OLED battery saving
- Eye strain reduction

### ⚙️ **Customization**
- **Settings modal** with all configurations
- ZIP code for weather location
- Stock symbol selection
- Time format (12/24hr)
- API key management
- Debug panel for monitoring

---

## 🚀 Quick Start

Local Testing

1. **Download the files**
2. **Open in browser:**
   ```bash
   # Double-click index.html, or:
   python -m http.server 8000
   # Then visit: http://localhost:8000
   ```

---

## 📱 Recommended Setup

**Ideal Display:**
- **480×800 portrait touchscreen** (like Raspberry Pi displays)
- OLED or LCD panel
- Touch-enabled for best experience

**Works on:**
- ✅ Desktop browsers (Chrome, Firefox, Edge, Safari)
- ✅ Mobile browsers (responsive)
- ✅ Raspberry Pi with touchscreen
- ✅ Tablets in portrait mode

---

## 🔑 API Keys & Configuration

### Free APIs Used (No Credit Card Required)

| Service | Purpose | Free Tier | Get Key |
|---------|---------|-----------|---------|
| **OpenWeatherMap** | Weather data | Unlimited | [Get Key](https://openweathermap.org/api) |
| **AlphaVantage** | Stock prices | 25 calls/day | [Get Key](https://www.alphavantage.co/support/#api-key) |
| **CoinGecko** | Bitcoin price | Unlimited | No key needed |
| **Yahoo Finance** | Stock fallback | Unlimited | No key needed |
| **RainViewer** | Radar tiles | Unlimited | No key needed |

### Setup API Keys

1. Click **⚙️ Settings** button
2. Enter your API keys:
   - OpenWeatherMap API Key: `` (default)
   - AlphaVantage API Key: `` (default)
3. Set your ZIP code (default: 63090)
4. Set your stock symbol (default: NVDA)
5. Click **Save**

---

## 🎮 Controls & Buttons

### Top-Left Controls (2×2 Grid)
- ⚙️ **Settings** - Configure app
- ⏰ **Alarms** - Manage alarms
- ☀️🌙 **Night Mode** - Toggle e-ink mode
- 🐞 **Debug** - Show debug panel

### Top-Right Controls (2×2 Grid)
- 🛰️ **Radar** - Toggle weather radar
- 📺 **Stocks** - (Reserved)
- 📰 **News** - Toggle news ticker
- 🥕 **Carrot Rain** - Easter egg

### Bottom Controls (4×2 Grid)
- 🎮 **Tetris** - Play game
- 🔫 **Wolf3D** - Play FPS
- 💻 **Matrix** - Toggle effect
- 🎵 **Music** - Spotify player
- 🦴 **Treat** - Give all companions treats
- 🥤 **Dew** - Give fox Mountain Dew
- 📺 **CNBC** - Live news stream
- 😂 **Ahahah** - Nedry easter egg

---

## ⏰ How to Use Alarms

1. **Click ⏰ button** (top-left)
2. **Set time** using the time picker
3. **Add label** (optional): "Wake up!", "Meeting", etc.
4. **Click "Add Alarm"**
5. **Toggle switch** to enable/disable
6. **Delete** with ✕ button

### When Alarm Rings:
- Full-screen overlay appears
- Audio plays (loops until dismissed)
- Two options:
  - **Snooze** (5 minutes)
  - **Dismiss** (stops alarm)

---

## 🎨 Cyberpunk Aesthetic

### Color Palette
```css
--neon-pink: #ff006e
--neon-cyan: #00f5ff
--neon-purple: #bf00ff
--neon-green: #39ff14
--neon-yellow: #ffea00
--dark-bg: #0a0015
```

### Typography
- **Display**: Orbitron (futuristic, bold)
- **Body**: Rajdhani (clean, technical)
- All text has neon glows and shadows

### Visual Effects Stack
1. Holographic animated backgrounds
2. CRT scan lines overlay
3. Data stream particles (30 binary floaters)
4. Cyberpunk corner brackets
5. Glass panel overlays
6. RGB chromatic aberration
7. VHS edge distortion

---

## 🌙 Night Mode (E-Ink)

Toggle with ☀️🌙 button for **true dark mode**:

**Features:**
- Pure black background (#000000)
- Pure white text (#ffffff)
- All effects disabled
- Grayscale inverted elements
- High contrast for readability
- Paper grain texture overlay
- Perfect for nighttime bedside use

---

## 🔧 Customization

### Change Default Location
Edit in Settings or modify in code:
```javascript
const CONFIG = {
  DEFAULTS: {
    zip: '63090',      // Your ZIP code
    stock: 'NVDA',     // Your stock
    timeFormat: '12hr' // or '24hr'
  }
};
```

### Change Alarm Sound
Replace `ahahah.mp3` with your own audio file, or update:
```javascript
function playAlarmSound() {
  alarmAudio = new Audio('your-sound.mp3');
  alarmAudio.loop = true;
  alarmAudio.play();
}
```

### Add More Stocks
Modify the financial section to track multiple stocks.

---

## 📊 Technical Details

### File Structure
```
cyberpunk-clock/
├── index.html      # Complete app (self-contained)
├── ahahah.mp3      # Alarm & easter egg audio
├── ahahah.gif      # Nedry easter egg GIF
└── README.md       # This file
```

### Dependencies (CDN)
- jQuery 3.6.0
- Moment.js 2.29.1
- Leaflet 1.7.1 (for maps)

### Browser Storage
- **localStorage** for:
  - Settings (ZIP, stock, time format, API keys)
  - Alarms (persistent across sessions)
  - User preferences

### Performance
- Single HTML file (~3900 lines)
- Minimal external dependencies
- Optimized animations (CSS-only when possible)
- Lazy-loaded iframes (games, music, news)

---

## 🐛 Troubleshooting

### Alarms Not Ringing
- ✅ Check alarm is enabled (toggle switch green)
- ✅ Ensure time is correct (uses 24hr internally)
- ✅ Check browser didn't block audio (autoplay policy)
- ✅ Verify `ahahah.mp3` is in same directory

### Weather Not Loading
- ✅ Check API key is valid
- ✅ Verify ZIP code is correct (US 5-digit)
- ✅ Check browser console for errors
- ✅ Try refreshing the page

### Radar Not Loading
- ✅ Click 🛰️ button to initialize
- ✅ Check coordinates are valid
- ✅ Look for "ERROR: Invalid location" message
- ✅ Check browser console for Leaflet errors

### Stock Prices Not Updating
- ✅ AlphaVantage has 25/day limit (may hit limit)
- ✅ Yahoo Finance is automatic fallback
- ✅ Check "Yahoo" indicator if using fallback
- ✅ Get your own free AlphaVantage key

### Audio Not Playing
- ✅ Browser may block autoplay - click page first
- ✅ Check `ahahah.mp3` exists in root directory
- ✅ Verify file is valid MP3 format
- ✅ Check browser console for errors

---

## 🚀 Future Enhancements

Potential features to add:
- [ ] Multiple alarm sounds
- [ ] Recurring alarms (daily, weekdays, etc.)
- [ ] Custom color themes
- [ ] More companion animals
- [ ] Weather-based animations
- [ ] Voice control
- [ ] PWA support (installable)
- [ ] Offline mode
- [ ] Calendar integration
- [ ] Multiple time zones

---

## 📄 License

**MIT License** - Free to use, modify, and distribute

---

## 🙏 Credits

**APIs & Services:**
- OpenWeatherMap (weather data)
- AlphaVantage (stock data)
- CoinGecko (crypto data)
- RainViewer (radar tiles)
- Google News (RSS feeds)
- Leaflet (mapping library)

**Fonts:**
- Orbitron (Google Fonts)
- Rajdhani (Google Fonts)

**Audio/Visual:**
- Jurassic Park (Nedry "ah ah ah!")
- Various neon/cyberpunk inspirations

---

## 💜 Enjoy Your Cyberpunk Clock!

**Questions? Issues? Suggestions?**
- Open an issue on GitHub
- Check browser console for errors
- Verify all 3 files are uploaded

**Made with ⚡ and lots of neon 🌈**

---

**Version:** 2.0.0  
**Last Updated:** February 2026  
**Screen Size:** 480×800 (Portrait)  
**Mode:** Cyberpunk Acid / E-Ink Dark
