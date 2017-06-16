---
layout: post
title:  "Installing CUDA 8.0"
---

Today, I tried to install CUDA 8.0 (along with NVidia driver)
on Ubuntu 16.04.
Previously I mistakenly chose to not install the OpenGL library
that shipped with the installer.
This made OpenGL based applications that I often used (Xcrysden
and Avogadro) failed to start.

To install the driver, I need to disable or blacklist Nouveau.

I also need to stop X server:
```
sudo service stop lightdm
```
I need to call this command **after** going to
background terminal via `Ctrl+Alt+F2`.
If I call this from the usual session, X server will stop but I could
not access background terminal after that and forced to do hard restart.
I do not know yet the reason.

In the background terminal I can finally start the installation of
the driver. I simply answered yes to all questions and
choose the default settings offered by the installer.
The installation went smoothly and finally I can run OpenGL applications
again.
