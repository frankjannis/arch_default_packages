```
curl -s https://raw.githubusercontent.com/frankjannis/arch_default_packages/refs/heads/main/packages.txt \
| sed 's/#.*//' \
| xargs sudo pacman -S --needed --noconfirm --
```
