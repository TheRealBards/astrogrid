# AstroGrid ✨

A free, browser-based star map generator that creates beautiful, astronomically accurate posters of the night sky for any date, time, and location.

**[Try it live →](https://therealbards.github.io/astrogrid)**

## Features

- **Astronomically Accurate** — Star positions calculated using precise algorithms with over 9,000 stars
- **70+ Constellations** — Complete stick figure patterns for major constellations
- **Realistic Milky Way** — Rendered galactic band based on actual position
- **Multiple Themes** — Midnight, Celestial, Cosmos, Vintage, Navy, and Minimal
- **Customisable** — Toggle constellations, Milky Way, compass, star names, and degree grid
- **High Resolution** — Export as PNG or JPG at print-ready 2400×3200px
- **Privacy Friendly** — Runs entirely in your browser, no data sent to servers

## Use Cases

- Commemorate a wedding, birth, or anniversary
- Remember a first date or special trip
- Create personalised gifts
- Educational astronomy projects

## How It Works

1. Enter a title and optional subtitle
2. Select your date and time
3. Search for your location
4. Choose a theme and display options
5. Download your star map

## Technical Details

AstroGrid is a single HTML file with no external dependencies (apart from Google Fonts). It uses:

- **Julian Date calculations** for precise astronomical time
- **Local Sidereal Time (LST)** conversion
- **Equatorial to Horizontal coordinate transformation**
- **Stereographic projection** for mapping the celestial sphere to 2D
- **Canvas API** for high-resolution rendering

## Local Development

No build process required. Simply:

```bash
git clone https://github.com/yourusername/astrogrid.git
cd astrogrid
# Open index.html in your browser
```

## Deployment

The project is designed for GitHub Pages:

1. Push to your GitHub repository
2. Go to Settings → Pages
3. Select your branch (usually `main`) and save
4. Your site will be live at `https://yourusername.github.io/astrogrid`

## Browser Support

Works in all modern browsers: Chrome, Firefox, Safari, Edge.

## Roadmap

- [ ] Additional colour themes
- [ ] PDF export option
- [ ] Share directly to social media
- [ ] Southern hemisphere constellation improvements

## License

MIT License — free for personal and commercial use.

## Acknowledgements

Star catalogue data derived from the Yale Bright Star Catalogue. Constellation line patterns based on IAU standards.

---

Made with 🌟 by Bardia