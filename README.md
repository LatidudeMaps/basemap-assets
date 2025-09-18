# Basemap Assets

A comprehensive collection of map styling assets for Maplibre GL JS including sprites, fonts, and complete map styles. All assets are hosted via GitHub Pages and ready for production use.

## 🗂️ What's Included

### 🎨 **Sprites** (Icon Sets)
- **Default Sprites**: Self-hosted sprites from OpenFreeMap and Protomaps
- **Lucide Icons**: Clean, customizable icon set
- **Phosphor Icons**: Available in multiple weights (regular, bold, thin, fill)
- **Geo Patterns**: Geological patterns by [davenquinn](https://github.com/davenquinn/geologic-patterns)

### 📝 **Fonts** (22 Font Families)
Includes popular web fonts like:
- Rubik (Regular, Medium, Bold, Light, SemiBold, etc.)
- Noto Sans (Regular, Bold, Italic, Medium)
- Open Sans Regular
- Libre Baskerville (Regular, Bold, Italic)

### 🎯 **Complete Map Styles** (13 Styles)
Ready-to-use map styles including:
- OpenFreeMap variants (bright, liberty, positron, vintage)
- Protomaps styles (dark, grayscale, dataviz variants)
- Custom styling options

## 🚀 Quick Start

### Using a Complete Style
```javascript
const map = new maplibregl.Map({
    container: 'map',
    style: 'https://latidudemaps.github.io/basemap-assets/styles/vintage.json'
});
```

### Using Single Sprite Source
```json
{
    "sprite": "https://latidudemaps.github.io/basemap-assets/sprites/v4/light"
}
```

### Using Multiple Sprite Sources
```json
{
    "sprite": [
        {
            "id": "default",
            "url": "https://tiles.openfreemap.org/sprites/ofm_f384/ofm"
        },
        {
            "id": "lucide",
            "url": "https://latidudemaps.github.io/basemap-assets/sprites/lucide/lucide-icons"
        },
        {
            "id": "phosphor-regular",
            "url": "https://latidudemaps.github.io/basemap-assets/sprites/phosphor/regular"
        }
    ]
}
```

## 📁 Repository Structure

```
├── sprites/           # Icon spritesheets
│   ├── lucide/       # Lucide icons
│   ├── phosphor/     # Phosphor icons (multiple weights)
│   ├── geo-patterns/ # Geological patterns
│   ├── v3/           # Version 3 sprites
│   └── v4/           # Version 4 sprites
├── fonts/            # Web font glyphs (22 font families)
├── styles/           # Complete map styles (13 styles)
└── layers/           # Layer definitions
```

## 🛠️ Tools Used

- **[Spreet](https://github.com/flother/spreet)**: Used to generate all custom spritesheets
- **GitHub Pages**: Hosting platform for all assets

## 📖 Documentation

- [Maplibre Sprite Specification](https://maplibre.org/maplibre-style-spec/sprite/)
- Individual README files in each subdirectory for detailed usage

## 🙏 Credits

- Geo patterns by [davenquinn](https://github.com/davenquinn) - check out the [original repo](https://github.com/davenquinn/geologic-patterns)
- Default sprites from [OpenFreeMap](https://openfreemap.org/) and [Protomaps](https://github.com/protomaps/basemaps-assets)
- Icon sets from [Lucide](https://github.com/lucide-icons/lucide) and [Phosphor](https://github.com/phosphor-icons/homepage)

## 📄 License

Please refer to individual asset licenses. Most icon sets maintain their original licensing terms.