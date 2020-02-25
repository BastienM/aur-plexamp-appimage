# Maintainer: Bastien Mennesson <bastien.mennesson@pm.me>
pkgname=plexamp-appimage
pkgver=1.1.0
pkgrel=1

pkgdesc="A small music player for your desktop, with a number of unique features"
arch=('x86_64')
url="https://www.plex.tv/plex-labs"
license=('MIT')
depends=('appimage-git')
noextract=("plexamp-${pkgver}-${arch}.AppImage")
options=("!strip")
source=(
    "https://plexamp.plex.tv/plexamp.plex.tv/plexamp-${pkgver}-${arch}.AppImage"
    "https://archive.archlinux.org/packages/p/pango/pango-1%3A1.44.1-1-x86_64.pkg.tar.xz"
)
sha256sums=(
    "144208341ee9d78a81fdfc3cce668453fc68e04ddf0d43262b9636d52d4ffb10"
    "ad55288cf833f77b441bb04c5b3351991ebc346a2b6aa9d7a8f07917d78f2d8c")

package() {
    install -Dm755 "plexamp-${pkgver}-${arch}.AppImage" "${pkgdir}/opt/appimages/plexamp.AppImage"
}

