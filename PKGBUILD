# Maintainer: Ma Jiehong <ma.jiehong at gmail>
pkgname=ttf-tw
pkgver=3.0
pkgrel=1
pkgdesc="Set of KAI and SONG font from the Ministry of Education of Taiwan. These fonts follow all the official recommendations and their shapes are correct."
arch=('i686' 'x86_64')
url="http://english.moe.gov.tw/ct.asp?xItem=9367&ctNode=424&mp=1"
license=('CC-BY-ND 3.0')
depends=('fontconfig' 'xorg-font-utils')
conflicts=()
install=ttf.install
source=("http://www.edu.tw/files/site_content/MANDR/edukai-3.ttf"
"http://www.edu.tw/files/site_content/MANDR/eduSong_Unicode.ttf")

build() {
  cd "$srcdir"
  install -Dm644 edukai-3.ttf "$pkgdir/usr/share/fonts/TTF/tw-kai.ttf"
  install -Dm644 eduSong_Unicode.ttf "$pkgdir/usr/share/fonts/TTF/tw-song.ttf"
}
md5sums=('54ec89be4e542507e9039f1e9d32b971'
         '4d089afa4b97f314daf4b761ce63a662')

