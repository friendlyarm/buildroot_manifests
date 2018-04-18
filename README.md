# Rockchip Debian/Buildroot SDK

The Default:

To initialize Linux source tree

$ repo init -u https://github.com/rockchip-linux/manifests

To synchronize the source code

$ repo sync

--

The RK3399 chips:

There are two ways to get the code:

(1) Sync to the lastest TOT code:

$ repo init -u https://github.com/rockchip-linux/manifests -m rk3399_linux.xml

$ repo sync

(2) Sync to the lastest release code:

$ repo init -u https://github.com/rockchip-linux/manifests -m rk3399_linux_release.xml

$ repo sync
