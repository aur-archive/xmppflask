pkgname=xmppflask
pkgver=1
pkgrel=1
pkgdesc="XmppFlask is a python2 XMPP framework inspired by Flask."
url='http://xmppflask.org/'
arch=('i686' 'x86_64')
license=('GPL2')
depends=('python2' 'pypy' 'python2-jinja' 'python2-flask' 'xmpppy')
source=("https://bitbucket.org/k_bx/xmppflask/get/fb61f32addd5.tar.gz")
md5sums=('673f7e433d85a037c8ad118a486de3d2')

package() {
  tar -xvf fb61f32addd5.tar.gz
  cd "$srcdir/k_bx-xmppflask-fb61f32addd5"
  python2 setup.py install --root="$pkgdir/" --optimize=1
}