**Dependencies:** [mullvad](https://aur.archlinux.org/packages/mullvad-vpn-bin) runit

## How to use
**Artix**
```
sudo ./artix.install
```

**Linux**

Depending on the Runit implementation. In this example, I'm using Void Linux.
```
sudo ./linux.install
sv dir: /etc/sv
service dir: /var/service
```

**Manual**
```
mkdir /etc/runit/sv/mullvad
cp ./run /etc/runit/sv/mullvad
ln -s /etc/runit/sv/mullvad /run/runit/service/mullvad
```
