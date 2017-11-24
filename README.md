# elementarywatson
ChromeOS to ElementaryOS

```
git clone https://github.com/hugegreenbug/libevdevc.git
cd /tmp/lokiforpixel/libevdevc
make
sudo make install
cd /tmp/lokiforpixel
git clone https://github.com/hugegreenbug/libgestures.git
cd /tmp/lokiforpixel/libgestures
make
sudo make install
cd /tmp/lokiforpixel
git clone https://github.com/hugegreenbug/xf86-input-cmt.git
cd /tmp/lokiforpixel/xf86-input-cmt
./configure --prefix=/usr
make
sudo make install
sudo cp xorg-conf/20-mouse.conf /usr/share/X11/xorg.conf.d/20-mouse.conf
sudo cp xorg-conf/40-touchpad-cmt.conf /usr/share/X11/xorg.conf.d/40-touchpad.conf
cd /tmp/lokiforpixel
sudo cp preferences/touchpad/50-touchpad-cmt-peppy.conf /usr/share/X11/xorg.conf.d/50-touchpad.conf
sudo mv /usr/share/X11/xorg.conf.d/50-synaptics.conf /usr/share/X11/xorg.conf.d/50-synaptics.conf-old
```

