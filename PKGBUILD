url="https://github.com/TheVoidBlock/cpu-toggle"

pkgname="cpu-toggle"
pkgver="1.0.0_Alpha.1"
pkgrel="1"
pkgdesc="TUI tool for enabling/disabling CPU cores."
arch=("x86_64")
depends=("bash" "findutils" "coreutils" "ncurses" "tcl" "grep")
license=("GPL-3")
source=("cpu-toggle")
sha512sums=('9d40e7356a265ee24d61d9258d82bd9cbeaa5011becfd097831194c1d475b73a11e34e4f737c88f2d82726392acc5ad90565a4b767035c5ba33be33529e2fa6f' 'SKIP')

package() {
	mkdir -p ${pkgdir}/usr/bin
	cp ${srcdir}/cpu-toggle ${pkgdir}/usr/bin
	chmod +x ${pkgdir}/usr/bin/cpu-toggle
}
