
git://github.com/exynos5410/android_device_samsung_ja3gduosctc

Changes
- ja3gduosctc: Restore OTA support
- Merge pull request #2 from Pohrom/master
- Merge pull request #1 from exynos5410/cm-14.1
- fix acceptCall in SamsungLegacyRIL
- Merge pull request #1 from Pohrom/master

git://github.com/LineageOS/android_frameworks_base

Changes
- improve compatibility when compiling with clang
- DO NOT MERGE "[PATCH] Zygote: Stop breaking the entire system"

git://github.com/LineageOS/android_hardware_qcom_audio

Changes
- msm8937: hal: Support custom mixer_paths file names
- policy_hal: Don't fill in offload information for unsupported streams
- msm8937: acdb: Make acdb reloading optional
- ssr: Fix building with OSS materials
- msm8996: ultrasound: Initial open source hal for Elliptic Ultrasound
- msm8996: audio: Add l/r mic swapping when using stereo mics
- Add special case for stereo camcorder
- hal: Featureize APE/VORBIS/WMA offload support
- audio policy: fix capture indication to sound trigger service.
- hal: Don't try to record using 3-mic unless we mean it
- hal: Haxed header
- audio: Fix flac offload not working
- hal: Fix build with HDMI disabled
- audio: Fix complilation warnings under Clang
- msm8996: fix werror when AUDIO_FEATURE_ENABLED_DTS_EAGLE is enabled
- audio: Extend platform parser to allow device name aliasing
- hal: post_proc: enabled / disable volume listener based on prop
- hal: Support the audio amplifier hook
- audio: Use direct project pathmap

git://github.com/LineageOS/android_hardware_qcom_display

Changes
- display: Fix ColorMetaData
- display-caf: msm8996: Use ColorMetaData in SDM in hwc2
- display-caf: 8996: Add color metadata to libgralloc1
- hwc2: Only set display_width and display_height when equal to zero
- hwc2: Handle empty lists in AcceptDisplayChanges
- msm8996: hwc2: check for null layers in layer map
- hwc2 : Fix layer updating flag
- gralloc: Return an error if the buffer was not mapped
- Revert "Revert "gralloc: Default to 601 color space""
- hwc2: Workaround use after free by surfaceflinger
- hwc2: Update composition types on AcceptDisplayChanges
- Revert "gralloc: Default to 601 color space"
- gralloc: Disable UBWC for writeback buffers
- hwc2: Initialize color mode to native
- hwc2 : Allow only top most cursor layer
- Revert "gralloc: Return an error if the buffer was not mapped"
- hwc2: Fix solid fill
- sdm:hwc2: Store higher order mode id in case of clash
- gralloc: Return an error if the buffer was not mapped
- hwc2: Fix retire fences
- hwc2: Always store a release fence if a layer is presented
- hwc2: Use current frames retire fence only for the primary
- 8996/HWC2: Return this frame's retire fence
- hwc2: Remove default mode application at boot.
- hwc2: Support HWC2_CAPABILITY_SKIP_CLIENT_COLOR_TRANSFORM
- hwc: Set ioprio for vsync thread
- Fix duplicate copy file rules
- Don't build lights module if vendor supplies it
- display: Use project pathmap

git://github.com/LineageOS/android_hardware_qcom_media

Changes
- Fix duplicated OMX.qcom.audio.decoder.aac entry
- media: libOmxSw encoders require prop headers :(
- mm-video: Disable proprietary extension
- venc: Fix VQZip issue
- media: Avoid collision with FFMPEG plugin
- media: Use project pathmap

git://github.com/LineageOS/hudson

Changes
- hudson: add LG L90 (w7)
- hudson: pull v20s (h910 vs995 us996 ls997)
- Revert "Pull v521"
