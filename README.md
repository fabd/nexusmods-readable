# Make NexusMods Readable Again

This is an attempt at improving the hit and miss visual hierarchy in the 2017 redesign of NexusMods. The redesign feels cluttered and I find it slower to scan pages and figure out what is what.

![nexusmods-readable-preview](https://user-images.githubusercontent.com/169391/43167195-2691e216-8f99-11e8-9a0e-eb45affaf562.png)

## How to install

[![Install directly with Stylus](https://img.shields.io/badge/Install%20directly%20with-Stylus-00adad.svg)](https://raw.githubusercontent.com/fabd/nexusmods-readable/master/nexusmods-readable.user.css)

Requires **Stylus addon** for [Firefox](https://addons.mozilla.org/en-US/firefox/addon/styl-us/) or 
 [Google Chrome](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne?hl=en).

Tested on Desktop, Firefox, best for 1000px wide and up.


## Changes

Note: there are **OPTIONS**! After installing, click the cog wheel in the Stylus dropdown.

In general:

- Site-wide compact header / top navigation
- Slightly darker theme, so images and text pop better
- **Option** to change the main button color
- **Option** to change the button style between rounded / square

Mod pages:

- DESCRIPTION tab:
  - **Option** to hide the confusing "about this mod" section in the mod description
  - **Option** to disable the centered content (easier to read)
  - limit the line length on wide desktop (easier to read)
- FILES tab:
  * auto-expand all the files, so "Misc" file descriptions can be seen
  * simplify the NMM / MANUAL download buttons
- IMAGES tab:
  * remove the awful gradient, so the images look brighter
- POSTS tab:
  * mostly aesthetic tweaks
- Fix lack of contrast or emphasis in some areas, for example:
  * visually separate the mod tags from the main buttons
- Fix unnecessary repetition in some places, for example:
  * "Mod tags" label next to what are obviously tags
  * mod title at the end of the breadcrumb, just above the... mod title
- Simplify by unifying some background / boxes so it's easier to scan


## Contributions

Feel free to suggest fixes or even CSS improvements. Always interested in learning things!

The focus is on readability. But of course you can fork this to tweak anything you like.


## License

Permission is hereby granted to do whatever the hell you want with this.
