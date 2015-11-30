This is an OpenWrt package feed containing community maintained routing packages.

To use these packages, add the following line to the feeds.conf in the OpenWrt buildroot:

src-git batman_adv git://github.com/wirelesspt/batman-adv-2015.1.git

Update the feed:

./scripts/feeds update batman_adv

Activate the package:

./scripts/feeds install -a -p batman_adv

The routing packages should now appear in menuconfig.
