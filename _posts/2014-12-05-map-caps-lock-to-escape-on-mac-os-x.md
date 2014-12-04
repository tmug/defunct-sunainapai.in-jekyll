---
layout: post
title:  "Map caps lock to escape on Mac OS X"
---

I wanted to map the caps lock key to the escape key to conveniently use
MacVim. These are the steps I followed.

* Download `Seil-10.11.0.dmg` from
  <https://pqrs.org/osx/karabiner/seil.html>. (Note: The installer is
  for Mac OS X 10.9 (Mavericks) or later.)

* To install it, double click on `Seil-10.11.0.dmg` and then open the
  `Seil.pkg`. The Seil installer is launched. Complete the installation
  process with default options. Seil gets installed in `/Applications`
  folder.

* Launch Seil from Launchpad.  

* Change keycode of the caps lock key to *53* in the 'Change the caps
  lock key' section.

    <figure>
        <a
        href="{{site.url}}/img/map-caps-lock-to-escape-on-mac-os-x/seil-capslock-to-53.png"
           target="_blank"><img
                class="largeimage"
                src="{{site.url}}/img/map-caps-lock-to-escape-on-mac-os-x/seil-capslock-to-53.png"
                alt="Screenshot of changing keycode of caps lock to 53 in Seil"></a>
    </figure>

* In case you still want to use the caps lock feature, you may want to
  map the escape key to function as caps lock. To do so, change keycode of
  the escape key to *57* in the 'Other keys' section. This effectively
  swaps the caps lock key and the escape key.
  
    <figure>
        <a
        href="{{site.url}}/img/map-caps-lock-to-escape-on-mac-os-x/seil-escape-to-57.png"
           target="_blank"><img
                class="largeimage"
                src="{{site.url}}/img/map-caps-lock-to-escape-on-mac-os-x/seil-escape-to-57.png"
                alt="Screenshot of changing keycode of escape to 57 in Seil"></a>
    </figure>
