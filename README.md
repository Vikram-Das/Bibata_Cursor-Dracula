<p align="center">
  <img src="https://imgur.com/852r65D.png" width="150">
  <br />
  <img src="https://imgur.com/g60k2RA.png" width="150">
</p>

<p align="center">
  🚀 Material Based Cursor 🏳️‍🌈
</p>

<!-- Badges -->

<p align="center">

  <!-- First Row -->
  <img alt="Travis CI" src="https://travis-ci.org/KaizIqbal/Bibata_Cursor.svg?branch=master">
  
  <a href="https://github.com/ful1e5/Bibata_Cursor/blob/master/LICENSE" >
    <img alt="License" src="https://img.shields.io/github/license/ful1e5/Bibata_Cursor?color=0081FB" />
  </a>

  <a href="https://github.com/KaizIqbal/Bibata_Cursor/releases" >
    <img alt="GitHub release (latest by date)" src="https://img.shields.io/github/v/release/KaizIqbal/Bibata_Cursor">
  </a>
  
  <a href="https://aur.archlinux.org/packages/bibata-cursor-theme" >
    <img alt="AUR version" src="https://img.shields.io/aur/version/bibata-cursor-theme">
  </a>
  
  <!-- Second Row -->
  <br />
  <a href="https://github.com/ful1e5">
    <img alt="Made By Kaiz"  src="https://kaiz.vercel.app/api/badge" width="133" />
  </a>
</p>

---

## Bibata ?

Bibata is **OpenSource**, Compact and Material Designed Cursor set. This project masterelop for improve `Cursor` Experience.

