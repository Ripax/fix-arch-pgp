pkgname=fix-arch-pgp
pkgver=1.1.1
pkgrel=1
pkgdesc="Professional Arch Linux pacman PGP repair utility with auto-detection and logging"
arch=('any')
url="https://github.com/Ripax/fix-arch-pgp"
license=('MIT')
depends=('pacman' 'gnupg')
optdepends=('reflector: mirror optimization support')
source=("$pkgname-$pkgver.tar.gz::https://github.com/Ripax/fix-arch-pgp/archive/refs/tags/v$pkgver.tar.gz")
sha256sums=('REPLACE_WITH_REAL_HASH')

package() {
    cd "$srcdir/$pkgname-$pkgver"

    install -Dm755 fix-arch-pgp \
        "$pkgdir/usr/bin/fix-arch-pgp"

    install -Dm644 fix-arch-pgp.1 \
        "$pkgdir/usr/share/man/man1/fix-arch-pgp.1"

    install -Dm644 LICENSE \
        "$pkgdir/usr/share/licenses/$pkgname/LICENSE"

    install -Dm644 README.md \
        "$pkgdir/usr/share/doc/$pkgname/README.md"
}