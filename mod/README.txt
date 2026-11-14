# HOI4 Map Color Change Mod
This mod allows you to change the color of countries on the map using a color picker (scripted GUI).

## Installation
1. Extract the contents of the `mod` folder into your `Documents/Paradox Interactive/Hearts of Iron IV/mod/` directory.
2. Enable the mod in the launcher.

## Usage
1. Start a game or load a save.
2. Select a country (or a state belonging to the country).
3. Click the **Color Picker** button in the top right corner (or via the scripted GUI).
4. Choose a color from the picker or enter an RGB value.
5. Click **Apply** to change the map color of the selected country.

## How it works
- The mod uses a Scripted GUI (`interface/color_picker.gui` and `common/scripted_guis/color_picker.txt`).
- The color picker allows selecting RGB values.
- The script triggers an effect to update `color` and `color_ui` in `common/countries/colors.txt` or directly via country scope effects.

## Credits
- Created by Belndini55 / Arena.ai Agent

## License
MIT License
