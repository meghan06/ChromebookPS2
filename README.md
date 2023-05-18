VoodooPS2
=========

[![CI](https://github.com/meghan06/ChromebookPS2/actions/workflows/main.yml/badge.svg)](https://github.com/meghan06/ChromebookPS2/actions/workflows/main.yml)

This is a modified version of VoodooPS2 for Chromebooks running macOS. It enables keyboard backlight control and [maps the top row keys](#keyboard-remaps).

------------------------------------------------------------------------------------------------------------------------------------

### Read this:
>**Note**: Keyboard backlight can be controlled with `left ctrl` + `left alt` + comma (`,`) and period (`.`) keys.

**[SSDT-KBBL.aml](https://github.com/meghan06/ChromebookPS2/blob/master/Docs/SSDT-KBBL.aml) is required for keyboard backlight control.** 

------------------------------------------------------------------------------------------------------------------------------------

### Keyboard Remaps

```
F1 -> Previous Song
F2 -> Next Song
F3 -> Play/Pause
F4 -> Fullscreen (Map in SysPrefs)
F5 -> Mission Control (Map in SysPrefs)
F6 -> Brightness Down
F7 -> Brightness Up
F8 -> Volume Mute 
F9 -> Volume Down
F10 -> Volume Up

```

#### Things to keep in mind:

- F4 can be mapped to Full Screen in System Preferences -> Keyboard -> Shortcuts -> App Shortcuts.
- F5 can be mapped to Mission Control in System Preferences -> Keyboard -> Shortcuts -> App Shortcuts.

------------------------------------------------------------------------------------------------------------------------------------

### ok idc but where do i download
Grab the latest release from [Actions](https://github.com/meghan06/ChromebookPS2/actions) or from the [Releases](https://github.com/meghan06/ChromebookPS2/releases) tab.

------------------------------------------------------------------------------------------------------------------------------------

### Credits:
* **one8three for SSDT-KBBL.aml and the original idea of a custom VPS2 for Chromebooks.**
* acidanthera for the original VoodooPS2
* VoodooPS2Controller etc. – turbo, mackerintel, @RehabMan, nhand42, phb, Chunnan, jape, bumby (see RehabMan's repository).
* Magic Trackpad 2 reverse engineering and implementation – https://github.com/alexandred/VoodooI2C project team.
* VoodooPS2Trackpad integration – @kprinssu.
* Force Touch emulation and finger renumbering algorithm** – @usr-sse2.
* Elan touchpad driver – linux kernel contributors, @kprinssu, @BAndysc and @hieplpvip
