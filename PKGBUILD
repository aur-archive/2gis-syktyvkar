pkgname=2gis-syktyvkar
pkgver=9
pkgrel=1
pkgdesc="Map of Syktyvkar for 2GIS, December 2012"
arch=('i686' 'x86_64')
url="http://syktyvkar.2gis.ru/how-get/linux/"
license=('custom')
depends=('2gis>=3.12.0.2')
source=("http://download.2gis.ru/arhives/2GISData_Syktyvkar-9.orig.zip")
md5sums=('47080a481d681e31f953ca2d3fe66b4b')

build() {
  cd $startdir
# Installing to /opt/2gis
  install -D -m 644 ${startdir}/src/2gis/3.0/Data_Syktyvkar.dgdat "${startdir}/pkg/opt/2gis/syktyvkar.dgdat" || return 1
  
}
