pkgname=wakatime
pkgver=999
pkgrel=1
arch=('any')
url="htps://github.com/mikrfe/wakatime"
license=('BSD-3-Clause')
groups=()
depends=('python')
makedepends=()
provides=()
conflicts=()
replaces=()
options=(!emptydirs)
install=
srcdir=.
package() {
    cd ..
    python ./setup.py install --root="$pkgdir/" --optimize=1
}

# vim:set ts=2 sw=2 et: