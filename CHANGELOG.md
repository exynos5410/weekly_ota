
git://github.com/exynos5410/android_device_samsung_exynos5410-common

Changes
- exynos5410-common: BoardConfig: WEEKLY to MONTHLY release
- exynos5410-common: configs: Configure NXP audio effects

git://github.com/exynos5410/android_device_samsung_ja3gxx

Changes
- ja3gxx: bluetooth: Disable useless vendor config
- ja3gxx: ril: Move to lt033g RIL headers and class

git://github.com/LineageOS/android_frameworks_av

Changes
- AudioPolicyEffects: fix OOB read in input source array
- EffectsFactory: add debug and trace wrappers for NXP LifeVibes
- Add check preventing div0 issue
- Sanitize effect descriptors for AudioPolicyService binder calls.
- Init gain config to prevent uninit leak.

git://github.com/LineageOS/android_frameworks_base

Changes
- Fix wrong peek height of the notification panel
- Fix the "Alarm volume" icon is displayed incorrectly
- improve compatibility when compiling with clang
- DO NOT MERGE "[PATCH] Zygote: Stop breaking the entire system"
- SystemUI: Toggle USB tethering only when USB is connected
- Rework thumbnail cleanup
- ResStringPool: Fix security vulnerability
- Automatic translation import
- [BACKPORT] SystemUI: Fix alignment glitch with brightness mirror

git://github.com/LineageOS/android_frameworks_opt_telephony

Changes
- Fixed invalid pdu issue
- Telephony: Fix "Keep preferred SMS Sim"

git://github.com/LineageOS/android_hardware_samsung

Changes
- Audio: remove unsupported aec loopback stuff.
- MAC: add new Murata range
- Add missing murata and semco3rd mac addresses
- libsecril-client: provide req_id for SendOemRequestHook errors
- audio: Re-worked sound pre- and post-processing

git://github.com/LineageOS/hudson

Changes
- hudson: Build pioneer
- hudson: Re-add wt88047
- hudson: Promote Z00L & Z00T to 15.1
- Remove serrano3gxx/serranodsdd/serranoltexx
- hiae: Unlist hiae
- hudson: Add nash in devices json
- hudson: Ship Moto Z2 Force (nash)
- hudson: Rebalance 15.1 builds
- Re-add herolte/hero2lte
- hudson: Promote kccat6/lentislte to 15.1
- Unify find7s with find7 and promote to 15.1
- [bey-kuh n]
- Mix up Oreo
- Regenerate device dependency mappings
- Add mt2

git://github.com/LineageOS/mirror

Changes
- Updated to 29-Jun-2018 22:39:10 UTC
- Updated to 25-Jun-2018 15:39:45 UTC

git://github.com/LineageOS/www

Changes
- Reorganise engineering posts
- Pills: telephony
- Trust me, I'm an engineer
- Engineering layout

git://github.com/LineageOS/lineage_wiki

Changes
- wiki: Adapt install template for A/B devices
- wiki: Add Moto Z2 Force (nash)
- sdk: Fix lineage sdk jar name
- wiki: Add Xperia XA2 (pioneer)
- wiki: Re-add wt88047 and update install instructions
- wiki: Add Adreno 508 to GPUs list
- wiki: Promote Z00L and Z00T to 15.1 & update device info
- Mark herolte/hero2lte as maintained
- wiki: Add template for A/B recovery installation
- test: allow redirects in device templates
- wiki: use github as image host for CI
- wiki: Add the "Update recovery" solution for Error 7 to the FAQ
- devices: Additional fixes for 820/821 devices
- Update contributors list
- devices: Minor fixes for Xiaomi MSM8996 Pro devices
- bardock: Fixup some bad device specs info
- wiki: Add BQ bardock/bardockpro devices
- wiki: Update kccat6/lentislte to 15.1
- Unify find7s with find7 and promote to 15.1
- Promote bacon to 15.1 and update device info
- crackling, klte, lux: add physical dimensions
- verifying_builds: Update keytool command
- devices: add missing 'mm' to device sizes
- Mix up Oreo
- wiki: mt2: Ressurect
- wiki: Remove required_bootloader from zero devices

git://github.com/LineageOS/android_packages_apps_Dialer

Changes
- InCallUI: Refactor primary call info card
- Automatic translation import

git://github.com/LineageOS/android_packages_apps_Jelly

Changes
- Jelly: Show a Snackbar when removing an HistoryItem
- Jelly: add option to remove identifying headers

git://github.com/exynos5410/proprietary_vendor_samsung

Changes
- ja3gxx: Add NXP LifeVibes libraries 3.25.00
- ja3gxx: Update cbd and libsec-ril.so from k3gxx
