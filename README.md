PKGBUILDs (outdated!)
=====================

PKGBUILDs for the ArchLinux AUR

**IMPORTANT:** I do not maintain this Github repository anymore. Since the switch to AUR4, every AUR-package resides in its own git repository, so I'll use that instead of duplicating everything here. You can browse the Package git repo at:

```
https://aur.archlinux.org/cgit/aur.git/?h=PACKAGENAME
```

You can clone it via:

```bash
git clone https://aur.archlinux.org/PACKAGENAME.git/
```

If you commit any changes, feel free to send me a patch:

```bash
$ mksrcinfo
$ git add PKGBUILD .SRCINFO
$ git commit -m 'My changes'
$ git format-patch origin
```
