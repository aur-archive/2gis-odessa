# Contributor: max1m <mr[dot]mxm86[at]gmail[dot]com>
     
pkgname=2gis-odessa
pkgver=66
pkgrel=1
pkgdesc="Map of Odessa for 2GIS, August 2012"
arch=('i686' 'x86_64')
url="http://odessa.2gis.ru/how-get/linux/"
license=('custom')
depends=('2gis>=3.7.0.0')
source=("http://download.2gis.ru/arhives/2GISData_Odessa-66.orig.zip")
md5sums=('fb791887e449b97b6048db3b6c6a8517')
     
build() {
     
   cd $startdir
     
# Installing to /opt/2gis
  install -D -m 644 ${startdir}/src/2gis/3.0/Data_Odessa.dgdat "${startdir}/pkg/opt/2gis/odessa.dgdat" || return 1
  install -D -m 644 ${startdir}/src/2gis/3.0/Plugins/DGisLan/Odessa.dglf "${startdir}/pkg/opt/2gis/Plugins/DGisLan/Odessa.dglf" || return 1
     
}

