# Dmenu - Dynamic Menu

This is my build of dmenu that fits with my dwm color scheme.

### Patches

+ **FuzzyFinder** - A better search method
+ **FuzzyMatch** - To go with fuzzyfinder (grey+red color scheme used in my dwm build)

## Notes on Emojis and Special Characters

If st crashes when viewing emojis, install [libxft-bgra](https://aur.archlinux.org/packages/libxft-bgra/) from the AUR.

Note that some special characters may appear truncated if too wide. You might want to manually set your preferred emoji/special character font to a lower size in the `config.h` file to avoid this. By default, JoyPixels is used at a smaller size than the usual text.
