# VSCode Minimalist Theme

A bunch of minimalist dark theme for VSCode. Mostly based on the `Dark Modern` theme, but with a few tweaks:
- No drop shadows: menus and popups have no drop shadows.
- Consistent color palette. For example:
	- The Activity Bar active indicator is white.
	- Active tab and editor have the same background color.

## Screenshots
### Minimalist
![Theme screenshot](/screenshots/minimalist.png?raw=true)
### Minimalist _Flat_
![Flat screenshot](/screenshots/flat.png?raw=true)
### Minimalist _One Dark Pro Colors_
![ODP screenshot](/screenshots/odp.png?raw=true)
### Minimalist _Oak_
![OAK screenshot](/screenshots/oak.png?raw=true)
### Minimalist _Obsidian_
![OAK screenshot](/screenshots/obsidian.png?raw=true)

## Installation
From [marketplace](https://marketplace.visualstudio.com/items?itemName=MuhammadMohsen.vsc-minimalist-theme)

## Publishing / Updating
- run `vsce login muhammadmohsen` and enter the access token.
- run `vsce package`
- run `vsce publish major/minor/patch/`

## Palette (outdated)
### background `#161616` -> `#111111`
- activityBar.background
- sideBar.background
- statusBar.background
- titleBar.activeBackground
- input.background
- panel.background
- editorGroupHeader.tabsBackground
- tab.inactiveBackground

### secondary background `#1e1e1e` -> `#191919` -> `#1A1B20`
- tab.activeBorder

### foreground `#fff`
- activityBar.foreground
- activityBarBadge.foreground
- statusBar.foreground
- statusBar.debuggingForeground
- badge.foreground

### secondary foreground `#ccc`

### border `#333333` -> `#222222`
- titleBar.border
- input.border
- panel.border
- terminal.border
- editorGroupHeader.tabsBorder
- tab.border

### accent `#007acc`
- focusBorder
- progressBar.background
- activityBarBadge.background
- badge.background

### transparent
- scrollbar.shadow
- tab.activeBorderTop

## Ref
https://code.visualstudio.com/api/references/theme-color
