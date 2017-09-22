
git://github.com/LineageOS/android

Changes
- Switch deqp, pdfium and speex to our forks
- cm: Remove libphonenumbergoogle
- manifest: switch to our forks of several repos

git://github.com/LineageOS/android_build

Changes
- Fix warning with AAPT2 and LOCAL_STATIC_ANDROID_LIBRARIES
- Updating Security String to 2017-09-05 Bug:63846344

git://github.com/LineageOS/android_external_libavc

Changes
- Decoder: Fixed allocation of pv_map_ref_idx_to_poc_buf.
- Decoder: Fixed overflow in refernce list creation.
- Initialize DPB structures to valid values.
- Added error check for output buffer size.

git://github.com/LineageOS/android_external_libhevc

Changes
- Limit boundary PU sizes in case of errors
- Fix array size for hrd parameters
- Check number of output buffers and sizes
- Return error for invalid crop parameters

git://github.com/LineageOS/android_external_sonivox

Changes
- Fix compiler warnings in sonivox and enable -Werror.
- Fix interpolator

git://github.com/LineageOS/android_frameworks_av

Changes
- audioflinger: Use offloaded effects in case of PCM offload
- MPEG4Source: fix fragmented read.
- stagefright: fix crash due to bad timestamp index
- stagefright: check aac_frame_length to prevent infinite loop
- MediaPlayerService: fix access of mPlayer in client
- audio effects: filter reserved effect commands
- MPEG4Extractor: ensure returned status is checked.
- DO NOT MERGE Check frame handle validity before freeing buffer.
- Change MPEG2 reinit Error Handling
- Track: Check buffer size of static tracks
- MPEG4Extractor: check size for yrrc box
- AudioFlinger: Fix memory allocation for client-less tracks
- Notify Errors Appropriately from SoftMPEG2
- EffectBundle: Check value size for get preset name
- Fix TOCTOU problem in libstagefright_soft_aacenc

git://github.com/LineageOS/android_frameworks_base

Changes
- improve compatibility when compiling with clang
- DO NOT MERGE "[PATCH] Zygote: Stop breaking the entire system"
- Automatic translation import
- SystemServer: Don't start widget service when it is alarm boot
- ActivityManager: Remove POWER_OFF_ALARM intent leftover
- Always hide protected apps from the recent tasks list
- Recents: Add accessibility descriptions for lock ImageViews
- SystemUI: Add separate pref screen for the status bar tuner
- SystemUI: Revert some Tuner changes
- Back-port fixes for b/62196835

git://github.com/LineageOS/cve_tracker

Changes
- logs: cast pages number to int
- api: v1: implement GET kernels/repo_name/cve_name
- api: v1: implement GET cves/cve_name
- api: v1: implement GET kernels/repo_name
- api: v1: implement GET CVEs
- api: v1: implement GET kernels

git://github.com/LineageOS/hudson

Changes
- Add Sony Xperia Z3+ (ivy)
- hudson: reenable v20s (h910 h918 vs995 us996 ls997)
- hudson: Add Sony fusion3 devices

git://github.com/LineageOS/lineageos_updater

Changes
- updater: add Galaxy J7 (j7ltespr)
- updater: Add the Sony Xperia Z3+ (ivy)
- Add v400

git://github.com/LineageOS/lineage_wiki

Changes
- faq: fix updater download location
- devices: Add Sony Xperia Z3+ (ivy)
- wiki: Add Sony fusion3 devices

git://github.com/LineageOS/android_packages_apps_CMParts

Changes
- Automatic translation import
- CMParts: Update intent to start the status bar preferences

git://github.com/LineageOS/android_packages_apps_Eleven

Changes
- Automatic translation import
- Eleven: Create one cursor per background task

git://github.com/LineageOS/android_packages_apps_Messaging

Changes
- Automatic translation import
- 37742976 - Catch bad gifs

git://github.com/LineageOS/android_packages_apps_Nfc

Changes
- Automatic translation import
- Add READ_EXTERNAL_STORAGE for file based Uri while beaming.

git://github.com/LineageOS/android_packages_apps_Settings

Changes
- Automatic translation import
- AppOpsState: Hide undeclared Privacy Guard OPs
- Back-port ag/2491664

git://github.com/LineageOS/android_vendor_cm

Changes
- extract_utils: implement LOCAL_MODULE_RELATIVE_PATH
- cm/aosp/cafremote: Make variables local
- envsetup: Fix cmremote for AOSP projects
- cm: Add CMSettings package to power_off_alarm_apps

git://github.com/LineageOS/cm_platform_sdk

Changes
- Revert "cmsdk: Don't change ring volume or mode if DND is enabled"
- Automatic translation import
- cmsdk: Run in core apps only for poweroff alarm boot
- Make CMParts a protected component manager
- cmsdk: Don't change ring volume or mode if DND is enabled
