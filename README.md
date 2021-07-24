# how to rice

This is guide on how to rice your wm/de in linux.

## Step 1 - choose a WM/DE

- WM - stand for window manger. It controls the placement of windows. It may be a floating wm like `openbox` or a tiling wm like i3 or a dynamic tiling wm like `bspwm`.

Read more about number of available wm in the arch wiki. WM are more customizable than DE, and they usually have a easily modifiable configuration file instead of some GUI configuration manager.

- DE - stands for desktop environment. 

> A desktop environment bundles together a variety of components to provide common graphical user interface elements such as icons, toolbars, wallpapers, and desktop widgets. Additionally, most desktop environments include a set of integrated applications and utilities. Most importantly, desktop environments provide their own window manager, which can however usually be replaced with another compatible one.  --Arch wiki

*Some* major DE are:

- Gnome
- KDE
- XFCE

## Step 2 - choose a color-scheme

This is most important step, you have to choose one color scheme which will define how your rice will look.

*Some* popular color scheme are:

- Nord - dimmed colors - is easy on eyes - bluish
- Dracula - bright colors - bluish
- Gruvbox - brown

## Step 3 - find a GTK theme, a theme for QT applications and some nice icon pack

For your rice to be consistent you have to find matching GTK and QT theme.

[Arch wiki link on how to make GTK and QT app look uniform](https://wiki.archlinux.org/title/Uniform_look_for_Qt_and_GTK_applications)

If you are unable to find a matching GTK them for the color scheme you can:
- make you own GTK using [phocus](https://github.com/phocus/gtk)
- use a GUI [oomox](https://github.com/themix-project/oomox) to create one

For QT apps on WM you can use [qt5ct](https://sourceforge.net/projects/qt5ct/) *this will be availiable in your pacakage manager*. If you are unable to found a matching qt theme, then you can:
- load a custom colors in `qt5ct`, (in Appearance tab in Palette group, a radio button `Custom`), these are stored in `~/.config/qt5ct/colors`
- install [kvantum-manager](https://github.com/tsujan/Kvantum/tree/master/Kvantum) and then select it as `Style:` in `qt5ct`, and then you can use `kvantum` themes too, select them using `kvantum-manager`

## Step 4 - fix color scheme of the wm or de, rice login-manager and choose a nice wallpaper

Now you need to fix the color of components of the wm or de, like title-bar, window-borders, windows-gaps, bar/panel, dock, lock screen, application launcher, terminal, widgets.

Now rice your login-manager/display-manager.

Now configure the compositor you are using.

Looking for alternatives tools or components check this [awesome-ricing](https://github.com/fosslife/awesome-ricing)

## Step 5 - set keybindings and mouse-bindings

Set the keybindings as you like them, this is most important for tiling window managers.

## Step 6 - set startup programs, make scripts, rice boot screen, boot animation

Add some `dmenu`/`rofi` scripts, so you can be more productive. e.g. add a script to open the configuration of tools you use in you favorite editor, this will save you lot of time.

## Step 7 - theme every application you use

Not you have to find a nice matching theme for your applications too.
Here is list of some applications you may have to rice:

- text editor
- browser, rice the home-page
- video player
- music player
- discord client -if you use discord
- telegram-desktop - if you use telegram
- you should also add some stylesheets to websites you use frequently, use this open-source extension [stylus](https://add0n.com/stylus.html)

## Step 8 - Create a backup of your configurations

You can use github, gitlab, host your own git server, or use some cloud storage for this.

✨ Keep Ricing