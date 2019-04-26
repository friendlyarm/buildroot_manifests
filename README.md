# Rockchip Debian/Buildroot SDK

The Default:

To initialize Linux source tree

$ repo init --repo-url=https://github.com/rockchip-linux/repo -u https://github.com/rockchip-linux/manifests

To synchronize the source code

$ repo sync

--

The PX30 chips

Sync to the lastest release code:

$ repo init --repo-url=https://github.com/rockchip-linux/repo -u https://github.com/rockchip-linux/manifests -b master -m px30_linux_release.xml

$ repo sync

--

The RK3326 chips

Sync to the lastest release code:

$ repo init --repo-url=https://github.com/rockchip-linux/repo -u https://github.com/rockchip-linux/manifests -b master -m rk3326_linux_release.xml

$ repo sync

--

The RK3288 chips

There are two ways to get the code:

(1) Sync to the lastest TOT code:

$ repo init --repo-url=https://github.com/rockchip-linux/repo -u https://github.com/rockchip-linux/manifests -b master -m rk3288_linux.xml

$ repo sync

(2) Sync to the lastest release code:

$ repo init --repo-url=https://github.com/rockchip-linux/repo -u https://github.com/rockchip-linux/manifests -b master -m rk3288_linux_release.xml

$ repo sync

--

The RK3399 chips

There are two ways to get the code:

(1) Sync to the lastest TOT code:

$ repo init --repo-url=https://github.com/rockchip-linux/repo -u https://github.com/rockchip-linux/manifests -b master -m rk3399_linux.xml

$ repo sync

(2) Sync to the lastest release code:

$ repo init --repo-url=https://github.com/rockchip-linux/repo -u https://github.com/rockchip-linux/manifests -b master -m rk3399_linux_release.xml

$ repo sync

--

The RK3399pro chips

There are two ways to get the code:

(1) Sync to the lastest TOT code:

$ repo init --repo-url=https://github.com/rockchip-linux/repo -u https://github.com/rockchip-linux/manifests -b master -m rk3399pro_linux.xml

$ repo sync

(2) Sync to the lastest release code:

$ repo init --repo-url=https://github.com/rockchip-linux/repo -u https://github.com/rockchip-linux/manifests -b master -m rk3399pro_linux_release.xml

$ repo sync

--


The RK1808pro chips

$ repo init --repo-url=https://github.com/rockchip-linux/repo -u https://github.com/rockchip-linux/manifests -b master -m rk1808_linux_release.xml

$ repo sync

--
