# Maintainer: Bastien Mennesson <bastien.mennesson@pm.me>
pkgname=plexamp-appimage
pkgver=3.0.3
pkgrel=1

pkgdesc="A small music player for your desktop, with a number of unique features"
arch=('any')
url="https://www.plex.tv/plex-labs"
license=('MIT')
depends=('appimage-git')
noextract=("plexamp-${pkgver}-${arch}.AppImage")
options=("!strip")
source=("https://plexamp.plex.tv/plexamp.plex.tv/desktop/Plexamp-${pkgver}.AppImage")
sha256sums=("e5ddc589d18180a9f68312ea22a33e239a74d322895ac1c525a0b7cb260206e6")

package() {
    install -Dm755 "Plexamp-${pkgver}.AppImage" "${pkgdir}/opt/appimages/plexamp.AppImage"
}

