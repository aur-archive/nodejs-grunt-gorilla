# Maintainer: Andy Weidenbaum <archbaum@gmail.com>

pkgname=nodejs-grunt-gorilla
_npmname=grunt-gorilla
pkgver=0.1.6
pkgrel=1
pkgdesc="Compile GorillaScript files to JavaScript"
arch=('any')
depends=('nodejs')
makedepends=('npm')
url="https://github.com/ckknight/grunt-gorilla"
license=('MIT')
provides=('nodejs-grunt-gorilla')

package() {
  local _npmdir="$pkgdir/usr/lib/node_modules/"
  mkdir -p $_npmdir
  cd $_npmdir
  npm install --user root -g --prefix "$pkgdir/usr" $_npmname@$pkgver
}
