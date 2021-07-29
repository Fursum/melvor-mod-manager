![M3 Logo](repo/m3-small.png)
# Melvor Mod Manager (M3)
Melvor Mod Manager (M3) allows you to quickly add userscripts and browser extensions as mods to the Steam edition of Melvor Idle.

## Installation
Download and run the setup .exe from the [Latest Release](https://github.com/ChaseStrackbein/melvor-mod-manager/releases/latest).

## Use
Once installed and launched:
1. Click the 'Browse' button and find your Melvor Idle installation directory. It is most likely something like: `C:\Program Files (x86)\Steam\steamapps\common\Melvor Idle`
2. Click the 'Add +' button and add a mod from either a file or a web URL.
3. Launch the game using the button in the upper-right and your mods should be loaded upon selecting your character.

### Add From File
Files can be either a JavaScript (.js) file formatted with UserScript metadata or a WebExtension manifest (manifest.json). This means that for extensions, you should manually download them (for example, from the Combat Simulator Reloaded's [release page](https://github.com/visua0/Melvor-Idle-Combat-Simulator-Reloaded/releases)), extract the .zip file, and then navigate the M3 file prompt to the manifest.json file found within.

### Add From Web
Currently only GreasyFork userscript URLs are supported. Example: `https://greasyfork.org/en/scripts/428146-quickshards-for-melvor-idle`

### Updating Mods
M3 currently only supports updating of mods through the UI that have been added via GreasyFork. For all other mods, you should first remove it and then re-add using the newer version. 

### Mod Load Order
You can adjust the load order of the mods using the arrows on the right-hand side of the mod list. This may help in resolving dependencies in the correct order.

## Screenshot
![Screenshot of M3](repo/app-screenshot.png)

## Submitting Feedback or Contributing
Feel free to [create an issue here on GitHub](https://github.com/ChaseStrackbein/melvor-mod-manager/issues) or reach out to me on Discord @ Buttchouda#3950.