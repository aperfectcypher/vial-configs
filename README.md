# keeb

Vial keymap files for my custom keyboards.

## Keyboards

### Cosmotyl (Dactyl)

Handwired split keyboard based on the Dactyl form factor, powered by an RP2040. Features a 5x6 matrix per side with thumb keys, a rotary encoder, and trackball support.

- **Layout:** AZERTY (French)
- **Layers:** 5 (Base, Navigation, Gaming, Function/Numpad, Trackball)
- **Features:** Home-row mods (`LALT_T`, `LSFT_T`, `LCTL_T`), combos for brackets/symbols/navigation, layer lock, encoder (scroll/volume per layer)
- **File:** `dactyl.vil`

### Silakka54 (60% split)

A 60%-style split keyboard with a 5x6 matrix per side and 3 thumb keys.

- **Layout:** QWERTY
- **Layers:** 4 active (Navigation, Mouse, Function/Numpad) + 4 reserved
- **Features:** Combos for brackets/symbols/navigation, layer lock, key override (Shift+Backspace = Delete), caps word toggle
- **File:** `60sh_silakka54.vil`

## File Format

`.vil` files are JSON keymap exports from [Vial](https://get.vial.today/) (File > Save As). They can be loaded back into Vial to flash or edit the keymap.
