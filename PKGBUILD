pkgname=fix-arch-pgp
pkgver=1.1.1
pkgrel=1
pkgdesc="Professional Arch Linux pacman PGP repair utility"
arch=('any')
url="https://github.com/Ripax/fix-arch-pgp"
license=('MIT')
depends=('pacman' 'gnupg')
optdepends=('reflector: mirror optimization support')
source=("https://github.com/Ripax/fix-arch-pgp/archive/v$pkgver.tar.gz")
sha256sums=('f5aef3cf5460b886b061e45ffefad40bc37f302ec9c3042a512536cade7ce0c2')

package() {
    cd "$srcdir/$pkgname-$pkgver"

    install -Dm755 fix-arch-pgp \
        "$pkgdir/usr/bin/fix-arch-pgp"

    install -Dm644 fix-arch-pgp.1 \
        "$pkgdir/usr/share/man/man1/fix-arch-pgp.1"

    install -Dm644 LICENSE \
        "$pkgdir/usr/share/licenses/$pkgname/LICENSE"
}