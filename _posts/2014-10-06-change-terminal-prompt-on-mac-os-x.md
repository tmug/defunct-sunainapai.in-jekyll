---
layout: post
title:  "Change Terminal prompt in Mac OS X"
---

When you open a Terminal in Mac OS X, the default command prompt
displayed is a very long name which goes like this:
`<ComputerName>:<CurrentDirectory> <UserName>$`. In my case it was
`Sunainas-MacBook-Pro:~ sunaina$`, quite boring!

I prefer something like `sunaina@MacBook:~$`, commonly used in the Linux
world. I did the following customizations.

* On Terminal, execute the following commands.

      sudo scutil --set ComputerName "MacBook" 
      sudo scutil --set LocalHostName "MacBook"
      sudo scutil --set HostName "MacBook"
  
  The `ComputerName` and `LocalHostName` are also accessible as
  `Computer Name` and `Local Hostname` respectively, at `System
  Preferences > Sharing`. The `ComputerName`, `LocalHostName` and
  `HostName` are saved in
  `/Library/Preferences/SystemConfiguration/preferences.plist`.

* Edit the file `~/.bash_profile` with the following command. 
  
      mvim ~/.bash_profile

* Add the following line to `~/.bash_profile`, save and
  quit.

      export PS1="\u@\h:\w$ "

  Here,

  * `\u` stands for the username of the current user.
  * `\h` stands for the hostname upto the first '.'.
  * `\w` stands the current working directory.

* Open a new Terminal. You should see your customized prompt.

Play around with the [prompt
escapes](http://www.gnu.org/software/bash/manual/bashref.html#Printing-a-Prompt)
for the `PS1` shell variable and see what you prefer.
