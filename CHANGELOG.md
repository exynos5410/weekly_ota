
git://github.com/exynos5410/android_device_samsung_exynos5410-common

Changes
- exynos5410: enable variable touchkey brightness support
- exynos5410-common: overlay: Enable call recording feature by default
- exynos5410-common: overlay: Fix bluetooth connect issues
- exynos5410-common: Remove power profiles
- exynos5410-common: Switch to unified Power HAL

git://github.com/LineageOS/android_external_wpa_supplicant_8

Changes
- Clear PMK length and check for this when deriving PTK
- Add debug prints on PMK configuration in WPA supplicant
- WPA: Extra defense against PTK reinstalls in 4-way handshake
- Remove all PeerKey functionality
- Add MGMT_TX_STATUS_PROCESS command for testing purposes
- FT: Do not allow multiple Reassociation Response frames
- WNM: Ignore WNM-Sleep Mode Response without pending request
- TDLS: Reject TPK-TK reconfiguration
- Fix PTK rekeying to generate a new ANonce
- Prevent installation of an all-zero TK
- Extend protection of GTK/IGTK reinstallation of WNM-Sleep Mode cases
- Prevent reinstallation of an already in-use group key
- hostapd: Avoid key reinstallation in FT handshake
- Set EAPOL-Key Key Length field to 0 for group message 1/2 in RSN

git://github.com/LineageOS/android_frameworks_base

Changes
- improve compatibility when compiling with clang
- DO NOT MERGE "[PATCH] Zygote: Stop breaking the entire system"
- SystemUI: Profiles tile should require authentication
- Revert "Always hide protected apps from the recent tasks list"

git://github.com/exynos5410/android_kernel_samsung_exynos5410

Changes
- interactive: half timer slack
- cpufreq: interactive: Remove trace event from idle_start handler
- cpufreq: interactive: Reset floor_validate_time if busy at max for 100ms
- cpufreq: interactive: Allow 1 ms error in above_hispeed_delay comparisons
- Interactive: Tune for power-saving
- exynos5410: cypress: add variable touchkey brightness support
- exynos5410: arch: arm: ja: switch to interactive cpu governor
- input: touchscreen: Disable all touch boosters by default
- exynos5410: arch: arm: ja3gxx: switch to interactive cpu governor
- cpufreq: Introduce new relation for freq selection
- cpufreq: transfer ondemand-sec changes to ondemand
- cpufreq: exynos-ikcs: include sysfs_helpers.h
- cpufreq: ondemand-sec: Remove sysfs group on governor stop
- input: touchscreen: Adapt touch booster controls to new mechanism
- cpufreq: ondemand: Change the calculation of target frequency
- cpufreq: Move around min/max defines and misc
- cpufreq: Update IKCS to Exynos 5420 state
- cpufreq: Add a standalone hotplug driver
- cpufreq: Remove Ondemand-SEC hotplug logic
- gpu: pvr: Make GPU QoS requests configurable
- input: cypress: Make touchkey booster frequencies configurable
- devfreq: mif: PMS PLL experimental changes
- cpufreq: ondemand-sec: Fix governor being stuck on A7 cores
- cpufreq: Enforce policies in relation to CA7 frequency hole
- cpufreq: IKCS: Allow configurable switching frequencies
- gpu: pvr: Reduce QoS MIF freqs
- i2c: Disable cpufreq notifier in I2C drivers
- gpu: pvr: Disable CPU QoS requests
- mach-exynos: Lower regulator buck min voltages to their minima
- cpufreq: ondemand to ondemand-sec (duplicate)

git://github.com/LineageOS/www

Changes
- Fix typo in title
- Summer Survey Results

git://github.com/LineageOS/lineage_wiki

Changes
- addison: Update Motorola Moto Z Play Specs
- athene: Update Motorola Moto G4 Specs
- harpia: Update Motorola Moto G4 Play Specs
- pme: Update HTC 10 Specs
- Improve phrasing and content of some wiki pages
- wiki: A6020 - Link custom TWRP
- Update V20 peripherals list, add common ones

git://github.com/LineageOS/android_packages_apps_Eleven

Changes
- Eleven: Fix potential NPE when media server crashes
- Eleven: Don't use a sticky service
