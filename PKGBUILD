# Maintainer: VHSgunzo <vhsgunzo.github.io>

pkgname='ubruntime'
pkgver='0.0.1'
pkgrel='1'
pkgbase="$pkgname"
pkgdesc='Ubuntu runtime from Steam for Lutris Wine'
url="https://github.com/VHSgunzo/ubruntime"
arch=('x86_64')
license=('MIT')
source=("ubruntime.tar.xz::https://raw.githubusercontent.com/VHSgunzo/ubruntime/main/ubruntime.tar.xz")
sha256sums=('SKIP')

package() {
    cp -ar --no-preserve=ownership "$srcdir/etc" "$pkgdir/etc"
    cp -ar --no-preserve=ownership "$srcdir/opt" "$pkgdir/opt"
}
