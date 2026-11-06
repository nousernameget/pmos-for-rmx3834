# Reference: <https://postmarketos.org/devicepkg>
maintainer="babob1994"
pkgname=device-realme-rmx3834
pkgdesc="realme Note50 "
pkgver=1
pkgrel=0
url="https://postmarketos.org"
license="MIT"
arch="aarch64"
options="!check !archcheck"
depends="
        linux-postmarketos-unisoc-ums9230
        mkbootimg
        postmarketos-base
"
makedepends="devicepkg-dev"
source="
        deviceinfo
        modules-initfs
"

build() {
        devicepkg_build $startdir $pkgname
}

package() {
        devicepkg_package $startdir $pkgname
}

