pkgname=2gis-syktyvkar
pkgver=10
pkgrel=1
pkgdesc="Map of Syktyvkar for 2GIS, January 2013"
arch=('i686' 'x86_64')
url="http://syktyvkar.2gis.ru/how-get/linux/"
license=('custom')
depends=('2gis>=3.12.0.2')
source=("http://download.2gis.ru/arhives/2GISData_Syktyvkar-10.orig.zip")
md5sums=('9aad3e96cfedb1959a51c58ce22678f9')

build() {
  cd $startdir
# Installing to /opt/2gis
  install -D -m 644 ${startdir}/src/2gis/3.0/Data_Syktyvkar.dgdat "${startdir}/pkg/opt/2gis/syktyvkar.dgdat" || return 1
  
}
