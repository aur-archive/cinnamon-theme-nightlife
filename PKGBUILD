# Maintainer: Daniel Leining <daniel@the-beach.co>

pkgname=cinnamon-theme-nightlife
_file=68V2-TJOB-0Y95
pkgver=3.1
pkgrel=1
pkgdesc="Cinnamon theme in seven colors."
arch=('any')
url="http://cinnamon-spices.linuxmint.com/themes/view/31"
license=('unknown')
depends=('cinnamon')
source=($pkgname-$pkgver.zip::http://cinnamon-spices.linuxmint.com/uploads/themes/$_file.zip)
sha1sums=('1c8fed10a75ba1233b973b98123bf40e1c522f53')

package() {
  cd "$srcdir"
  find Nightlife* -type f -exec install -Dm644 {} "$pkgdir/usr/share/themes/{}" \;
}

# vim:set ts=2 sw=2 et:
