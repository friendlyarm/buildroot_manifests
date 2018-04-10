# Rockchip Debian SDK

The Default:

To initialize Linux source tree

$ repo init -u https://github.com/rockchip-linux/manifests

To synchronize the source code

$ repo sync

--

The RK3036G chips:

$ repo init -u https://github.com/rockchip-linux/manifests -m rk3036.xml

$ repo sync


The RK3399 chips:

$ repo init -u https://github.com/rockchip-linux/manifests -m rk3399_linux.xml

$ repo sync
