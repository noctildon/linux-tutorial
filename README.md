# Content

- [Content](#content)
- [Linux ubuntu install](#linux-ubuntu-install)
    - [中文](#%E4%B8%AD%E6%96%87)
    - [English](#english)
- [Ubuntu mate install](#ubuntu-mate-install)
- [Speed up internet](#speed-up-internet)
    - [中文](#%E4%B8%AD%E6%96%87-1)
    - [English](#english-1)
- [Internet speedtest](#internet-speedtest)
- [Firewall](#firewall)
    - [中文](#%E4%B8%AD%E6%96%87-2)
    - [English](#english-2)
- [Mouse scroll](#mouse-scroll)
- [Chinese input 中文輸入法](#chinese-input-%E4%B8%AD%E6%96%87%E8%BC%B8%E5%85%A5%E6%B3%95)
- [WIFI hotspot](#wifi-hotspot)
- [Curose theme](#curose-theme)
- [Power save](#power-save)
- [PTT browser](#ptt-browser)
- [Latex](#latex)
- [Remove package](#remove-package)
- [DeaDBeeF(music player)](#deadbeefmusic-player)
- [Sublime Text](#sublime-text)
- [Firejail(sandbox)](#firejailsandbox)
- [Restart wifi manager](#restart-wifi-manager)
- [Check mint version](#check-mint-version)
- [Set alias](#set-alias)
- [CPU mode panel](#cpu-mode-panel)
- [Pdf reader in linux](#pdf-reader-in-linux)
- [Set firefox zoom level and sidebar](#set-firefox-zoom-level-and-sidebar)
- [Modify startup setting](#modify-startup-setting)
- [Swappiness](#swappiness)
- [Install software-center on mint](#install-software-center-on-mint)
- [Connect to wifi linux command](#connect-to-wifi-linux-command)
- [Read and write file to ipad/iphone](#read-and-write-file-to-ipadiphone)
- [Check vscode installed extensions](#check-vscode-installed-extensions)
- [Shutter (screenshot tool)](#shutter-screenshot-tool)
- [Install orage panel clock](#install-orage-panel-clock)
- [Install python virtual environment](#install-python-virtual-environment)
- [Install pyqt5 globally](#install-pyqt5-globally)
- [Install pyqt5 in virtualenv](#install-pyqt5-in-virtualenv)
- [Caja extension development](#caja-extension-development)
- [IPython](#ipython)
- [Install nvm(Node Version Manager)](#install-nvmnode-version-manager)
- [To do list](#to-do-list)



# Linux ubuntu install

## 中文
[中文安裝指引-純文字](https://wklchris.github.io/Win10-Ubuntu-dual-os.html#%E5%9B%9B%E5%88%B6%E4%BD%9C%E5%BC%95%E5%AF%BC-u-%E7%9B%98)

[中文安裝指引-圖文](https://blog.birkhoff.me/windows-10-and-ubuntu-14_04_3-lts-dual-boot/)

[中文安裝指引-影音1](https://www.youtube.com/watch?v=tA9OKOZqjdg)

[中文安裝指引-影音2](https://www.youtube.com/watch?v=rjpBTT6AmeU)

## English

To be added...


# Ubuntu mate install


[English tutorial-video](https://www.youtube.com/watch?v=-9nux6iKmjU)

[English tutorial-article](https://www.tecmint.com/install-mate-desktop-in-ubuntu-fedora/)


# Speed up internet

## 中文
[中文指引-命令列1](http://thaddeusnotes.blogspot.tw/2010/09/ubuntu-1004.html)

[中文指引-命令列2](https://shaoweicai.wordpress.com/2013/04/22/%E8%A7%A3%E5%86%B3ubuntu-%E4%B8%8A%E7%BD%91%E9%80%9F%E5%BA%A6%E6%85%A2%E7%9A%84%E9%97%AE%E9%A2%98/)

## English

To be added...


# Internet speedtest

```console
$ sudo apt-get install speedtest-cli
$ speedtest-cli --share # to measure the internet speed
```

# Firewall

## 中文

[中文指引-圖文1](http://it-easy.tw/ubuntu-firestarter/)

[中文指引-命令列1](https://www.peterdavehello.org/2016/01/ubuntu-based-gnulinux-firewall-ufw-essential-config/)

[中文指引-命令列2](https://www.cloudsgo.org/life/2016/07/ubuntu%E9%98%B2%E7%81%AB%E7%89%86ufw%E5%AE%89%E8%A3%9D%E6%95%99%E5%AD%B8%E8%88%87%E5%B8%B8%E7%94%A8%E6%8C%87%E4%BB%A4/)

[中文指引-命令列3](https://www.ubuntu-tw.org/modules/newbb/viewtopic.php?post_id=139762)

## English

To be added...

# Mouse scroll

Change the mouse scroll wheel speed

[English tutorial](http://www.webupd8.org/2015/12/how-to-change-mouse-scroll-wheel-speed.html)

# Chinese input 中文輸入法

[中文指引-圖文1](https://blog.xuite.net/yh96301/blog/287374341-Ubuntu+14.04%E5%AE%89%E8%A3%9D%E9%8D%B5%E7%9B%A4%E8%BC%B8%E5%85%A5%E6%B3%95%E7%B3%BB%E7%B5%B1gcin)

[中文指引-圖文2](http://goodjack.blogspot.com/2013/08/linux-phonetic-setting.html)


# WIFI hotspot

[中文指引-圖文](http://www.coctec.com/docs/linux/show-post-64702.html)


# Curose theme

```bash
$ sudo xed /usr/share/icons/default/index.theme
```

# Power save

[中文指引-圖文](https://0xhack.wordpress.com/2017/10/30/linux-ubuntu-16-04-%E7%AD%86%E9%9B%BB%E4%B8%8A%E7%9C%81%E9%9B%BB%E6%8B%9B%E6%95%B8/)


# PTT browser

```console
$ sudo apt-get install pcmanx-gtk2
```


# Latex

```console
$ sudo apt-get install texlive
$ sudo apt-get install texlive-full
$ cpan install File::HomeDir # install module for home folder path in perl
$ which latexindent # check if latexindent is installed
$ perl latexindent # check if latexindent works properly
```

# Remove package

[中文指引-命令列](http://blog.lyhdev.com/2013/01/ubuntu-linux-apt-get.html)


# DeaDBeeF(music player)

```console
$ sudo add-apt-repository ppa:starws-box/deadbeef-player
$ sudo apt-get update
$ sudo apt-get install deadbeef
```

# Sublime Text

1. download from the website(it should be zip)
2. unzip the zip file(it should be a folder)
3. move the folder to /opt
4. create .desktop file (@folder /usr/share/applications) (see an example at the [link](https://blog.csdn.net/gzy_0922/article/details/80081119))
5. install package control from the [link](https://packagecontrol.io/installation)


# Firejail(sandbox)

download from software manager

# Restart wifi manager

```console
$ sudo service network-manager restart
```

# Check mint version

```console
$ cat /etc/linuxmint/info
```

# Set alias

```console
$ echo "alias YourNewCommand='command'" >> ~/.bashrc
$ source ~/.bashrc
```

# CPU mode panel

```console
$ sudo apt-get install indicator-cpufreq
```

# Pdf reader in linux

- master pdf editor
- foxit reader
- qpdfview


# Set firefox zoom level and sidebar

1. addressbar : "about:config"
2. search "layout.css.devPixelsPerPx", "sidebar.position_start"
3. set value [(refence)](https://support.mozilla.org/zh-TW/questions/1147570)


# Modify startup setting

```console
$ /etc/default/grub
$ sudo update-grub
```

# Swappiness

[tutorial-command line](https://askubuntu.com/questions/103915/how-do-i-configure-swappiness)


# Install software-center on mint

[tutorial-article](https://delightlylinux.wordpress.com/2014/06/10/how-to-install-the-ubuntu-software-center-in-linux-mint-17/)

[tutorial-video](https://www.youtube.com/watch?v=vqtOjr_9SXY)

# Connect to wifi linux command

1. run $nmcli c
2. copy the UUID of the wifi
3. run $nmcli c up uuid <paste uuid here> [reference](https://unix.stackexchange.com/questions/92799/connecting-to-wifi-network-through-command-line)


# Read and write file to ipad/iphone

[中文指引-圖文](http://atelier-wini.blogspot.com/2015/03/iphone-jb-libimobiledevice-linux-mint.html)

# Check vscode installed extensions

```console
$ code --list-extensions
```
# Shutter (screenshot tool)

```console
$ sudo add-apt-repository ppa:shutter/ppa
$ sudo apt-get update
$ sudo apt-get install shutter
```

# Install orage panel clock

```console
$ sudo apt-get install orage
```

# Install python virtual environment

```console
$ sudo apt-get install python3.5-venv
$ python3.5 -m venv [myenv] # create virtual environment
```


# Install pyqt5 globally

```console
$ sudo apt-get install python3-pyqt5
$ sudo apt-get install pyqt5-dev-tools
$ sudo apt-get install qttools5-dev-tools
```

# Install pyqt5 in virtualenv

first install pyqt5 globally(i.e. run the above script), then run the following
```console
$ LIBDIR="/virtualenv_NAME/lib/python3.5/site-packages"
$ cp -r /usr/lib/python3/dist-packages/PyQt5 "$LIBDIR/PyQt5"
$ cp /usr/lib/python3/dist-packages/sip.cpython-35m-x86_64-linux-gnu.so "$LIBDIR/"
```

**path of QTDesigner might be "/usr/lib/x86_64-linux-gnu/qt5/bin/designer"**

[reference](http://www.nerdyweekly.com/posts/how-to-install-pyqt5-on-virtualenv-on-ubuntu-14.04/)


# Caja extension development

```console
$ sudo apt-get install caja-python
$ sudo apt-get install caja-pyextensions
```
see [website](https://www.giuspen.com/nautilus-pyextensions/)

# IPython

```console
$ sudo apt-get install ipython # install ipython for python 2
$ sudo apt-get install ipython3 # install ipython for python 3
```

# Install nvm(Node Version Manager)

Visit the [nvm github website](https://github.com/creationix/nvm) then run the installation script

[中文指引](https://medium.com/@wrre/%E5%AE%89%E8%A3%9Dnvm%E4%BE%86%E5%AE%89%E8%A3%9Dnode-js-9b4a9514552)

# To do list

- [ ] add more content
- [ ] add English version
- [ ] add the scripts I wrote
