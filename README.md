# Block Mono Font

A programming font based on IBM Plex Mono, enhanced for improved readability and developer experience.

## Features

### Increased Height
- Extended character height for better visual distinction
- Improved readability in code editors and terminals
- Maintains the professional appearance of IBM Plex Mono while providing better legibility

### Ligatures
- Comprehensive ligature support for common programming patterns
- Includes arrows (→, ←, ↑, ↓), comparisons (==, !=, <=, >=), and logical operators (&&, ||)
- Elegant rendering of common code constructs like `->`, `=>`, `/*`, `*/`, and more

### Nerd Fonts Support
- Complete Nerd Fonts integration with thousands of glyphs
- Includes icons for:
  - Development tools (Git, Node.js, Python, etc.)
  - File type indicators
  - Powerline symbols
  - Custom glyphs for various programming languages and frameworks

## Font Showcase

### Block Mono Font

![Block Mono Font Preview](assets/blockmono.png)

## How to Download

### Getting the Font

1. Click on the **Releases** section on the right side of this repository
2. Download the latest release:
   - **BlockMono-Regular.zip** - Standard version without Nerd Fonts
   - **BlockMono-NerdFont.zip** - Version with complete Nerd Fonts integration
3. Extract the downloaded `.zip` file to access the `.ttf` font files

## Installation

### Windows
1. Right-click on the `.ttf` font file
2. Select "Install" or double-click the file and click "Install"
3. The font will be available in all applications

### macOS
1. Double-click the `.ttf` font file
2. Click "Install Font" in the Font Book preview window
3. The font will be installed and available in all applications

### Linux
#### For all users (system-wide):
```bash
sudo cp *.ttf /usr/share/fonts/
sudo fc-cache -f -v
```

#### For current user only:
```bash
mkdir -p ~/.local/share/fonts
cp *.ttf ~/.local/share/fonts/
fc-cache -f -v
```

## License

This font is based on IBM Plex Mono and follows its license terms. Please refer to the [IBM Plex Mono license](https://github.com/IBM/plex#license) for more information.


## Acknowledgments

- Based on [IBM Plex Mono](https://github.com/IBM/plex)