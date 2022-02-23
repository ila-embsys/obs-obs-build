pkgname=build
pkgver=20211125+103
pkgrel=0
pkgdesc="Build packages in sandbox"
arch=('i686' 'x86_64')
url="https://www.github.com/openSUSE/obs-build"
license=('GPL-2.0+' 'GPL-2.0')
groups=('base-devel')
depends=('perl')
source=(obs-build-${pkgver}.tar.gz)
md5sums=('SKIP')

package() {
  msg "Installing build ..."
  cd "${srcdir}"/obs-build-${pkgver}
  make DESTDIR=${pkgdir} install
}
