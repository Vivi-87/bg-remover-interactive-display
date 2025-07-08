# Canva Display Ad Portfolio

A complete set of interactive HTML5 display ads featuring dynamic animations, star bursts, and responsive layouts optimized for all major advertising platforms.

## 🎯 Available Ad Formats

All formats are fully implemented and ready to use:

- **300×250** (Medium Rectangle) - Most common format
- **160×600** (Skyscraper) - Vertical sidebar placement  
- **300×600** (Half Page) - Large vertical format
- **320×50** (Mobile Banner) - Mobile-optimized banner
- **728×90** (Banner) - Desktop header/footer
- **970×250** (Leaderboard) - Premium desktop placement

## 🚀 Features

- ✅ Interactive animations with star burst effects
- ✅ Purple stars (yellow stars for 320×50 format)
- ✅ Custom cursor tracking with parallax effects
- ✅ Responsive headline sizing based on text length
- ✅ Background remover button with smooth transitions
- ✅ Image sequence animations (1.png → 2.png → 3.png)
- ✅ Hover effects and scale animations
- ✅ One-time animation sequence (refresh to reset)
- ✅ Optimized for web performance

## 📁 File Structure

```
_Cursor/
├── Asset/
│   ├── 1.png, 2.png, 3.png     # Image sequence
│   ├── Collab Cursor.svg        # Custom cursor
│   └── Logo.svg                 # Canva logo
├── Font/
│   ├── CanvaSans-Medium.woff
│   └── CanvaSansDisplay-Regular.woff
├── ad-300x250/index.html        # Medium rectangle
├── ad-300x600/index.html        # Half page
├── ad-160x600/index.html        # Skyscraper
├── ad-320x50/index.html         # Mobile banner
├── ad-728x90/index.html         # Banner
├── ad-970x250/index.html        # Leaderboard
├── index.html                   # Main 300×250 ad
├── all-sizes-preview.html       # Portfolio showcase
└── preview.html                 # Single ad preview
```

## 🎨 Customization

### Update Text Content
Change the headline text in any ad format:
```html
<h2 class="ad-headline">Your custom headline here</h2>
```

### Modify Colors
Update the gradient background:
```css
background: linear-gradient(135deg, #13A3B5 0%, #992BFF 100%);
```

### Replace Images
Update the image sequence in Asset/ folder:
- `1.png` - Initial image
- `2.png` - After background remover click
- `3.png` - Final image with hover effects

### Star Colors
- Most formats: Purple stars (`#8B3DFF`)
- 320×50 format: Yellow stars (`#FFD200`)

## 🔧 Animation Sequence

1. **Initial State**: Shows 1.png with "Background remover" button
2. **Click Action**: Headline transitions + SVG swipe animation
3. **Star Burst**: Purple/yellow stars animate outward at 75% timing
4. **Image Swap**: Changes to 2.png during swipe
5. **Final State**: Scales to 3.png with hover effects enabled

## 🌐 Usage

### Individual Ad Formats
Each ad format is self-contained in its own folder:
- Open `ad-[size]/index.html` directly in browser
- All assets are referenced relatively from root folders

### Portfolio View
- Open `all-sizes-preview.html` to see all formats
- Each format is displayed with dimensions as labels
- Includes "View Full Size" and "Refresh" buttons

## 📊 Performance

- Optimized asset loading with relative paths
- Efficient CSS animations with cubic-bezier timing
- Minimal JavaScript for maximum compatibility
- All ads work without external dependencies

## 🎯 Ready to Use

All ads are production-ready and can be:
- Uploaded to ad platforms
- Embedded in websites
- Customized with your content
- Scaled for different campaigns

---

**Complete display ad portfolio ready for deployment!** 🚀 