pkgname=2gis-syktyvkar
pkgver=19
pkgrel=1
pkgdesc="Map of Syktyvkar for 2GIS, October 2013"
arch=('i686' 'x86_64')
url="http://syktyvkar.2gis.ru/how-get/linux/"
license=('custom')
depends=('2gis>=3.13.9.0')
source=("http://download.2gis.ru/arhives/2GISData_Syktyvkar-19.orig.zip")
md5sums=('8126faff0ac80e057da8ac7c40520428')

package() {
  install -D -m 644 "${srcdir}/2gis/3.0/Data_Syktyvkar.dgdat" "${pkgdir}/opt/2gis/syktyvkar.dgdat" || return 1
  install -D -m 644 "${srcdir}/2gis/3.0/Plugins/DGisLan/Syktyvkar.dglf" "${pkgdir}/opt/2gis/Plugins/DGisLan/syktyvkar.dglf" || return 1
}
