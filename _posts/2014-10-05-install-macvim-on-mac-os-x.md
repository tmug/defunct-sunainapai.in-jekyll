---
layout: post
title:  "Install MacVim on Mac OS X"
---

Download `MacVim-snapshot-73-Mavericks.tbz` from
<https://github.com/b4winckler/macvim/releases>. (Note: The binary
requires Mac OS X 10.9 (Mavericks) or later. It will not run on earlier
versions of Mac OS X!)

To install, drag the `MacVim.app` to the `Applications` folder. You are
good to go by double clicking this MacVim icon.

To start MacVim from Terminal, set the `PATH` enviroment variable to
include the location where the `mvim` script has to be found. To do this
move the `mvim` script to your favourite location, which in my case is
`/Users/sunaina/bin` and add this path to `/etc/paths`.

To set `PATH`, enter the following command on Terminal.

    sudo vi /etc/paths

Enter your password and you will see all the paths you have. Add `the
path to the mvim script` to this file, save and quit. Open a new
Terminal. You should be able to start MacVim from Terminal with the
following command.

    mvim

You can customize your MacVim to suit your needs. For doing this create a
`.vimrc` file at your home location. You can download my
customizations from <https://github.com/sunainapai/dotfiles>.
