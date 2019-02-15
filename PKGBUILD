# Maintainer: Alfredo Ramos <alfredo dot ramos at yandex dot com>
# Contributor: Thomas Nordenmark <t.nordenmark@gmail.com>

pkgname=composite-run
pkgver=3
pkgrel=1
arch=('any')
license=('GPL3')

depends=('xorg-xdriinfo')

source=("composite-run"
	"composite"
)

sha256sums=(
	'SKIP'
	'SKIP'
)


package() {
	install -Dm755 "${srcdir}"/composite "${pkgdir}"/etc/default/composite
	install -d "${pkgdir}"/usr/bin/
	install -m755 "${srcdir}"/composite-run "${pkgdir}"/usr/bin/
}
