# sneed-arch-repo

AUR Replacement for the Sneed Suite of Feed

## usage
add the following to your /etc/pacman.conf: (if you are on ARM architecture, replace `x86_64` with `aarch64`)
```ini
[sneed-arch-repo]
SigLevel = Optional TrustAll
Server = https://repo.swurl.xyz/sneed/arch/x86_64
```
refresh package repos and update: `pacman -Syu`

available packages: `sneedacity-bin`
