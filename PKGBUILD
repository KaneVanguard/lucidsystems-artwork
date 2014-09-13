# Maintainer: Kane Vanguard
pkgname=lucidsystems-artwork
pkgver=1.0.0
pkgrel=1
pkgdesc="LucidSystems Artwork"
arch=('any')
url="https://github.com/KaneVanguard/lucidsystems-artwork"
license=('GPL')

package() {
    cd "$pkgdir"

    mkdir -p usr/share/backgrounds
    mkdir -p usr/share/lucidsystems
    mkdir -p usr/share/pixmaps

    cp -R "$srcdir/usr/share/backgrounds" usr/share
    cp -R "$srcdir/usr/share/lucidsystems" usr/share
    cp -R "$srcdir/usr/share/pixmaps" usr/share
}
