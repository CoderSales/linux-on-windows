# linux-on-windows

![Tux, the Linux mascot](/assets/images/tux.png)

wsl

## open terminal

cmd > As admin

## list windows subsystem for linux distributions installed

### This list gives Linux Distro's Installed

``` bash
wsl --list --verbose
```

``` bash
wsl
```

``` bash
rmdir /s /q \\wsl$\DistroNameFromListAbove
```

After this if distro was previously installed,
use shortcut to launch distro,
and it may install automatically.

(Alternatively, may have to install Distro on Windows.)

____
____

## Other notes / issues

### Alpine ~# sudo -i

``` bash
sudo -i
```

gives 

``` bash
-ash: sudo: not found
```

on Alpine.

## References

- [ChatGPT3.5](https://chat.openai.com/chat)

### Linux image

- [linux logo | horizontal rule in markdown](https://www.markdownguide.org/basic-syntax/)
- [File:Tux.png](https://en.wikipedia.org/wiki/File:Tux.png)
- [Tux (mascot)](https://en.wikipedia.org/wiki/Tux_%28mascot%29)
