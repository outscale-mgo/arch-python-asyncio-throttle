# Maintainer: Matthias gatto <matthias.gatto@outscale.com>
# Reference: PKGBUILD(5)

pkgname=python-asyncio-throttle
pkgver=1.0.1
pkgrel=1
pkgdesc='Simple, easy-to-use throttler for asyncio'

arch=('any')
url='https://github.com/hallazzang/asyncio-throttle/'
license=(BSD)

makedepends=('python-pip')
depends=()

package() {
	PIP_CONFIG_FILE=/dev/null pip install --isolated --root="$pkgdir" --ignore-installed --no-deps asyncio-throttle==1.0.1
}
