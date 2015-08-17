# Maintainer: Kyle Cesare <kcesare@gmail.com>
pkgname=python2-catkin-tools
realname=catkin_tools
pkgver=0.2.2
pkgrel=1
pkgdesc="Command line tools for working with catkin"
arch=(i686 x86_64)
url="https://github.com/catkin/catkin_tools"
license=('Apache')
makedepends=('python2-setuptools')
depends=('python2' 'python2-catkin_pkg')
options=(!emptydirs)
source=("https://pypi.python.org/packages/source/c/$realname/$realname-$pkgver.tar.gz")
md5sums=('b9a43a62d8f94f66e6c342245a01d9de')

package() {
  cd "$srcdir/catkin_tools-$pkgver"
  python2 setup.py install --root="$pkgdir/" --optimize=1
}

# vim:set ts=2 sw=2 et:
