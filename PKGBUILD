# Maintainer: VHSgunzo <vhsgunzo.github.io>

pkgname='steam-runtime-libs'
pkgver='0.0.7'
pkgrel='1'
pkgdesc='Libraries from Steam for Lux Wine'
url="https://github.com/VHSgunzo/steam-runtime-libs"
arch=('x86_64')
license=('MIT')
source=("steam-runtime-libs.tar.zst")
sha256sums=('SKIP')

package() {
    cp -ar --no-preserve=ownership "$srcdir/etc" "$pkgdir/etc"
    cp -ar --no-preserve=ownership "$srcdir/opt" "$pkgdir/opt"
}
