# Biolink Template

A modern, animated biolink page with Discord status integration, music player, and custom cursor effects.

## Features

- Animated starfield background
- Custom cursor follower
- Discord status integration (real-time)
- Built-in music player with waveform visualization
- Smooth animations and transitions
- Mobile responsive
- Visitor counter
- Click-to-enter splash screen

## Setup

1. Download the HTML file
2. Replace all placeholder values at the top of the file:

```javascript
// Meta tags (in <head>)
YOUR_OG_IMAGE_URL_HERE
YOUR_DESCRIPTION_HERE
YOUR_NAME_HERE
YOUR_FAVICON_URL_HERE

// Configuration variables
const SONG_URL = 'YOUR_SONG_URL_HERE.mp3';
const SONG_TITLE = 'YOUR_SONG_TITLE';
const SONG_ARTIST = 'YOUR_ARTIST_NAME';
const DISCORD_USER_ID = 'YOUR_DISCORD_ID_HERE';
```

3. Update the content sections:
   - Replace `YOUR_NAME` with your display name
   - Replace `@YOUR_USERNAME` with your username
   - Replace `YOUR_LOCATION` with your location
   - Update all link URLs and text in the links section
   - Update social media URLs at the bottom

4. Upload to your web host

## Discord Integration

The template uses two APIs for Discord status:
- [Discord Lookup API](https://discord-lookup-api-opal-three.vercel.app) for profile info
- [Lanyard API](https://api.lanyard.rest) for real-time status

To get your Discord User ID:
1. Enable Developer Mode in Discord (Settings > Advanced)
2. Right-click your profile and select "Copy User ID"

## Music Player

Upload your music file to a hosting service (GitHub, Dropbox, etc.) and use the direct link. Supported formats: MP3, WAV, OGG.

## Visitor Counter

The template includes a visitor counter powered by `visitor.6developer.com`. It tracks:
- Total visits
- Page views
- Referrer data
- Search queries

## Customization

### Colors
Change the pink accent color by replacing `#f2a2c2` throughout the CSS with your preferred color.

### Font
The template uses VT323 (pixel font). To change it:
1. Update the Google Fonts import in `<head>`
2. Replace `font-family: 'VT323', monospace;` in CSS

### Links
Add or remove link items in the "flex flex-col gap-4 mb-8" section. Copy/paste the existing link structure.

## Browser Support

- Chrome/Edge (recommended)
- Firefox
- Safari
- Mobile browsers

## Credits & License

**IMPORTANT**: If you use this template, you **MUST** include the following comment in your HTML file:

```html
<!-- Witheredheartz made this, do not delete this, this is credits, even if you obfuscate it put my name it in the comment thanks. -->
```

### Terms of Use

- ✅ Personal use allowed
- ✅ Modify and customize
- ✅ Host on your own domain
- ❌ Sell or redistribute as your own
- ❌ Remove credits
- ❌ Claim as your own work

**Failure to include credits may result in a DMCA takedown request to your hosting provider.**

## Support

For issues or questions, contact:
- Discord: witheredheartz
- GitHub: [@Justanewplayer19](https://github.com/Justanewplayer19)

## Changelog

### v1.0.0 (2025)
- Initial release
- Discord status integration
- Music player with waveform
- Custom cursor effects
- Visitor tracking

---

Made with love by [Witheredheartz](https://github.com/Justanewplayer19)
