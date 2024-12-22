# Maintainer: Trevin Jones <tr3vinj at gmail dot com>
pkgname=zmk-studio-bin
pkgver=0.2.4
pkgrel=1
pkgdesc="A tool for runtime keymap updates on ZMK-powered devices without reflashing firmware."
arch=('x86_64')
url="https://github.com/zmkfirmware/zmk-studio"
license=('Apache-2.0')
depends=('cairo' 'desktop-file-utils' 'gdk-pixbuf2' 'glib2' 'gtk3' 'hicolor-icon-theme' 'libsoup' 'pango' 'webkit2gtk')
options=('!strip' '!emptydirs')
install=${pkgname}.install
source_x86_64=("https://github.com/zmkfirmware/zmk-studio/releases/download/v$pkgver/zmk-studio_"$pkgver"_amd64.deb")
sha256sums_x86_64=('7e6c5864404504bdf409f57414b547cb3bc5004ba3f29d46b74813c1d93e51ea')
package() {
  tar -xz -f data.tar.gz -C "${pkgdir}"
}
