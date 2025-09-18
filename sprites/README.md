This is the place where I store my icon sets to use in web maps. 
There are both self-hosted default sprites from OpenFreeMap and Protomaps, but also some experimental versions of Lucide and Phosphor icons.
The custom icons were all made with [Spreet](https://github.com/flother/spreet).

You can either use a single sprite source in your map style, or multiple sprite sources by providing arrays of Id and Urls pointing to specific spritesheet.

Please see the official docs for this matter https://maplibre.org/maplibre-style-spec/sprite/

Example of standard single sprite url:
```
    "sprite": "https://latidudemaps.github.io/basemap-assets/sprites/v4/light",
```

Example of multiple sprite sources:
```
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
        },
        {
            "id": "phosphor-bold",
            "url": "https://latidudemaps.github.io/basemap-assets/sprites/phosphor/bold"
        },
        {
            "id": "phosphor-thin",
            "url": "https://latidudemaps.github.io/basemap-assets/sprites/phosphor/thin"
        },
        {
            "id": "phosphor-fill",
            "url": "https://latidudemaps.github.io/basemap-assets/sprites/phosphor/fill"
        }
    ]
```
