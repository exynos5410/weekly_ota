
git://github.com/LineageOS/android_external_aac

Changes
- Fix out of bound memory access in lppTransposer
- DO NOT MERGE Prevent out of bound memory access in GetInvInt

git://github.com/LineageOS/android_external_libavc

Changes
- Decoder: Handle dec_hdl memory allocation failure gracefully
- Decoder: Fixed incorrect use of mmco parameters.
- Decoder: Detect change of mbaff flag in SPS
- Decoder: Increased allocation and added checks in sei parsing.

git://github.com/LineageOS/android_external_libhevc

Changes
- Add PUSH-POP of D registers in Arm Neon 32 bit functions
- Fixed few issues in SAO arm assemblies
- Decoder: Handle ps_codec_obj memory allocation failure gracefully
- Fix prev slice incomplete check
- Set error skip ctbs as multiple 8x8 pus
- Fix first frame error return
- Return error for negative crop parameters
- Consume bytes for sps with unsupported resolution
- Fix slice address zero for not first slice in pic
- Fix incomplete frame error

git://github.com/LineageOS/android_frameworks_av

Changes
- Fix the UAF bug caused by a dead stack variable
- Fix edge case when applying id3 unsynchronization
- Add EFFECT_CMD_SET_PARAM parameter checking to Preset Reverb
- Validate decryption key length to decrypt function.
- stagefright: MP4Extractor: allow 10% overhead on default sample size
- Access AVCDEC context after create fail check
- SoftAVCDec: Handle zero length input without EOS
- Access HEVC context after create fail check

git://github.com/LineageOS/android_frameworks_base

Changes
- improve compatibility when compiling with clang
- DO NOT MERGE "[PATCH] Zygote: Stop breaking the entire system"
- Keyguard: Don't apply input restriction if disabled by profile
- PhoneWindowManager: Make sure KeyDisabler is always called on boot
- DO NOT MERGE Backporting potential usb tapjacking precaution.
- mtp: fix double free of thumbnail data
- Throw OOME if Bitmap.nativeCreate fails
- Adjust Uri host parsing to use last instead of first @.
- SysUI: Add Russian translation for accessibility_battery_level_charging
- Automatic translation import

git://github.com/LineageOS/hudson

Changes
- hudson: Add Sony Xperia Z5 (sumire)
- hudson: Add Redmi 3S/3X (land)
- Add zerofltexx
- updater: Add Samsung Galaxy S6 (zerofltexx)
- Pull gtelwifiue and gtesqltespr
- Remove devices that never shipped from updater
- hudson: Pull hima
- Regenerate device dependency mappings

git://github.com/LineageOS/lineage_wiki

Changes
- devices: Add Sony Xperia Z5 (sumire)
- wiki: sony: Document installation for FOTA-only devices
- wiki: sony: Document pollux and pollux_windy unlock check
- wiki: land: remove unnecessary redirect lines
- fix maintainers to have array
- wiki: Add Redmi 3S/3X (land)
- Add info for the Samsung Galaxy S6 (zerofltexx)
- wiki: Add GPU Mali-T760 MP8
- device_build.md: Handle split userspace/CPU architecture
- wiki: Validate battery
- wiki: templates: Minor TWRP file naming tip changes
- wiki: Update bootloader unlocking guide for Xiaomi
- Mark discontinued devices
- wiki: Rework architecture to allow different archs for cpu and os

git://github.com/LineageOS/android_packages_apps_Dialer

Changes
- Automatic translation import
- Don't crash if Blocked Number Storage is disabled

git://github.com/LineageOS/android_packages_apps_Settings

Changes
- DevelopmentSettings: Fix possible NPE
- DevelopmentSettings: Hide OEM unlock by default
- Automatic translation import

git://github.com/LineageOS/android_system_core

Changes
- init: if permissive dont back out of starting a service
- libnetutil: Check dhcp respose packet length

git://github.com/LineageOS/android_vendor_cm

Changes
- ATV: Default double tap on home to the recents menu
- sensitive_pn: added Belgium & Switzerland
- Updated Syma APN
