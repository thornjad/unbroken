# Unbroken

Unbroken is a flat light theme based on Arc for GTK 3 based desktop environments like Cinnamon, Gnome, Unity, Budgie, Pantheon, XFCE, Mate, etc.

##### Unbroken

![A screenshot of the Unbroken theme]()

## Installation

### Supported Desktop Enviroments

  * `Antergos` (Gnome)
  * `Arch`
  * `Budgie`
  * `Cinnamon` (Updated version)
  * `Elementary OS`
  * `Fedora` (Gnome)
  * `Manjaro`
  * `Mate` (3.14 or later)
  * `Unity` (7.4 or later)
  * `Xfce`

### Supported GTK version
  * `GTK 3.14`
  * `GTK 3.16`
  * `GTK 3.18`
  * `GTK 3.20`
  * `GTK 3.22`

### Supported Ubuntu OS versions
  * `14.04 LTS`
  * `16.04 LTS`
  * `16.10`

--

### Manual Installation

How To Install:

1. Download

2. Extract to /usr/share/themes or ~/.themes (create it (in your home folder) if necessary)

3. Change via distribution specific tweak tool


**Note:** If your distribution doesn't ship separate development packages you just need GTK 3 instead of the `-dev` packages.

For the theme to function properly, install the following
* Gnome Shell, GTK 3.14 - 3.22
* The `gnome-themes-standard` package
* The murrine engine. This has different names depending on your distro.
  * `gtk-engine-murrine` (Arch Linux)
  * `gtk2-engines-murrine` (Debian, Ubuntu, elementary OS)
  * `gtk-murrine-engine` (Fedora)
  * `gtk2-engine-murrine` (openSUSE)
  * `gtk-engines-murrine` (Gentoo)


After the installation is complete you can activate the theme from the settings menu, or with `gnome-tweak-tool` or a similar program by selecting `Unbroken` as Window/GTK+ theme and `Unbroken` as Gnome Shell/Cinnamon theme.

## Uninstall

Run

```
sudo rm -rf /usr/share/themes/Unbroken
```

## Extras

### Unbroken Firefox theme
A theme for Firefox is available at https://github.com/horst3180/arc-firefox-theme

### Unbroken icon theme
The Unbroken icon theme is available at https://github.com/horst3180/arc-icon-theme

### Chrome/Chromium theme
To install the Chrome/Chromium theme go to the Extra folder and drag and drop the unbroken.crx file into the Chrome/Chromium window. The source of the Chrome themes is located in the source folder Unbroken/extra/Chrome/unbroken.crx.

### Plank theme
To install the Plank theme, copy the `extra/Unbroken-Plank` folder to `~/.local/share/plank/themes` or to `/usr/share/plank/themes` for system-wide use.
Now open the Plank preferences window by executing `plank --preferences` from a terminal and select `Unbroken-Plank` as the theme.

## Troubleshooting

If you have Ubuntu with a newer GTK/Gnome version than the one included by default (i.e Ubuntu 14.04 with GTK 3.14 or Ubuntu 15.04 with GTK 3.16, etc.) you have to install the theme manually as described above.
This is also true for other distros with a different GTK/Gnome version than the one included by default

---

If you get artifacts like black or invisible backgrounds under Unity, disable overlay scrollbars with

```
gsettings set com.canonical.desktop.interface scrollbar-mode normal
```


## Bugs
Bugs should be reported on the [issues page](https://github.com/raindeer44/Unbroken/issues)

## License
Unbroken is available under the terms of the MIT license. See `LICENSE` for details.

Unbroken is based on [OSX White Theme by LinxGem33](https://github.com/LinxGem33/OSX-Arc-White)
