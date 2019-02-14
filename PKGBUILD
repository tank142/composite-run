# Maintainer: Alfredo Ramos <alfredo dot ramos at yandex dot com>
# Contributor: Thomas Nordenmark <t.nordenmark@gmail.com>

pkgname=composite-run
pkgver=2
pkgrel=1
arch=('i686' 'x86_64')
url='https://github.com/lxqt/compton-conf'
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
