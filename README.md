# Keyboard settings

Personal config for Sweep High:
https://github.com/davidphilipbarr/Sweep

## Flashing

```bash
sudo mount -o uid=$(id -u),gid=$(id -g) /dev/sda ~/Mnt
nix run .#flash
```
