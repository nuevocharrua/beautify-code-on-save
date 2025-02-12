# Beautify Code on Save
>A Godot 4 plugin that automatically formats and lints your GDScript files when saving.
<img width="220" alt="Format on Save logo" src="./icon.png" />


## Features

- Automatic code formatting using `gdformat` when saving files
- Code style checking with `gdlint` after formatting
- Maintains cursor and scroll position
- Configurable paths for both tools
- Automatic tool path detection
- Clean error reporting

## Prerequisites

1. You need to have `gdtoolkit` installed. For installation instructions, visit:
   https://github.com/Scony/godot-gdscript-toolkit

2. Make sure both `gdformat` and `gdlint` are available in your system after installation.

## Installation

1. Clone this repository (or download it) into your project's `addons` folder:
```bash
cd your-project
git clone https://github.com/nuevocharrua/beautify-code-on-save addons/beautify_code_on_save
```

2. Enable the plugin in Godot:
   - Go to Project -> Project Settings -> Plugins
   - Find "Beautify Code on Save" in the list
   - Check the "Enable" checkbox

## Configuration

The plugin will try to automatically detect the paths to `gdformat` and `gdlint`. If it cannot find them, you can configure them manually:

1. Go to Editor -> Editor Settings
2. Scroll down to the "Beautify Code on Save" section
3. Set the paths for both tools

Common paths are:
- Linux/macOS: `/usr/local/bin/gdformat` or `~/.local/bin/gdformat`
- Windows: Usually in `%APPDATA%\Python\Scripts\gdformat.exe`

## Usage

Just save your GDScript files (Ctrl+S/Cmd+S) and they will be automatically formatted and checked!

## License

MIT License - See LICENSE file for details
