# repo-v32

this repository contains ports of packages of the virbos32 repository

# packages:
- alacritty-sixel
- maxfetch
- ninvaders
- virbos-livescripts
- virbos-logos
- virbos-utils
- yay

# packages(removed):
- vscodium32 - very old + slow
- vscodium - no longer supported on i686(if someone ever insists i might build a vscodium 1.6x) using skills
- librewolf - build issues and firefox is there

# adding this repo:

you can add this repository on any arch32 install as long as it has sse2

add this to `/etc/pacman.conf`
```note
[virbos32]
SigLevel = Never TrustAll
Server = https://virbos32.github.io/repo-v32/$arch
```
