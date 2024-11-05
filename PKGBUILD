pkgname=xkb-dvorak
pkgver=0.0.1
pkgrel=1
pkgdesc="xkb config but the US keyboard is replaced with Dvorak"
arch=('any')
depends=('xkeyboard-config' 'python' 'pacman')
source=()
license=('BSD')
sha256sums=()

package() {
	install -Dm755 ../restore "$pkgdir/usr/share/$pkgname/restore"
	install -Dm644 ../xkb-dvorak.hook "$pkgdir/usr/share/libalpm/hooks/xkb-dvorak.hook"
}
