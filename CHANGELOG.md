
git://github.com/LineageOS/android_frameworks_base

Changes
- improve compatibility when compiling with clang
- DO NOT MERGE "[PATCH] Zygote: Stop breaking the entire system"
- LocationTile: Improve strings

git://github.com/LineageOS/android_hardware_samsung

Changes
- secril-client: close fds on I/O errors
- power: Keep boost fd opened as well

git://github.com/LineageOS/cve_tracker

Changes
- Regenerate kernel->device mappings
- cve_tracker: Make kernel selection easier
- cve_tracker: add import statuses functionality

git://github.com/LineageOS/lineage_wiki

Changes
- Revamp contributing pages
- Rewrite docker support
- Use new wiki path in repo
- Use HTML entities for ellipses
- Update gems
- Remove dependency on github-pages
- wiki: Add Xiaomi Redmi Note 4 (mido)

git://github.com/LineageOS/android_packages_apps_Eleven

Changes
- Eleven: Add WRITE_MEDIA_STORAGE permission
- Eleven: Promote to privileged app
- Eleven: allow artwork to scale down

git://github.com/LineageOS/android_packages_apps_Gallery2

Changes
- Automatic translation import
- Gallery2: Fix various issues and glitches
- Gallery2: Fix potential crash
- Gallery2: Switch to navigationbar from support libs
- Gallery2: Fix can't parse documents uri
- Gallery2: Fix views overlap
- Gallery2: Support GIF animation
- Gallery2: Increase the size of the tiles when decoding images
- Gallery2: Support the newly added media file types in MTP mode
- Gallery2: Fix use of uninitialized stack variables
- Gallery2: Remove unused renderscript class
- Gallery2: Fix spelling error
- Gallery2: Properly declare the own permissions
- Gallery2: Remove more possible NPEs
- Gallery2: Enable frames in the editor
- Gallery2: Remove slideshow option if there are only videos
- Gallery2: Remove 3D overscroll effect
- Gallery2: Disable dummy starting window
- Gallery2: Fix up audio effects dialog
- Gallery2: Everyone or no one
- Gallery2: Replace hamburger menu with bottom bar
- Gallery2: Change all share intents to chooser style
- Gallery2: Update menu
- Gallery2: Update theme
- Gallery2: Move & improve CAF strings
- Gallery2: Make sure no NPE happens
- Gallery2: Remove invalid comment from manifest
- Gallery2: Cleanup renderscript flags in Android.mk
- Gallery2: Reduce logspam in video player
- Gallery2: Store DATE_TAKEN as milliseconds
- Gallery2: Modify AOSP EL translations
- Gallery2: Remove CAF translations
- Gallery2: Add record time to details view
- Gallery2: Fix crash of gallery on showing details
- Gallery2: Fix crash when Bluetooth service is disabled
- Gallery2: Try to open existing camera
- Gallery2: New icon
- Gallery2: Bump minsdk and targetsdk version
- Gallery: FilterShowActivity: Fix loading spinner being show forever
- Gallery: TileImageView: fix NPE
- FaceDetect: Catch more linker errors during initialization
- FaceDetect: Catch linker errors during initialization
- Bump API to match dependencies.
- Add missing includes.
- Cleanup warnings in jni.
- Fix misc-macro-parentheses warnings in Gallery2.
- Float.NaN != ... always evaluates to true, use Float.isNaN.
- Rename app back to Gallery

git://github.com/LineageOS/android_packages_apps_Snap

Changes
- Snap: fix low resolution front camera switch icon
- Revert "Revert "SnapdragonCamera: Adding PRIVILEGED true""

git://github.com/LineageOS/android_vendor_cm

Changes
- qcom: Allow setting custom audio, display, and media HALs
- templates: Update to show usage for new extract_files features
- extract_files: Add support for paths without system/
- extract_files: Add support for specifying blob sections
- build: Update smali and baksmali to 2.2.1
- Revert "Revert "vendor: cm: sepolicy: Allow rw-access to system_app_data_file""
- extract_utils: Fix cleanup variables assigment
