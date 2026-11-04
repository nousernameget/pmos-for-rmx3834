# Reference: <https://postmarketos.org/devicepkg>
maintainer=""
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

sha512sums="
1a83cd0eb59b7a510ecb683a09089a6e1ec77a833553abc9e6b8aa5341b9b14d12ac726224812a6eecedc8e640b10a6455d6b7d5ff976d010a6c9dd78fa0028f  deviceinfo
3bb2c10c1a15b98326f55ff2107bca35892819cba0e4df2a4600f91a612a0dcbb79b50118538c197778438a0c5923fed828eca4ba5b61eeaff9da270470250cf  modules-initfs
"
