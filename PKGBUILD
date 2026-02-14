pkgname=fix-arch-pgp
pkgver=2.0.0
pkgrel=1
pkgdesc="Professional Arch Linux PGP and pacman signature repair utility"
arch=('any')
url="https://github.com/yourname/fix-arch-pgp"
license=('MIT')
depends=('pacman' 'gnupg')
optdepends=('reflector: for automatic mirror refresh')
source=('fix-arch-pgp' 'man/fix-arch-pgp.1')
sha256sums=('SKIP' 'SKIP')

package() {
    install -Dm755 fix-arch-pgp "$pkgdir/usr/bin/fix-arch-pgp"
    install -Dm644 man/fix-arch-pgp.1 "$pkgdir/usr/share/man/man1/fix-arch-pgp.1"
}