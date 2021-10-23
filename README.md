# Owen Gaspard's Dotfiles

My dotfiles for various programs I use in Linux.  Some are based off others' work.  Proper credit is given if that is the case.

## What are dotfiles?
Dotfiles get the name from the hidden config folder.  In *NIX operating systems, directories and files can be hidden by beginning the name with a period (.).  They are the configuration files for certain programs like tiling window managers, terminals, terminal programs, etc.

## Installation
I would advise that you do not directly clone this into your .config.  Look over everything, and copy what you want into your .config ONLY after you edit the configuration files (that won't work out of the box) to work for you.
```
git clone https://gitlab.com/ogaspard/dotfiles.git
cp -r <directory> ~/.config/
```

## Credit
Derek Taylor (DT) <br>
    - DT has been a huge inspiration for me to  start using Linux as a daily driver on my main  production machine and has made me endorse more FOSS software. <br>
    - https://gitlab.com/dwt1/ <br>
The EndeavourOS Team <br>
    - When I used EndeavourOS for a little while, I used their stock rofi config.  I have included it, but it may not work for your system.  I have switched to dmenu, and I think it works fine for me. <br>
    - https://endeavouros.org
## License
Everything in this repository is licensed under the MIT License. This allows you to quite literally whatever you want with it. The only requirement with the MIT License is that the license and copyright notice must be provided with the software.
