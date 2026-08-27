# Setup Instructions for Raksha Bandhan Premium

## Quick Start

### 1. Upload Your Photos

Add three photos to the `photos/` folder:
- `photo1.jpg` - First celebration photo
- `photo2.jpg` - Second celebration photo  
- `photo3.jpg` - Third celebration photo

**Recommended image specifications:**
- Format: JPG, PNG, or WebP
- Size: 800x600px or larger (landscape orientation)
- Quality: High resolution for best appearance

### 2. Upload Your Music

Add a music file to the `music/` folder:
- `raksha-bandhan.mp3` - Devotional or celebration music

**Supported formats:**
- MP3 (recommended)
- WAV
- OGG
- M4A

### 3. Open in Browser

Simply double-click `index.html` or:
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx http-server

# Then open http://localhost:8000
```

## Customization Tips

### Change Colors
Edit the CSS variables in `index.html` (lines 17-23):
```css
--primary-color: #d4af37;      /* Gold */
--secondary-color: #c41e3a;    /* Red */
--accent-color: #ffd700;       /* Bright Gold */
--saffron: #ff9933;            /* Saffron */
```

### Add Personal Text
Edit any section in `index.html`:
- Change the title
- Modify the about section
- Update the celebration message
- Customize footer text

### Gallery Customization
- Adjust grid columns in CSS (`.gallery-container`)
- Change image sizes (`.gallery-item img` height)
- Modify hover effects

## Features

✅ Fully Responsive Design
✅ Interactive Photo Gallery
✅ Built-in Music Player
✅ Smooth Animations
✅ Mobile Friendly
✅ No Dependencies Required
✅ Easy to Customize

## File Structure

```
raksha_bandhan_premium/
├── index.html              # Main website
├── README.md               # Documentation
├── SETUP.md                # Setup guide (this file)
├── photos/
│   ├── photo1.jpg
│   ├── photo2.jpg
│   └── photo3.jpg
└── music/
    └── raksha-bandhan.mp3
```

## Troubleshooting

**Q: Images not showing?**
- Check file names match exactly: `photo1.jpg`, `photo2.jpg`, `photo3.jpg`
- Ensure files are in the `photos/` folder
- Try using a local server instead of opening directly

**Q: Music not playing?**
- Check file name is `raksha-bandhan.mp3`
- Ensure file is in the `music/` folder
- Try a different audio format if MP3 doesn't work
- Use a local server for best results

**Q: Styling looks wrong?**
- Make sure you're using a modern browser
- Clear browser cache (Ctrl+Shift+Del or Cmd+Shift+Del)
- Try a different browser

## Need Help?

Refer to the main README.md for more information about features and browser support.

Happy Raksha Bandhan! 🎉💝
