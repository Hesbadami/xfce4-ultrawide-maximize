A simple shell script useful for users with ultra-wide monitors who find the default maximize behavior too wide.

### The script:
* Resizes the active window to 60% of the screen width>
* Fills the screen height, accounting for the title bar and borders.
* Keeps the window's original position.
* Ensures the window doesn't exceed screen boundaries.

### Requirements:
* `xdotool`: To get window geometry.
* `xprop`: To retrieve window frame extends.
* `wmctrl`: To resize and move windows.

### Usage:
1. Make the script executable:
```sh
chmod +x widemaximize
```
2. Move to PATH
3. Assign a suitable keyboard shortcut such as `Super+F`
