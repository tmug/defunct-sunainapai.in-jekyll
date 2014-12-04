---
layout: post
title:  "Swap caps lock key and escape key on Mac OS X"
---

I wanted to swap caps lock key and escape key to conveniently use
MacVim. These are the steps I followed.

* Download `Karabiner-10.4.0.dmg` from <https://pqrs.org/osx/karabiner>.
  (Note: The installer is for Mac OS X 10.9 (Mavericks) or later.)

* To install, double click on `Karabiner-10.4.0.dmg` and then open
  `Karabiner.pkg`. The Karabiner 10.4.0 installer is launched. Complete
  the installation process. Karabiner will be installed in
  `/Applications` folder. (Note: Do not change the location of
  Karabiner.app from /Applications.)
  
* Launch `Karabiner` from `Launchpad`.

* Download `Seil-10.11.0.dmg` from
  <https://pqrs.org/osx/karabiner/seil.html>. (Note: The installer is
  for Mac OS X 10.9 (Mavericks) or later.)

* To install, double click on Seil-10.11.0.dmg and then open the
  `Seil.pkg`. The Seil 10.11.0 installer is launched. Complete the
  installation process. Seil will be installed in `/Applications`
  folder. (Note: Do not change the location of Seil.app from
  /Applications.)

* Launch `Seil` from `Launchpad`.  

* Change keycode of caps lock to `110` on Seil.

    <figure>
        <a href="{{site.url}}/img/swap-capslockkey-and-escapekey-on-mac-os-x/seil-capslock-to-110.png"
           target="_blank"><img
                class="largeimage"
                src="{{site.url}}/img/swap-capslockkey-and-escapekey-on-mac-os-x/seil-capslock-to-110.png"
                alt="Screenshot of changing keycode of CapsLock to 110 in Seil"></a>
    </figure>

* Open `System Preferences > Keyboard > Modifier Keys` and change `Caps
  Lock` configuration to `No Action`. (Note: This is required to reduce
  the delay of the caps lock key.)

    <figure>
        <a href="{{site.url}}/img/swap-capslockkey-and-escapekey-on-mac-os-x/keyboard-capslock-to-noaction.png"
           target="_blank"><img
                class="largeimage"
                src="{{site.url}}/img/swap-capslockkey-and-escapekey-on-mac-os-x/keyboard-capslock-to-noaction.png"
                alt="Screenshot of changing Caps Lock configuration to No Action"></a>
    </figure>

* Activate `Application Key to Escape` on Karabiner.

    <figure>
        <a href="{{site.url}}/img/swap-capslockkey-and-escapekey-on-mac-os-x/karabiner-application-key-to-escape.png"
           target="_blank"><img
                class="largeimage"
                src="{{site.url}}/img/swap-capslockkey-and-escapekey-on-mac-os-x/karabiner-application-key-to-escape.png"
                alt="Screenshot of changing Application Key to Escape on Karabiner"></a>
    </figure>

* Activate `Escape to CapsLock` on Karabiner.

    <figure>
        <a href="{{site.url}}/img/swap-capslockkey-and-escapekey-on-mac-os-x/karabiner-escape-to-capslock.png"
           target="_blank"><img
                class="largeimage"
                src="{{site.url}}/img/swap-capslockkey-and-escapekey-on-mac-os-x/karabiner-escape-to-capslock.png"
                alt="Screenshot of changing Escape to CapsLock on Karabiner"></a>
    </figure>
