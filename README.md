# msys2-packages
Personal packages for Windows

## Register repository
```shell
baseurl=https://github.com/dsogari/msys2-packages/raw/master
wget -q -O /etc/pacman.d/dsogari-packages.mingw32 ${baseurl}/dsogari-packages.mingw32
wget -q -O /etc/pacman.d/dsogari-packages.mingw64 ${baseurl}/dsogari-packages.mingw64
wget -q -O /etc/pacman.d/dsogari-packages.msys ${baseurl}/dsogari-packages.msys
wget -q -O - ${baseurl}/dsogari-packages.conf >> /etc/pacman.conf
pacman -Sy
```
