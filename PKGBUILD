# Maintainer: Bruno Goncalves <bigbruno@gmail.com>

pkgname=sysctl-network
pkgver=1.0.0
pkgrel=0
arch=('any')
license=('GPL')
url="https://github.com/biglinux/sysctl-network"
pkgdesc="Sysctl file to improve network configuration"
source=("git+https://github.com/biglinux/sysctl-network.git")
md5sums=(SKIP)

package() {
    cp -r "${srcdir}/sysctl-network/sysctl-network/etc/" "${pkgdir}/"
} 
