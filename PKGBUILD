# Maintainer: DaniD3v <nichtdu.login@gmail.com>

pkgname="jelly-drift-bin"
pkgdesc="car go vroom zoom skrrrt"
url="https://danidev.itch.io/jelly-drift"

pkgver="1.0.0"
pkgrel="1"

license=("unknown")

source=("jelly-drift.desktop" "JellyDrift.tar.xz")
makedepends=("tar")
arch=("x86_64")

sha256sums=('56279e3d77e2126a5886856923005d965c20b57d792142606badb71744423ab2' 'df92c9317470e73f934628c61643ba53f05a3bd7441e55a9f61f117f502d08dd')

package() {
  mkdir -p "${pkgdir}/usr/share"
  mv "${srcdir}/JellyDrift" "${pkgdir}/usr/share"

  mkdir "${pkgdir}/usr/share/applications"
  mv "${srcdir}/jelly-drift.desktop" "${pkgdir}/usr/share/applications"
}
