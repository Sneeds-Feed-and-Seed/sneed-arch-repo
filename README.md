# sneed-arch-repo

AUR Replacement for the Sneed Suite of Feed

## usage
add the following to your /etc/pacman.conf:
```ini
[sneed-arch-repo]
SigLevel = Optional TrustAll
Server = https://repo.swurl.xyz/sneed/arch/x86_64
```
refresh package repos and update: `pacman -Syu`
