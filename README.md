![theme](https://github.com/passivestar/godot-minimal-theme/assets/60579014/01c29b15-14be-47e9-a9bc-d9d2d935604f)

# Minimal Godot Theme

## Installation

- Click `Releases` on the right and download the `.tres` file. Use the high ppi version for high pixel density (i.e if you're on a laptop with a 4k display)
- In Godot open `Editor Settings -> Interface -> Theme`, and choose the downloaded theme in the Editor Theme field

## Recommended settings

To match the look of the theme in the screenshot, you can use the following settings:

- Base Color: `#252525`
- Accent Color: `#3d85f2`
- Contrast: `0.25`
- Icon Saturation: `1.8`

Everything else by default

## Known limitations

- If you're using a different base color rather than one listed above, input fields may look out of place. This is a limitation of Godot's theming, there is no way to style `LineEdit`s with support for different base colors. Unfortunately there's nothing that I can do about it
