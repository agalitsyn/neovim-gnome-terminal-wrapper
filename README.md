neovim-gnome-terminal-wrapper
=============================

![screenshot](screenshot.gif)

For original repo see https://github.com/fmoralesc/neovim-gnome-terminal-wrapper

I've modified it for to my own needs, for example:

-	I don't need filetypes associations from DE, becasue I've never used it.
-	I don't need to open nvim right after startup, because I need to choose workdir.
-	For fast dir change I use https://github.com/rupa/z
-	But it's cool to have separate scope of terminals, I use it with tabs like an IDE, may be open several projects, maybe combine with other debugging tools or just app log.

Requisites
----------

-	neovim
-	gnome-terminal >= 3.16 (uses gnome-terminal-server)
-	python-dbus

Works well on Ubuntu 16.04

Setup
-----

Manually:

```
$ sudo cp nvim-wrapper.py /usr/local/bin/nvim-wrapper && chmod +x /usr/local/bin/nvim-wrapper
cp neovim.desktop /usr/share/applications/neovim.desktop
cp neovim.svg /usr/share/icons/neovim.svg
```
