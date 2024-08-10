# Maintainer: swweetp <48543769+swweetp@users.noreply.github.com>
pkgname=udiskie-systemd
pkgver=0.1
pkgrel=1
epoch=
pkgdesc="systemd user service to start udiskie"
arch=('any')
url=""
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
source=("udiskie.service")
noextract=()
sha256sums=('d9b604334847a949273b277c0de6984874bb39e92011b12a3627f6448b678c1a')
validpgpkeys=()

package() {
	install -Dm644 "$srcdir/udiskie.service" -t "$pkgdir/usr/lib/systemd/user/"
}
