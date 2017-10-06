
git://github.com/LineageOS/android

Changes
- manifest: track our own dnsmasq and libmpeg2
- manifest: use updated svox tag to fix picotts

git://github.com/LineageOS/android_build

Changes
- [DO NOT MERGE] Update platform security string to 2017-10-05 in nyc-dev Bug:64896113 (cherry picked from commit 1517f3d2da27eae798a3ac765096251914f9b119)
- [DO NOT MERGE] Update platform security string to 2017-10-01 in nyc-dev Bug:64896113 (cherry picked from commit 73ab80dec9df8966bf660725dc1a942d9c1f324e)

git://github.com/LineageOS/android_external_dnsmasq

Changes
- Add extra (size_t) cast to avoid compiler warning.
- Make dnsmasq more stable.

git://github.com/LineageOS/android_external_libhevc

Changes
- Fix slice decrement for skipped slices
- Ensure CTB size > 16 for clips with tiles and width/height >= 4096

git://github.com/LineageOS/android_frameworks_av

Changes
- Fix 'potential memory leak' compiler warning.
- Check buffer size in useBuffer in software components
- stagefright: avoid buffer overflow in base64 decoder
- Add EFFECT_CMD_SET_PARAM parameter checking to Downmix and Reverb
- Fix memory leak in OggExtractor
- Skip track if verification fails

git://github.com/LineageOS/android_frameworks_base

Changes
- improve compatibility when compiling with clang
- DO NOT MERGE "[PATCH] Zygote: Stop breaking the entire system"
- Fix security hole in GateKeeperResponse.
- Enforce policy for camera gesture in keyguard
- SystemUI: Cleanup BatteryMeter
- SystemUI: Improve battery icons
- Revert "Camera: ignore torch status update for aux or compsite camera"

git://github.com/LineageOS/android_libcore

Changes
- Fix failing FileTest#test_canonicalCachesAreOff()
- Disable File.getCanonicalPath caches.

git://github.com/LineageOS/lineageos_updater

Changes
- updater: improve changelog link wording
- updater: link to wiki pages on device download page
- Regenerate device dependency mappings

git://github.com/LineageOS/lineage_wiki

Changes
- devices: add custom twrp links for lux, merlin, and otus
- wiki: Adjusted us996 for US Unlocked vs. GSM Unlocked
- templates: allow devices to specify a custom twrp link
- wiki: ride off into the sunset
