# DragonOS Installation Guide for Valve Steam Deck

This guide will walk you through the steps to install DragonOS on your Valve Steam Deck. DragonOS is a Linux distribution tailored for digital signal processing (DSP) and software-defined radio (SDR) enthusiasts.

## Installation Notes

## Display Orientations

To adjust display orientations on your DragonOS installation, follow these commands:

- **Change screen orientation in current boot**:
```bash
xrandr -o right
```

- **Orient touch screen in current boot**:
```bash
xinput set-prop "FTS3528:00 2808:1015" --type=float "Coordinate Transformation Matrix" 0 1 0 -1 0 1 0 0 1
```

  - Look for "FTS3528:00", it might be the last item under “Virtual core pointer” in your system.

## Additional Resources
