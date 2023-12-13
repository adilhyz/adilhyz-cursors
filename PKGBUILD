pkgname=adilhyz-cursors
pkgver=1.0
pkgrel=2
pkgdesc="Cursors For Needs"
arch=('any')
url="https://github.com/adilhyz-cursor"
license=('GPL3')

prepare() {

	cp -af ../cursor/. ${srcdir}

}

package() {

	local cursor_dir=${pkgdir}/usr/share/icons
	mkdir -p "$cursor_dir"
	cp -r ${srcdir}/* "$cursor_dir"

}
