# fix-arch-pgp

Professional Arch Linux PGP and pacman signature repair utility.

## Features

- Auto-detect broken keyring (`--auto-detect`)
- Quick repair mode (`--quick`)
- Dry-run mode (`--dry-run`)
- Force mode (`--force`)
- Mirror optimization with reflector
- Logging to `/var/log/fix-arch-pgp.log`
- Man page support
- AUR-ready packaging

---

## Installation (Manual)

```bash
git clone https://github.com/Ripax/fix-arch-pgp.git
cd fix-arch-pgp
makepkg -si
```
