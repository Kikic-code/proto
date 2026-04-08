# ParkPilot

A prototype interactive mobile application showcasing parking management features, built with Proto.io and exported as a static HTML5 application.

## Features

- iPhone 15 Pro Max responsive design
- Portrait and landscape orientation support
- Interactive prototype with multiple pages
- Fully self-contained with local assets
- No external dependencies

## Deployment

### GitHub Pages

1. Push this repository to GitHub
2. Go to **Settings → Pages**
3. Under "Build and deployment", select:
   - **Source**: Deploy from a branch
   - **Branch**: `main` (or your default branch)
   - **Folder**: `/` (root)
4. Your site will be live at: `https://yourusername.github.io/repo-name/`

### Local Testing

```bash
# Using Python 3
python -m http.server 8000

# Then open: http://localhost:8000
```

```bash
# Using Node.js
npx http-server

# Then open: http://localhost:8080
```

## File Structure

```
├── index.html                 # Main entry point
├── preview.html              # Preview version with UI controls
├── fullscreen.html           # Fullscreen player
├── src/
│   ├── index.html           # App content
│   ├── data/                # Application data
│   ├── assets/              # Images and branding
│   ├── scripts/             # JavaScript libraries
│   ├── stylesheets/         # CSS styles
│   └── libraries/           # UI components
└── README.md                # This file
```

## Usage

Simply open `index.html` in a web browser. The application will display an iPhone mockup with the interactive prototype loaded.

### Features

- **Refresh**: Reload the prototype
- **Rotate**: Toggle between portrait and landscape
- **Fullscreen**: Expand to full screen view

## Browser Support

- Chrome/Chromium
- Firefox
- Safari
- Edge

All modern browsers with ES6 support are required.

## Notes

- This is a static export of a Proto.io prototype
- All assets are included locally
- No backend server or external API calls are required
- Suitable for offline viewing and sharing

## License

ParkPilot - Parking Management Application Prototype
