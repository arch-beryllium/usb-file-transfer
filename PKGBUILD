pkgname=usb-file-transfer
pkgver=0.1
pkgrel=2
pkgdesc="USB file transfer on ConfigFS systems"
arch=('any')
url="https://gitlab.com/postmarketOS/pmaports/-/blob/master/main/postmarketos-mkinitfs/init_functions.sh"
license=('custom')
source=('usb-file-transfer')
sha256sums=('afaac077f37c1ebbdc10d1d23eb80f44d8f6b09b09824679fe8d9a8fc5fa8d6b')

package() {
  cd "${srcdir}"
  install -d ${pkgdir}/usr/bin
  install -m 755 usb-file-transfer ${pkgdir}/usr/bin/usb-file-transfer
}
