# Maintainer: swweetp <48543769+swweetp@users.noreply.github.com>
pkgname=udiskie-systemd
pkgver=1.0
pkgrel=1
epoch=
pkgdesc="systemd user service to start udiskie"
arch=('any')
url="https://github.com/swweetp/udiskie-systemd"
license=('MIT')
groups=()
depends=('udiskie')
makedepends=()
checkdepends=()
optdepends=()
provides=()
conflicts=()
replaces=()
backup=()
options=()
install=
changelog=
source=('udiskie.service'
		'LICENSE')
noextract=()
sha256sums=('d9b604334847a949273b277c0de6984874bb39e92011b12a3627f6448b678c1a'
            '9f00debbb4574fd2b767acd847fcf17c25bfb8d7cde63084801e94047b84e180')
validpgpkeys=()

package() {
	install -Dm644 "$srcdir/udiskie.service" -t "$pkgdir/usr/lib/systemd/user/"
	install -Dm644 "$srcdir/LICENSE" -t "$pkgdir/usr/share/licenses/$pkgname/"
}
