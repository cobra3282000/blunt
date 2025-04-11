# Maintainer: Your Name <your.email@example.com>

pkgname=blunt
pkgver=1
pkgrel=1
pkgdesc="Description of your 'blunt' program"
arch=('x86_64')
url="https://github.com/yourusername/blunt"
license=('GPL' or 'MIT' or whatever license you prefer)
depends=() # Add any runtime dependencies your program needs
makedepends=('git') # Add any build dependencies your program needs
source=("git+https://github.com/cobra3282000/blunt.git")
sha256sums=('SKIP')

build() {
  cd "$srcdir/$pkgname"
  # Add your build commands here
  # For example:
  # make
}

package() {
  cd "$srcdir/$pkgname"
  
  # Install the main executable to /usr/bin/
  install -Dm755 blunt "$pkgdir/usr/bin/blunt"
  
  # If you have a license file, install it too
  # install -Dm644 LICENSE "$pkgdir/usr/share/licenses/$pkgname/LICENSE"
  
  # If you have documentation, man pages, etc., install them as well
  # install -Dm644 README.md "$pkgdir/usr/share/doc/$pkgname/README.md"
}