- **Bibata Classic :** Solid Black Theme. (![#000000](https://placehold.it/15/000000/000000?text=+) `#000000`)
- **Bibata Oil :** Gnome Adwaita's Color based Theme. (![#272728](https://placehold.it/15/272728/000000?text=+) `#272728`)
- **Bibata Ice :** Light Theme. (![#ffffff](https://placehold.it/15/ffffff/000000?text=+) `#ffffff`)
- **Bibata Amber :** Yellowish Theme. (![#FF8300](https://placehold.it/15/FF8300/000000?text=+) `#FF8300`)

<!-- Table Of Content -->
<details>
 <summary><strong>Table of Contents</strong> (click to expand)</summary>

- [Bibata Cursor](#bibata-?)
- [Install](#install)
- [Windows](#windows)
- [Preview](#preview)
- [Contributors](CONTRIBUTING.md#contributors)
- [Credit](#credit)
- [Support](#support)
- [License](LICENSE)

</details>

### Build dependencies

- [git](https://git-scm.com/)
- [python3](https://www.python.org/)
- [pip](https://pypi.org/project/pip/)/[python-pillow](https://www.archlinux.org/packages/community/x86_64/python-pillow/)
- [Inkscape](https://inkscape.org/)
- [Xcursorgen](https://www.x.org/releases/X11R7.7/doc/man/man1/xcursorgen.1.xhtml)

### Install dependencies

**📝Note**: Snap/Flatpak packages raise issue in build (e.g. inkscape).

##### Debian/Ubuntu

```shell
sudo apt install git python3 python3-pip inkscape x11-apps
```

##### Fedora

```shell
sudo dnf install git python37 python3-pip inkscape xcursorgen
```

##### Arch Linux/Manjaro

```shell
sudo pacman -S git python-pillow inkscape xorg-xcursorgen
```

## Install

### Basic Installation

Bibata cursor is installed by running one of the following commands in your terminal. You can install this via the command-line with either `curl` or `wget`.

##### via curl

```shell
sh -c "$(curl -fsSL https://raw.githubusercontent.com/KaizIqbal/Bibata_Cursor/master/Bibata.sh)"
```

##### via wget

```shell
sh -c "$(wget -O- https://raw.githubusercontent.com/KaizIqbal/Bibata_Cursor/master/Bibata.sh)"
```

Latest `Stable` & `Development` releases can be downloaded from [Here](https://github.com/KaizIqbal/Bibata_Cursor/releases)

### Packages📦

**📝Note**: If you're having trouble with the packages please submit a request to the package maintainer before creating an issue.

#### Arch Linux/Manjaro

Arch Linux/Manjaro users can install from the [AUR](https://aur.archlinux.org/packages/bibata-cursor-theme) currently maintained by [_@Shatur_](https://aur.archlinux.org/packages/?K=Shatur&SeB=m). Can be installed via Pamac (preinstalled in Manjaro), Yay or any other [AUR helper](https://wiki.archlinux.org/index.php/AUR_helpers).

Pamac command:

```shell
pamac install bibata-cursor-theme
```

Yay command:

```shell
yay -S bibata-cursor-theme
```

#### Fedora

Fedora users can install from the [copr-repo](https://copr.fedorainfracloud.org/coprs/muhalantabli/copr-repo) currently maintained by _@muhalantabli_.

Enable the repo:

```shell
sudo dnf copr enable muhalantabli/copr-repo
```

Installation command:

```shell
sudo dnf install bibata-cursor-theme
```

<!--
From https://github.com/Silicasandwhich/Bibata_Cursor_Translucent#windows -->

#### Windows

1. Get the lastest stable/dev-version Windows release from the [releases tab](https://github.com/KaizIqbal/Bibata_Cursor/releases) on the github page.

2. Open the settings app.

3. Go to Devices -> Mouse -> Additional Mouse Options.

4. Go to the pointers tab.

5. Replace each cursor in the currently applied cursor set with the corresponding cursor in the Windows folder of your desired flavor.

6. Click "save as" and type in the desired name.

7. Click "apply" and "ok".

### Manual Installation

1. Make sure you have installed all [Build dependencies](#build-dependencies).

2. Build & Install:
   ```shell
   git clone https://github.com/KaizIqbal/Bibata_Cursor.git
   cd Bibata_Cursor/
   chmod +x build.sh
   ./build.sh
   chmod +x ./install.sh
   ```
   Install (available for all users):
   ```shell
   sudo ./install.sh
   ```
   Install (available only for local user):
   ```
   ./install.sh
   ```
3. Uninstall:

   Using `Script` :

   ```shell
   #From All Users
   sudo ./install.sh
   #From Local User
   ./install.sh
   ```

   Without `Script` :

   ```shell
   #From All Users
   $sudo rm -r /usr/share/icons/Bibata_*
   #from Local User
   $rm -r ~/.icons/Bibata_*
   #Note : Your replace * with flavor Name to remove individual
   ```

More information about script is found in [src](./src/README.md) directory.

## Preview

<p align="center"><img title="Bibata Classic" src="./image/Bibata_Classic.png">
</br><sub>Bibata Classic</sub></p>

<p align="center"><img title="Bibata Oil" src="./image/Bibata_Oil.png">
</br><sub>Bibata Oil</sub></p>

<p align="center"><img title="Bibata Ice" src="./image/Bibata_Ice.png">
</br><sub>Bibata Ice</sub></p>

<p align="center"><img title="Bibata Amber" src="./image/Bibata_Amber.png">
</br><sub>Bibata Amber</sub></p>

## You may also like...

- [**Bibata Extra**](https://github.com/KaizIqbal/Bibata_Extra_Cursor) - More Bibata!
- [**Bibata Adapta**](https://gitlab.com/cscs/Bibata_AdaptaBreath_Cursors) - Bibata Based Cursor Made for AdaptaBreath and Manjaro.
- [**Bibata Translucent**](https://github.com/Silicasandwhich/Bibata_Cursor_Translucent) - Bibata translucent is a translucent flavor of the Bibata.

## Bugs

Bugs should be reported [here](https://github.com/KaizIqbal/Bibata_Cursor/issues) on the Github issues page.

## Getting help

You can create a issue, I will help you.

## Contributions and Suggestions

<a href="https://github.com/KaizIqbal/Bibata_Cursor/graphs/contributors">
  <img alt="GitHub contributors" src="https://img.shields.io/github/contributors/KaizIqbal/Bibata_Cursor?style=social">
</a>

Check [CONTRIBUTING.md](./CONTRIBUTING.md), any suggestions for features and contributions to the continuing code masterelopment can be made via the issue tracker or code contributions via a `Fork` & `Pull requests`.

###

## Credit

- [Adwaita](https://github.com/GNOME/adwaita-icon-theme)
- [Dmz](https://github.com/GalliumOS/dmz-cursor-theme)
- [Yaru](https://github.com/ubuntu/yaru)
- Emojis are taken from [here](https://emojipedia.org/)

## Support

**Give a ❤️**

**OR**

<a href="https://www.buymeacoffee.com/Nt7Wg4V" >
<img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" >
</a>
<br><br>
<a href="https://www.patreon.com/bePatron?u=13184396" >
<img src="https://c5.patreon.com/external/logo/become_a_patron_button@2x.png" alt="Patreon" width=174 height=41 style="box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" >
</a>
<br><br>
<a href="https://www.pling.com/p/1197198/" >
<img src="https://www.pling.com/images_sys/store_pling/pling-logo.png" alt="Pling" width="150" height="81" style="box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;">
</a>

<p align="center">
  <h1 align="center">.^.</h1>
</p>
