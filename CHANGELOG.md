
git://github.com/LineageOS/android

Changes
- cm: Remove updater
- cm: Remove external/koush/ion
- cm: Remove external/lzo
- cm: Remove libtruezip
- cm: Remove tribble-tracker

git://github.com/LineageOS/android_frameworks_base

Changes
- improve compatibility when compiling with clang
- DO NOT MERGE "[PATCH] Zygote: Stop breaking the entire system"

git://github.com/exynos5410/android_kernel_samsung_exynos5410

Changes
- exynos5410: arch: arm: ja3gxx: enable android alarm dev
- exynos5410: arch: arm: jalteskt: enable android alarm dev
- exynos5410: arch: arm: update defconfigs
- rtc: Add S2MPS11 RTC driver and alarm boot functions
- Revert "HACK: android-alarm: wakelock workaround"
- android-alarm: Remove unused android alarm in-kernel interfaces
- android-alarm: Rework alarm-dev.c to use upstreamed alarmtimers
- android-alarm: Convert ALARM_ELAPSED_REALTIME to use CLOCK_BOOTTIME
- staging: android-alarm: Support old drivers via preprocessor aliasing
- staging: android-alarm: Fixup minor pr_alarm warnings
- staging: android-alarm: Fix bad index when canceling alarms[]
- staging: android-alarm: Update hrtimer if alarm at the head of the queue is reprogrammed
- staging: android-alarm: Disable Android alarm driver by default
- staging: android-alarm: Reenable android alarm driver
- staging: android-alarm: HACK: wakelock workaround
- staging: android-alarm: Fix namespace collision with upstreamed alarmtimers
- staging: android-alarm: Fix include compile issues
- staging: android-alarm: Add needed module.h includes
- staging: android-alarm: Don't use save_time_delta.
- staging: android-alarm: Add android alarm driver & in-kernel alarm interface

git://github.com/LineageOS/hudson

Changes
- Ship fugu weeklies
- hudson: move devices.json instructions out of updater
- hudson: include json blobs for updater

git://github.com/LineageOS/lineage_wiki

Changes
- wiki: Make "Contributing" a little more generic
- wiki: Change fugu vendor
- wiki: devices: Add fugu
- wiki: Search: Exclude build and installation pages from search
- wiki: Add ccache to build packages
- wiki: Link headers properly

git://github.com/LineageOS/android_packages_apps_Snap

Changes
- Snap: add QReader to module switch
- QuickReader: initial commit
