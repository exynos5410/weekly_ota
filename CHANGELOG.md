
git://github.com/LineageOS/android_frameworks_base

Changes
- improve compatibility when compiling with clang
- DO NOT MERGE "[PATCH] Zygote: Stop breaking the entire system"
- Core: Battery warning levels are inclusive, not exclusive

git://github.com/exynos5410/android_kernel_samsung_exynos5410

Changes
- ipx: call ipxitf_put() in ioctl error path
- Bluetooth: Properly check L2CAP config option output buffer length
- net: wireless: bcmdhd: remove SDIO debug IOVARs causing out of bounds
- Prevent potential double frees in sg driver
- net: wireless: bcmdhd: adding boundary check in wl_notify_rx_mgmt_frame
- net: wireless: bcmdhd: adding boudary check in wl_escan_handler
- net: wireless: bcmdhd: fix buffer overrun in wlfc reordering
- net: wireless: bcmdhd: Heap overflow in wl_run_escan
- net: wireless: bcmdhd: fix buffer overrun in wl_cfg80211_add_iw_ie
- fs/exec: fix use after free in execve

git://github.com/LineageOS/lineage_wiki

Changes
- wiki: recommend Linux LTS versions for new users
- g2m: Add custom TWRP link
- templates: Link directly to TWRP device download list
- templates: allow devices to specify a custom twrp codename
- cherry/che10: Point TWRP download page to xda
- addison: Add custom TWRP link

git://github.com/LineageOS/android_packages_apps_Gallery2

Changes
- Gallery: Kill media effect dialog on movies
- Gallery2: Fix crash when muting a video
- Fix gallery crash when trimming video

git://github.com/exynos5410/proprietary_vendor_samsung

Changes
- exynos5410-common: Make libsecnativefeature common
- Revert "ja3gxx: Switch to prebuilt RIL blobs"
