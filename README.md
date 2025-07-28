# Ardorcontrolcenter
Linux control center for ardor/celvo and tuxedo laptops

I noticed that Tuxedo Control Center is ideal for laptops from Ardor and Kelvo and others on Linux

[Github repo](https://github.com/tuxedocomputers/tuxedo-control-center) | [Official website](https://www.tuxedocomputers.com/en/Add-TUXEDO-software-package-sources.tuxedo)

Quick install for arch:

sudo pacman -S --needed git base-devel
git clone https://aur.archlinux.org/yay.git
cd yay
makepkg -si
yay -Syu
yay -S tuxedo-control-center-bin tuxedo-drivers-dkms linux-headers

Tuxedo tools (optional)
yay -S tuxedo-webfai-creator-bin
