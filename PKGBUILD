# Maintainer: Egor Sanin <egordotsaninatgmaildotcom>

pkgname=hrec
pkgver=0.2
pkgrel=1
pkgdesc="Small console program for quick recordings using ecasound and jack"
arch=('any')
url="https://sourceforge.net/projects/hrec/"
license=('GPL3')
depends=('python2' 'jack' 'ecasound')
options=(!emptydirs)
source=("https://downloads.sourceforge.net/project/hrec/$pkgname-$pkgver.tar.gz")
md5sums=('33c0514628aff7cc5cb31f91c668e555')

package() {
  cd "$srcdir/$pkgname-$pkgver"
  python2 setup.py install --root="$pkgdir/" --optimize=1
}
