![MoErgo Logo](./logo.png)

# MoErgo Go60 ZMK Config

This is my customized keyboard layout for the MoErgo Go60 split keyboard, designed as a clone and modification of the [TailorKey v4.2l](https://sites.google.com/view/tailorkey) Standard HRM Dual-OS configuration.

The original TailorKey layout is a zero-code, [Glorious Engrammer](https://github.com/sunaku/glove80-keymaps)–inspired design that uses only the Layout Editor’s native behaviors, requiring no custom-defined logic.

Set of features:

- Home-row modifiers (HRM)
- AutoShift
- Cursor and symbol layers
- Mouse / trackpad emulation
- Combo keys
- Optional RGB lighting
- Dual-OS (macOS / Linux) support

#### Changes done:

##### 1. General:

- Renamed HRM MacOS / HRM Linux layers
- Removed Gaming and Mouse layers
- Renamed AutoShift layer for clarity
- Reordered layers: HRM → Typing → AutoShift → Keypad → Symbol → Mouse → Magic
- Renamed and adjusted home-row hold-taps based on Sunaku’s [reference](https://docs.google.com/spreadsheets/d/1ESgObQelyz4lnKlfwLYsmofLJulOMK5RdGBsopLe2o8)
- Renamed and adjusted AutoShift macros and hold-taps following [ZMK AutoShift behavior](https://github.com/nickcoutsos/keymap-editor/wiki/Autoshift-using-ZMK-behaviors) guidelines
- Renamed thumb and space hold-taps for consistency
- Renamed `CapsLock` and `F*` combos
- Removed word and line selection extensions
- Removed unused macros, hold-taps, and combos
- Increased mouse movement speed (×3) and reduced scroll speed (×0.75)
- Mapped left mouse button to act as right click
- Enabled per-key and per-layer RGB ([instructions](https://sites.google.com/view/tailorkey/how-to/rgb))

##### 2. Home-Row Mods:

- Swapped `Space` and `Backspace`
- Adjusted layout to more closely match the factory configuration
- Added Symbol layer access
- Updated thumb key placement

##### 3. AutoShift:

- Added `Magic` key for exiting the layer
- Added brackets and tilde keys
- Return to Typing layer after use
- Removed extra `Num Enter` and `Num 0`; added `Num =`
- Removed clipboard and undo/redo actions

##### 4. Symbol:

- Made `Magic` and thumb keys transparent
- Return to Typing layer after use

##### 5. Mouse:

- Increased movement speed (×9) and scroll speed (×1)
- Added horizontal and vertical scroll controls

##### 6. Magic:

- Swapped HRM macOS and HRM Linux keys
- Replaced text output macro with Bluetooth Clear Bonds
