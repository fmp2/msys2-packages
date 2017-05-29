# msys2-packages
Personal packages for Windows

## Register repository
```shell
baseurl=https://github.com/fmp2/msys2-packages/raw/master
wget -q -O /etc/pacman.d/fmp2-packages.mingw32 ${baseurl}/fmp2-packages.mingw32
wget -q -O /etc/pacman.d/fmp2-packages.mingw64 ${baseurl}/fmp2-packages.mingw64
wget -q -O /etc/pacman.d/fmp2-packages.msys ${baseurl}/fmp2-packages.msys
wget -q -O - ${baseurl}/fmp2-packages.conf >> /etc/pacman.conf
pacman -Sy
```
