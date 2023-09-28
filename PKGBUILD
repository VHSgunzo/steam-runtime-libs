# Maintainer: VHSgunzo <vhsgunzo.github.io>

pkgname='steam-runtime-libs'
pkgver='0.0.3'
pkgrel='1'
pkgbase="$pkgname"
pkgdesc='Libraries from Steam for Lux Wine'
url="https://github.com/VHSgunzo/steam-runtime-libs"
arch=('x86_64')
license=('MIT')
source=("https://raw.githubusercontent.com/VHSgunzo/steam-runtime-libs/main/steam-runtime-libs.tar.xz")
sha256sums=('SKIP')

package() {
    cp -ar --no-preserve=ownership "$srcdir/$pkgname/etc" "$pkgdir/etc"
    cp -ar --no-preserve=ownership "$srcdir/$pkgname/opt" "$pkgdir/opt"
}
