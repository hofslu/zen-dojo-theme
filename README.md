# Zen Dojo Theme 🧘‍♂️🌱

A custom VS Code theme inspired by traditional Japanese house interiors—tatami mats, shoji paper screens, dark cedar beams, bamboo green, and subtle indigo accents.

## Themes

- **Zen Dojo Light**: A light theme evoking morning light filtering through shoji screens—soft paper whites, warm cedar, bamboo green, and indigo accents.
- **Zen Dojo Dark**: A dark theme capturing the serene evening atmosphere of a traditional Japanese room—dark cedar walls, warm candlelight, and muted natural tones.

## Color Palette

### Light Theme

- **Shoji Paper** `#F9F7F0` - Main editor background
- **Tatami** `#F5F2E6` - Sidebar and tabs
- **Dark Cedar** `#3F2A1C` - Main text
- **Chestnut** `#5A3D24` - Types, constants, activity bar
- **Bamboo Green** `#6F7B3A` - Strings, attributes
- **Indigo** `#1F3A5F` - Keywords, functions, status bar
- **Vermilion** `#C84418` - Control flow, cursor
- **Sakura** `#E8B7C4` - Selections

### Dark Theme

- **Dark Cedar** `#2A1F18` - Main editor background
- **Charcoal** `#221A14` - Sidebar
- **Shoji Paper** `#F5F2E6` - Main text
- **Light Indigo** `#7A9BC4` - Keywords, functions
- **Soft Bamboo** `#9BAA6B` - Strings
- **Warm Clay** `#E89F7D` - Control flow
- **Tatami Beige** `#D9C7A8` - Types, constants

## Installation

### For Development
1. Clone this repository
2. Run `npm run deploy` to package and install the theme
3. Reload VSCode (Cmd+Shift+P → "Developer: Reload Window")
4. Select "Zen Dojo Light" or "Zen Dojo Dark" from Color Theme picker (Cmd+K Cmd+T)

### For Testing
1. Open this folder in VS Code
2. Press `F5` to launch the Extension Development Host
3. In the new window, select the theme from Color Theme picker

## Development

### Making Changes
1. Edit colors in `themes/my-earthy-light.json` or `themes/my-earthy-dark.json`
2. Run `npm run deploy` to package and install the updated theme
3. Reload VSCode to see your changes

### Scripts
- `npm run package` - Package the extension as a .vsix file
- `npm run deploy` - Package and install the theme in your VSCode

## Customization

You can edit the colors in `themes/my-earthy-light.json` and `themes/my-earthy-dark.json`.
