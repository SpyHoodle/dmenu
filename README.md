# dmenu
My perfect build of suckless's dmenu. Designed for my build of dwm, [perfectwm](https://github.com/SpyHoodle/perfectwm).

![dmenu screenshot](https://file.coffee/u/4hxT5TKONwrZm0.png)

# patches
- dmenu-mousesupport-5.1.diff
- dmenu-numbers-4.9.diff

# installation
Clone the git repository
```sh
git clone https://github.com/SpyHoodle/dmenu
```
Change directory to dmenu
```sh
cd dmenu
```
Make and install dmenu
```sh
make install
```
**Final step:** Add a colourscheme to `~/.config/cols/dmenu.h`. This is where dmenu will read a colorscheme.<br>
This should be in the usual form dmenu would have a colourscheme in it's own source code, as `dmenu.h` is included at compile time.<br>
Alternatively, you could change the location of the colourscheme in `config.h`.
