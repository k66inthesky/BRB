<h1 align="center">
  BRB
  <img src="/wallpaper/Logo.ico" alt="BRB logo" ></img>
</h1>
<h3 align="center">Immediately tell people you will Be Right Back(BRB), in conference or write a bulletin note.</h3>
<p align="center">
  <img src="/wallpaper/BRB.png" alt="BRB logo" height="400" width="600" ></img>
</p>

<!--
<p align="center">
    <a href="https://github.com/k66inthesky">
        <img alt="Github Follow" src="https://play.google.com/store/apps/details?id=com.github.android&hl=zh_TW">
    </a>
    <a href="https://www.youtube.com/@k66inthesky">
        <img alt="Youtube Follow" src="https://play.google.com/store/apps/details?id=com.google.android.youtube&hl=zh_TW">
    </a>
</p>
<p align="center">
  <img alt="PyPI - Python Version" src="https://img.shields.io/pypi/pyversions/protonvpn-gui?color=Yellow&label=python&logo=Python&logoColor=Yellow">
</p>
<p align="center">
    <a href="https://github.com/k66inthesky/BRB/issues">
      <img alt="Issues"></img>
    </a>
    <a href="https://github.com/k66inthesky/BRB/actions/new">
      <img alt="Actions"></img>
    </a>
</p>
<p align="center">
  <a href="https://github.com/k66inthesky/BRB/blob/master/LICENSE">
    <img alt="License"></img>
  </a>
</p>

-->

***Disclaimer: BRB GUI currently support <u>(Gnome Desktop)</u>. In the near future we plan to support Windows/MacOS and more Linux Desktops.***


## Table of Contents
- [Demo Video](#demo-video)
- [Dependencies](#dependencies)
    - [Python dependencies](#python-dependencies)
    - [GUI dependencies](#gui-dependencies)
- [Run](#run)
  - [Linux](#linux)
  
# Demo Video
https://github.com/k66inthesky/BRB/assets/45890492/9cc61814-ccc2-4a3c-a8a3-da4235cc6b63


### Dependencies

#### Python dependencies
- python >= 3.9
- gi = 3.44.1

#### GUI dependencies
| **Distro**                              | **Command**                                                                                                     |
|:----------------------------------------|:---------------------------------------------------------------------------------------|
|Fedora/CentOS/RHEL                       | `sudo dnf install -y python3-gobject gtk3`                                                                      |
|Ubuntu/Linux Mint/Debian and derivatives | `sudo apt install -y python3-gi python3-gi-cairo gir1.2-gtk-3.0`                                                |
|OpenSUSE/SLES                            | `sudo zypper install python3-gobject python3-gobject-Gdk typelib-1_0-Gtk-3_0 libgtk-3-0`                        |
|Arch Linux/Manjaro                       | `sudo pacman -S python-gobject gtk3` 

# Run
#### Linux
```
./BRB-linux_1.0.0
```

