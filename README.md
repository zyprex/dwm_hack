# dwm get source files

```shell
git clone https://git.suckless.org/dwm
```

# show dwm in lightdm login screen

```shell
echo -e \
"[Desktop Entry]\n\
Encoding=UTF-8\n\
Name=dwm\n\
Comment=dwm window manager\n\
Exec=/usr/local/bin/dwm\n\
Type=Application\n" > /usr/share/xsessions/dwm.desktop
```

# change dwm status bar

```shell
echo "dwm3s &" >> ~/.xinitrc
```

```shell
setxkbmap -option caps:swapescape
xset b off
```

```shell
pkill dwm3s nohup ./dwm3s &
```


# find other patch

[https://dwm.suckless.org/patches/](https://dwm.suckless.org/patches/)

