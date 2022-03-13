# NetHack汉化

## 说明

## 编译平台支持

1.[Windows-VS](https://github.com/SunnyEric/NetHack-cn/blob/NetHack-cn/NetHack/sys/winnt/Windows-VS%E7%BC%96%E8%AF%91%E8%AF%B4%E6%98%8E.txt)

2.[Linux-Qt](https://github.com/SunnyEric/NetHack-cn/blob/NetHack-cn/NetHack/win/Qt4/Linux-Qt%E7%BC%96%E8%AF%91%E8%AF%B4%E6%98%8E.txt)

## linux的安装环境配置

(ubuntu 20.04的docker下)

```shellscript

sudo apt install byacc flex build-essential   qtmultimedia5-dev  qt5-default -y

```
不知道是为什么,我编译之后没有乱码但是有时候会`Segmentation fault (core dumped)`,刚好最近复习了编译原理,之后用`GDB`看下

- [ ] 解决Segmentation fault (core dumped)
- [ ] 制作appimage
