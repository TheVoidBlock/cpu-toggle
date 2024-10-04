url="https://github.com/TheVoidBlock/cpu-toggle"

pkgname="cpu-toggle"
pkgver="1.0.0_Alpha.1"
pkgrel="1"
pkgdesc="TUI tool for enabling/disabling CPU cores."
arch=("x86_64")
depends=("bash" "findutils" "coreutils" "ncurses" "tcl" "grep")
license=("GPL-3")
source=("cpu-toggle")
sha512sums=('d6f99c06e2a84ccdec171c0c8e8e3ce4196554afae8cf9f59d2f61e211c0d9e0' 'SKIP')

package() {
	mkdir -p ${pkgdir}/usr/bin
	cp ${srcdir}/cpu-toggle ${pkgdir}/usr/bin
	chmod +x ${pkgdir}/usr/bin/cpu-toggle
}
