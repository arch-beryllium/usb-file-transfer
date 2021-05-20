pkgname=usb-file-transfer
pkgver=0.1
pkgrel=1
pkgdesc="USB file transfer on ConfigFS systems"
arch=('any')
url="https://gitlab.com/postmarketOS/pmaports/-/blob/master/main/postmarketos-mkinitfs/init_functions.sh"
license=('custom')
source=('usb-file-transfer')
sha256sums=('e518521cad7b2bab43d57562cf65a335f11a2a895dfc3791fd320c424ace3a44')

package() {
  cd "${srcdir}"
  install -d ${pkgdir}/usr/bin
  install -m 755 usb-file-transfer ${pkgdir}/usr/bin/usb-file-transfer
}
