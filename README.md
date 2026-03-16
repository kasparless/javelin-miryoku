# javelin-miryoku
Miryoku and Steno layout for the Jarne keyboard, using Javelin firmware, implemented in Javelin-Script.

This repo: https://github.com/kasparless/javelin-miryoku

## Installing / Generating a Javelin Miryoku layout

Follow this link to the [installation instructions](./install.md)

## Reference Links

### Miryoku sites

Miryoku is a is an ergonomic, minimal, orthogonal, and universal keyboard layout for typing.
 
Homepage

https://github.com/manna-harbour/miryoku/
 
Reference Manual

https://github.com/manna-harbour/miryoku/tree/master/docs/reference

### Javelin sites

Javelin enables 'embedded steno', allowing for stenography to be embedded on the keyboard itself, removing the need for installing Plover, or using propriety steno systems.

https://lim.au/#/software/javelin-steno

https://github.com/jthlim/javelin-steno

Javelin-Script

https://github.com/jthlim/javelin-steno/blob/main/script.md

### Stenography

Traditional longhand handwriting evolved to typewriters, then modern keyboards. Type one symbol at a time.

Shorthand evolved into machine stenography, now open sourced.  Stroke a syllable or word at a time.

https://opensteno.org/

https://opensteno.org/plover/

https://lapwing.aerick.ca/

### Jarne keyboard

The Jarne is a 42-key board with capacity for embedded steno, bluetooth, IR and FIDO. 

https://shop.chenonetta.com/product-category/keyboards/jarne/

https://lim.au/#/hardware/jarne-manual

## Layout

Here are the combined layers.

![alt text](<docs/images/Screenshot 2026-03-15 165106.png>)

![alt text](<docs/images/Screenshot 2026-03-15 165120.png>)

[alt text](<docs/images/Screenshot 2026-03-16 174439.png>)

![alt text](<docs/images/Screenshot 2026-03-15 165154.png>)

![alt text](<docs/images/Screenshot 2026-03-15 165209.png>)

![alt text](<docs/images/Screenshot 2026-03-15 165224.png>)

![alt text](<docs/images/Screenshot 2026-03-15 165238.png>)

![alt text](<docs/images/Screenshot 2026-03-15 165251.png>)

![alt text](<docs/images/Screenshot 2026-03-15 165325.png>)

![alt text](<docs/images/Screenshot 2026-03-15 165308.png>)

### Discussion

This is not yet a full, canonical implementation of the Miryoku system.

Miryoku 'additional features':
- Reboot, tap and alt layers: I don't need/want them. PRs welcome.
- Layer and Opposite lock.  Hopefully soon, working to upskill on Javelin-Script.
- Mouse wheel movements: partially implemented, to be improved soon.

Jarne specific features:
- The Miryoku model doesn't map exactly to the Jarne: for the RGB controls, bluetooth and FIDO. These have been added in a hopefully consistent manner.

General musings:
- The outer pinkies could be used for a lot more
- Could maybe add a layer switch to steno inner thumb
- Potential to work on a Taipo or Artsey style layer for mouse work, instead of current 'button' layer.

## License

This repo has an MIT license.
