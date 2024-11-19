#BSPWM Window Manager Environment

## Very useful keybindigs to know...

| Keys                                                                                                                                                                                                     | Action                                                                |
| :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :-------------------------------------------------------------------- |
| <kbd>super</kbd> + <kbd>Enter</kbd><br><kbd>super</kbd> + <kbd>alt</kbd> + <kbd>Enter</kbd>                                                                                                              | Open a terminal<br>Open a floating terminal.                          |
| <kbd>alt</kbd> + <kbd>@space</kbd>                                                                                                                                                                       | Display menu to select a theme.                                       |
| <kbd>super</kbd> + <kbd>@space</kbd>                                                                                                                                                                     | Apps Menu.                                                            |
| <kbd>super</kbd> + <kbd>alt</kbd> + <kbd>w</kbd>                                                                                                                                                         | Opens a menu to select a wallpaper.                                   |
| <kbd>super</kbd> + <kbd>alt</kbd> + <kbd>h</kbd><br><kbd>super</kbd> + <kbd>alt</kbd> + <kbd>u</kbd>                                                                                                     | Hides bar/s<br>unhide bar/s                                           |
| <kbd>super</kbd> + <kbd>alt</kbd> + <kbd>s</kbd>                                                                                                                                                         | Takes screenshot.                                                     |
| <kbd>ctrl</kbd> + <kbd>alt</kbd> + <kbd>[plus,minus,t]</kbd>                                                                                                                                             | Changes transparency on focused window.                               |
| <kbd>ctrl</kbd> + <kbd>super</kbd> + <kbd>alt</kbd> + <kbd>p</kbd><br><kbd>ctrl</kbd> + <kbd>super</kbd> + <kbd>alt</kbd> + <kbd>r</kbd><br><kbd>ctrl</kbd> + <kbd>super</kbd> + <kbd>alt</kbd> + <kbd>k | Power off computer<br>Restart computer<br>Brute kill a window/process |
| <kbd>super</kbd> + <kbd>alt</kbd> + <kbd>r</kbd>                                                                                                                                                         | Restart bspwm.                                                        |
| `alt` + `F1`                                                                                                                                                                                             | Show keybinds cheatsheet                                              |

And more.. You need to look sxhkdrc file for more, or press Alt + F1 for a cheatsheet.

---

> [!CAUTION]
> ⚠️⚠️⚠️ My dotfiles are designed for a **1600x900** resolution with **96 DPI** on a single monitor.
> Some elements may appear different on higher or lower resolutions. You may need to make adjustments to adapt them to your preferences and setup. ⚠️⚠️⚠️

> [!important]
> ✏️✏️✏️ The installer assumes you already have a **functional** Arch Linux installation, whether it’s a fresh install or an existing setup.
>
> A login manager of your choice is required; **lightdm** is recommended.
>
> The rofi connection manager applet, works with **NetworkManager**
>
> If using a virtual machine, be sure to change the Picom backend from **glx** to **xrender** before rebooting, and verify that hardware acceleration is correctly configured in your VM. ✏️✏️✏️

> [!warning]
> :wrench::wrench::wrench: I have tested the installation and functionality of these dotfiles on both high- and low-end machines.
>
> Some adjustments may still be needed, such as changing the Picom backend or VSync settings to ensure compatibility with your graphics card.
>
> If you encounter any issues, feel free to open an [issue](https://github.com/gh0stzk/dotfiles/issues). :wrench::wrench::wrench:

---

### 💾 Installation:

> [!NOTE]
> The installer only works for **ARCH** Linux, and based distros.

- **Open a terminal in HOME and download the installer**
```sh
curl https://raw.githubusercontent.com/Jared0307/dotfiles/master/RiceInstaller -o $HOME/RiceInstaller
```
- **Now give it execute permissions**
```sh
chmod +x RiceInstaller
```
- **Finally run the installer**
```sh
./RiceInstaller
```
