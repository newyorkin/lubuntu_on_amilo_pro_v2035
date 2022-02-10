https://help.ubuntu.com/community/OpenChrome

My history log^

   27  sudo apt-get install build-essential
   28  sudo sed -i '/cdrom/d' /etc/apt/sources.list
   29  sudo apt-get install build-essential
   30  sudo apt-get install autoconf automake1.9 libtool git xutils xutils-dev
   31  sudo apt-get install autoconf automake libtool git xutils xutils-dev
   32  sudo apt-get build-dep xserver-xorg-video-openchrome
   33  sudo apt-get install xserver-xorg-video-openchrome
   34  sudo apt-get build-dep xserver-xorg-video-openchrome
   35  sudo apt-get install pkg-config xserver-xorg-dev libxext-dev libxv-dev libxvmc-dev
   36  git clone git://anongit.freedesktop.org/openchrome/xf86-video-openchrome
   37  cd xf86-video-openchrome
   38  ./autogen.sh --prefix=/usr --enable-debug --enable-xv-debug
   39  make
   40  sudo make install
