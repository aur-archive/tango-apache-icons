pkgname=tango-apache-icons
pkgver=1
pkgrel=3
arch=('any')
pkgdesc="Tango icons for Apache autoindex"
url="https://bitbucket.org/wooptoo/misc/downloads"
license="GPL"
depends=('apache' 'tango-icon-theme')
install=$pkgname.install
source=($url/$pkgname.zip)
md5sums=('3a3cdf858fc6f24c4d5b87e0abee10d1')

build() {
	cd $srcdir/$pkgname/
	install -Dm 644 tango-apache-icons.conf $pkgdir/etc/httpd/conf/tango-apache-icons.conf
	install -Dm 644 style.css $pkgdir/srv/http/.style.css
}
