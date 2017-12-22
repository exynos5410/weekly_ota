
git://github.com/exynos5410/android_device_samsung_ja3gxx

Changes
- ja3gxx: bt: Remove BTIF_HF_WBS_PREFERRED TRUE
- ja3gxx: ril: Rebase on SM-P601

git://github.com/LineageOS/android_frameworks_base

Changes
- improve compatibility when compiling with clang
- DO NOT MERGE "[PATCH] Zygote: Stop breaking the entire system"
- SystemUI: fix enabling burnIn protection
- SystemUI: KeyGuardMonitor: Prevent ConcurrentModificationException
- SystemUI: Recents: Improve code for long app titles being overlapped
- We don't want to feel deprecated...
- Automatic translation import

git://github.com/LineageOS/android_hardware_cyanogen

Changes
- cmhw: Remove duplicate class
- cmhw: Update picture adjustment class with proper comments

git://github.com/exynos5410/android_kernel_samsung_exynos5410

Changes
- ext4: fix reservation overflow in ext4_da_write_begin
- ext4: add support for FIDTRIM, a best-effort ioctl for deep discard trim [Geremy Condra]
- ANDROID: binder: fix OOB write in __binder_update_page_range
- binder: always allocate/map first BINDER_MIN_ALLOC pages
- android: binder: Move buffer out of area shared with user space
- android: binder: Refactor prev and next buffer into a helper function
- android: binder: use GPF_HIGHUSER flag since binder is designed for userspace
- BACKPORT: staging: android: fix missing a blank line after declarations
- UPSTREAM: Staging: Android: removed an unnecessary else statement
- UPSTREAM: include/linux/mm.h: add PAGE_ALIGNED() helper
- v4l2: Refactor, fix security bug in compat ioctl32
- UPSTREAM: ALSA: timer: Call notifier in the same spinlock
- UPSTREAM: ALSA: timer: Fix race between stop and interrupt
- UPSTREAM: ALSA: timer: Fix link corruption due to double start or stop
- UPSTREAM: ALSA: timer: Code cleanup
- BACKPORT: ALSA: timer: Fix race at concurrent reads
- BACKPORT: ALSA: timer: Handle disconnection more safely
- UPSTREAM: ALSA: timer: Fix wrong instance passed to slave callbacks
- ANDROID: scsi: Add segment checking in sg_read
- ANDROID: usb: gadget: f_mtp: Return error if count is negative
- arch: arm: ja3gxx: Enable TTL target support
- Bluetooth: bnep: bnep_add_connection() should verify that it's dealing with l2cap socket
- Bluetooth: hidp: verify l2cap sockets
- cfg80211: Check if PMKID attribute is of expected size
- ANDROID: input: keychord: fix race condition bug
-  UPSTREAM: tracing: Fix trace_printk() to print when not using bprintk()
- ALSA: pcm: prevent UAF in snd_pcm_info
- ASoC: arizona: Fix noise generator gain TLV
- net: socket: fix recvmmsg not returning error from sock_error
- ALSA: seq: Fix use-after-free at creating a port
- crypto: memneq - fix for archs without efficient unaligned access
- crypto: more robust crypto_memneq
- crypto: crypto_memneq - add equality testing of memory regions w/o timing leaks
- mac80211: use constant time comparison with keys
- mac80211: accept key reinstall without changing anything
- nl80211: check for the required netlink attributes presence
- ASoC: arizona: Fix bclk for sample rates that are multiple of 4kHz

git://github.com/LineageOS/cm_crowdin

Changes
- Drop LiveLockScreen from cm-14.1
- crowdin: Add InCallUI

git://github.com/LineageOS/hudson

Changes
- Ship R7sf weeklies
- Disable hero builds

git://github.com/LineageOS/tribble-tracker

Changes
- stats: include FLASK_APP in environment for exec commands
- Update readme with data explanation & limitations

git://github.com/LineageOS/lineageos_updater

Changes
- updater: Add R7s and update R5/R7plus info
- Open external links in new browser window/tab
- updater: fix full urls, remove double slash
- Regenerate device dependency mappings

git://github.com/LineageOS/lineage_wiki

Changes
- wiki: Update r5/r7plus device info
- wiki: add OPPO R7s/R7sf
- wiki: Update OnePlus 3 maintainers
- wiki: Mark addison as discontinued

git://github.com/LineageOS/android_packages_apps_AudioFX

Changes
- AudioFX: fix NPE at onPrepareOptionsMenu
- Automatic translation import

git://github.com/LineageOS/android_packages_apps_Dialer

Changes
- Dialer: Fix translation issues
- Automatic translation import

git://github.com/LineageOS/android_packages_apps_SetupWizard

Changes
- Disable SetupWraith, if GMS not present
- Automatic translation import

git://github.com/LineageOS/android_vendor_cm

Changes
- repopick: use https by default for repopicking
- repopick: support auth'ing to gerrit and picking drafts
