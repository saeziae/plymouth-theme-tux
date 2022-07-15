Original author <https://www.opencode.net/eren16>

A OSX-like boot splash of Tux penguin for plymouth

Fixed the problem of the display of vender logo

```sh
git clone https://github.com/saeziae/plymouth-theme-tux.git && cd plymouth-theme-tux
sudo cp -r linux-penguin /usr/share/plymouth/themes/
sudo plymouth-set-default-theme -R linux-penguin
```
