# Gentoo Linux
My current Gentoo settings and other shenanigans.

## PACKAGE.USE
```bash
sys-kernel/installkernel grub dracut
app-admin/doas persist
x11-base/xorg-server -suid
media-video/pipewire sound-server pipewire-alsa
x11-misc/dunst dunstify
x11-misc/polybar alsa doc ipc mpd network pulseaudio
dev-qt/qtmultimedia qml
dev-qt/qt5compat qml
```

## PACKAGE.ACCEPT_KEYWORDS
```bash
sys-kernel/gentoo-sources ~amd64
```

## Custom Overlays (with eselect-repository)
```bash
[136] gentoo
[155] guru
[252] nymphos
[271] pf4public
[351] steam-overlay
[369] tastytea
```

## Gentoo Specific Setup
```bash
USE flags: https://www.gentoo.org/support/use-flags/?style
Package List: https://packages.gentoo.org/categoriesc

AMDGPU: https://wiki.gentoo.org/wiki/AMDGPU
Hardware Acceleration: https://wiki.gentoo.org/wiki/Xorg/Hardware_3D_acceleration_guide
X.org: https://wiki.gentoo.org/wiki/Xorg
Non-root X.org: https://wiki.gentoo.org/wiki/Non_root_Xorg
PipeWire: https://wiki.gentoo.org/wiki/PipeWire

Steam: https://wiki.gentoo.org/wiki/Steam

QEMU: https://wiki.gentoo.org/wiki/QEMU
Libvirt: https://wiki.gentoo.org/wiki/Libvirt

NTFS: https://wiki.gentoo.org/wiki/NTFS
AutoFS: https://wiki.gentoo.org/wiki/AutoFS
UDisks: https://wiki.gentoo.org/wiki/Udisks

Installation: https://www.youtube.com/watch?v=eOXJrL5mZfs
Kernel Update: https://www.youtube.com/watch?v=PYQpJTVm5K4
Switching from rsync to git: https://www.youtube.com/watch?v=996q4Jn919k
Gentoo tips: https://www.youtube.com/watch?v=i03jDrJrHYE
```
