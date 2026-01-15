# Formosa Theme for Ghostty

A color theme for [Ghostty](https://ghostty.org/) terminal emulator, inspired by the **Porsche 911 Carrera T "Formosa" Taiwan Limited Edition**.

![Porsche 911 Carrera T Formosa](https://newsroom.porsche.com/.imaging/mte/porsche-templating-theme/image_1080x624/dam/Taiwan/2024/Motorsports%20and%20Events/911%20Carrera%20T%20Formosa%20Taiwan%20Limited%20Edition/gallery/911-Carrera-T-Formosa-Taiwan-Limited-Edition-4.jpeg/jcr:content/911-Carrera-T-Formosa-Taiwan-Limited-Edition-4.jpeg)

## Theme Variants

| Variant | Description |
|---------|-------------|
| **Formosa Light - Ipanema Blue** | Light theme with cyan/teal accent inspired by Ipanema Blue |
| **Formosa Light - Night Green** | Light theme with green accent inspired by Night Green Metallic |
| **Formosa Dark - Ipanema Blue** | Dark theme with cyan/teal accent inspired by Ipanema Blue |
| **Formosa Dark - Night Green** | Dark theme with green accent inspired by Night Green Metallic |

## Installation

### Option 1: Copy to Ghostty themes directory

```bash
# Create themes directory if it doesn't exist
mkdir -p ~/.config/ghostty/themes

# Copy theme files
cp themes/* ~/.config/ghostty/themes/
```

### Option 2: Clone repository

```bash
git clone https://github.com/peteryang1756/formosa-ghostty-theme.git
cp formosa-ghostty-theme/themes/* ~/.config/ghostty/themes/
```

## Usage

Add the theme to your Ghostty configuration file (`~/.config/ghostty/config`):

```ini
# Choose one of the following:
theme = formosa-light-ipanema-blue
# theme = formosa-light-night-green
# theme = formosa-dark-ipanema-blue
# theme = formosa-dark-night-green
```

### Auto-switch Light/Dark Mode

You can configure Ghostty to automatically switch themes based on system appearance:

```ini
theme = light:formosa-light-ipanema-blue,dark:formosa-dark-ipanema-blue
```

Or for Night Green variant:

```ini
theme = light:formosa-light-night-green,dark:formosa-dark-night-green
```

## Color Palette

### Ipanema Blue Variant

The Ipanema Blue variant uses cyan/teal tones inspired by the exclusive Ipanema Blue exterior color.

### Night Green Variant

The Night Green variant uses rich green tones inspired by the Night Green Metallic paint option.

## Related Projects

- [Formosa Theme for Zed](https://github.com/peteryang1756/formosa-zed-theme) - 100+ downloads
- [Formosa Theme for VS Code](https://github.com/peteryang1756/formosa-vscode-theme)

## Inspiration

This theme draws inspiration from the limited edition Porsche 911 Carrera T released exclusively for Taiwan in 2024, featuring:

- **Ipanema Blue** - A distinctive cyan/teal color exclusive to this edition
- **Night Green Metallic** - A deep, sophisticated green option
- **Pebble Grey Leather** - Premium interior appointments
- **"FORMOSA" Script** - Unique side decal celebrating Taiwan

## License

MIT License - see [LICENSE](LICENSE) file for details.

## Author

Created by [Takeshi](https://github.com/peteryang1756)
