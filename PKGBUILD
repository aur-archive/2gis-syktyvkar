pkgname=2gis-syktyvkar
pkgver=30
pkgrel=1
pkgdesc="Map of Syktyvkar for 2GIS, September 2014"
arch=('i686' 'x86_64')
url="http://info.2gis.ru/syktyvkar/products/download#linux"
license=('custom')
depends=('2gis>=3.14.7.0')
source=("http://download.2gis.com/arhives/2GISData_Syktyvkar-30.orig.zip")
md5sums=('1cfdc1b8c4c2967ab7571d845655d7ee')

package() {
  install -D -m 644 "${srcdir}/2gis/3.0/Data_Syktyvkar.dgdat" "${pkgdir}/opt/2gis/2gis-syktyvkar.dgdat" || return 1
  
}
