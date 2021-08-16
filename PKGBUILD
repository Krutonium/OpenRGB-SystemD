pkgname="OpenRGB-systemd-service"
pkgver="1.0.0"
pkgrel="1"
pkgdesc="A SystemD service for OpenRGB"
arch=("any")
depends=("openrgb")
license=("MIT")
source=("https://raw.githubusercontent.com/Krutonium/OpenRGB-SystemD/main/OpenRGB.service")
sha512sums=("SKIP")
package() {
    mkdir -p "${pkgdir}/etc/systemd/system/"
    cp "{$srcdir}/OpenRGB.service" "{$pkgdir}/etc/systemd/system/OpenRGB.service"
    chmod +x "{$pkgdir}/etc/systemd/system/OpenRGB.service"
} 
