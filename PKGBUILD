pkgname=2gis-odessa
pkgver=90
pkgrel=1
pkgdesc="Map of Odessa for 2GIS, August 2014"
arch=('i686' 'x86_64')
url="http://info.2gis.ua/odessa/how-get/linux/"
license=('custom')
depends=('2gis>=3.14.7.0')
source=("http://download.2gis.ru/arhives/2GISData_Odessa-90.orig.zip")
md5sums=('ae94712d85301b52b3db8ba141fa6ada')

package() {
  install -D -m 644 "${srcdir}/2gis/3.0/Data_Odessa.dgdat" "${pkgdir}/opt/2gis/2gis-odessa.dgdat" || return 1
  
}
