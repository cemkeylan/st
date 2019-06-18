# Maintainer: Cem Keylan

pkgname=st-ckyln
_pkgname=st
pkgver=20190618
pkgdesc="Simple Terminal from suckless.org (Fork)"
url="https://git.ckyln.com/cemkeylan/st.git"
arch=('i686' 'x86_64')
license=('MIT')
depends=('libxft')
makedepends=('git')
source=('https://git.ckyln.com/cemkeylan/st.git')
md5sums=('SKIP')

provides=('st')
conflicts=('st')

build() {
	cd $srcdir/${_pkgname}
	make
}

package() {
	cd ${_pkgnmae}
	make PREFIX=/usr DESTDIR="${pkgdir}" install
	install -Dm644 LICENSE "${pkgdir}/usr/share/doc/${pkgname}/LICENSE"
	install -Dm644 "${pkgdir}/usr/share/doc/${pkgname}/README.md"
}
