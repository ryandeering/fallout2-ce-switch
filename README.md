<div align="center">

![logo](assets/icon.jpg)

# Fallout 2 Community Edition - Switch

</div>

You must own the game to play and have a Switch capable of running **unsigned code, so you need a Switch running on custom firmware** to run the port. Needless to say, this is not an official effort from Interplay or Bethesda.

---

## Installation

1. Purchase your copy on [GOG](https://www.gog.com/game/fallout_2) or [Steam](https://store.steampowered.com/app/38410). The files need to be from a Windows installation (I think.)
2. Download the latest [release](https://github.com/ryandeering/fallout2-ce-switch/releases/latest) or build from the source. See YAML pipelines for reference.
3. Drag the installation files into a new folder called `fallout2` in your `switch` folder on the root of your SD card.
4. Put the necessary executable in your `switch` folder on the root of your SD card, either `.nro` or `.nso`.

> **Note:** Any Fallout 2 saves, CE or not, should work on this port. However, I'm not responsible if your save somehow corrupts!

## Controls

<div align="center">

![layout](assets/inputs.png)

</div>

- **Basic touchscreen support is implemented.**
- **On-screen keyboard support implemented for names and saves.**

## Configuration

- **Cursor Sensitivity**: Adjustable in options via mouse sensitivity. Note this will affect cursor speedup as well.
- **Resolution**: You can configure resolution and scaling through a config file. Create a file in your `fallout2` folder called `fallout2_nx.ini` - It needs to follow the following structure:

```ini
[MAIN]
SCR_WIDTH=1708
SCR_HEIGHT=960
SCALE_2X=1
; Change resolution and determine scaling. SCALE_2X=1 will turn 2x scaling on. SCALE_2X=0 will turn it off. 

[IFACE]
IFACE_BAR_MODE=0
IFACE_BAR_WIDTH=800
IFACE_BAR_SIDE_ART=1
IFACE_BAR_SIDES_ORI=0
; I wouldn't change these if you don't know what you're doing. Related to the interface bar.`
```

## Issues

If you encounter any issues, please create an issue ticket, and I'll look into it when I have time. Other contributors are welcome to assist in solving and fixing issues if interested.

## Questions

- **Fallout 1 wen?**

> When I get some time 🙂

## Credits

- **Interplay**: For developing and publishing the original game.
- **alexbatalov and fallout2-CE Contributors**: For their excellent work in keeping this game modern.
- **Romane**: For the graphics.
- **Tiwaz and Caleb Orchard**: For testing.

Much appreciated to all.
