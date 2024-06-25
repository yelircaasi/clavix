# clavix

Tool for creating and declaring a coherent set of keybindings in one place and
applying it nearly everywhere, even on websites. Integrated with NixOS and 
Home Manager (but works on other Linux distros, too). 

Note: This is a new project and while I anticipate rapid development, it will
remain a work in progress for some time. Suggestions welcome!

## Design notes

* it should be possible to represent and query any key sequence of any type
* all collisions should be detected
* top priority software supported: nix, wezterm, hyprland, sway, kanata, neovim, espanso

### Key Press Types

* tap
  * simple (key passed)
  * sticky (wait for next key, which will be modified)
* held modifier (key must be pressed before the modified key and not released before the modified key has been pressed)
* tap dance (key pressed quickly n times for a different interpretation)
* chords (combination of keys pressed simultaneously to be interpreted differently)

### Query Format

### JSON Format

```json
{}
```

### Keybind Imports

### Keybind Exports

