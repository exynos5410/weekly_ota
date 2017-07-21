
git://github.com/exynos5410/android_device_samsung_exynos5410-common

Changes
- exynos5410-common: prop: Kang some values from hardware_ti_omap4 repo
- exynos5410-common: Make touchkeys light indipendent from the touchscreen
- exynos5410-common: Increase ImageEncoding quality to 100%

git://github.com/exynos5410/android_device_samsung_ja3gxx

Changes
- ja3gxx: ril: SlteRIL: Fix incoming calls
- ja3gxx: system.prop: Back to SlteRIL
- ja3gxx: ril: SlteRIL: Implement proper AMR_WB management for SM-P601 ril
- ja3gxx: include: Clean-up samsung audio header

git://github.com/LineageOS/android_frameworks_base

Changes
- improve compatibility when compiling with clang
- DO NOT MERGE "[PATCH] Zygote: Stop breaking the entire system"
- BootReceiver: check console-ramoops-0
- PowerProfile: allow overriding default power profile
- ScreenCap : Add jpeg support

git://github.com/LineageOS/android_frameworks_native

Changes
- Surface: Use async lock/unlock in copyBlt
- Surface: Ensure synchronisation of copyBlt
- surfaceflinger: Validate setposition parameters
- sf: Fix GPU coordinates computation.
- sf: Limit co-ordinates difference fix for high res panel
- surfaceflinger: Fix continuous SF dump.

git://github.com/exynos5410/android_kernel_samsung_exynos5410

Changes
- exynos5410: include: Fix duplicate declaration introduced by previous merge
- Revert "ARM: perf: reject groups spanning multiple hardware PMUs"
- crypto: ahash - Fix EINPROGRESS notification callback
- crypto: hash - Simplify the ahash_finup implementation
- crypto: hash - Pull out the functions to save/restore request
- crypto: hash - Fix the pointer voodoo in unaligned ahash
- crypto: ahash - Fully restore ahash request before completing
- net/packet: fix overflow in check for priv area size
- packet: handle too big packets for PACKET_V3
- ipv4: keep skb->dst around in presence of IP options
- tty: n_hdlc: get rid of racy n_hdlc.tbuf
- Revert "proc: smaps: Allow smaps access for CAP_SYS_RESOURCE"
- net: wireless: bcmdhd: adding boundary check in wl_cfg80211_mgmt_tx
- net: wireless: bcmdhd: fix use-after-free in _dhd_pno_get_for_batch()
- BACKPORT: posix_acl: Clear SGID bit when setting file permissions
- USB: digi_acceleport: do sanity checking for the number of ports
- USB: mct_u232: add sanity checking in probe
- ARM: perf: reject groups spanning multiple hardware PMUs
- ARM: dma-mapping: don't allow DMA mappings to be marked executable
- i9500: merge Samsung Kernel Source I9500XXUHQD1
- Revert "ion: disable system contig heap"
- Revert "perf: duplicate deletion of perf event"
- ALSA: timer: fix division by zero after SNDRV_TIMER_IOCTL_CONTINUE
- ALSA: pcm: Add snd_printd_ratelimit()
- samsung: don't bother with setting VM_IO
- ALSA: pcm: Use snd_printd_ratelimit()
- ALSA: vmaster: Fix the regression of missing vmaster hook call
- ALSA: vmaster: Add snd_ctl_sync_vmaster() helper function
- ALSA: Fix the default suffix string with high card number
- ALSA: Constify the snd_pcm_substream struct ops field
- ASoC: jack: Remove unnecessary call to snd_soc_dapm_new_widgets()
- ASoC: Fix early event callback list iteration
- ASoC: dapm: Provide early event callbacks for power up and down
- ASoC: dapm: Add snd_soc_dapm_switch to the power up/down sequence table
- snd_pcm_link(): fix a leak...
- ASoC: core: Use PTR_RET function
- ALSA: compress: add support for gapless playback
- exynos5410: arch: arm: ja: Disable SND_SUPPORT_OLD_API
- net: wireless: bcmdhd: fix buffer overrun in private command path
- ALSA: compress: fix an integer overflow check
- ALSA: compress: fix compilation error
- CVE-2016-9555: sctp: validate chunk len before actually using it
- CVE-2016-3857: arm: oabi compat: add missing access checks
- CVE-2012-6703: ALSA: compress - move the buffer check
- CVE-2012-6703: ALSA: compress_core: integer overflow in snd_compr_allocate_buffer()
- LVT-2017-0002: kernel: Fix potential refcount leak in su check
- CVE-2017-9242: ipv6: fix out of bound writes in __ip6_append_data()
- CVE-2017-9076, CVE-2017-9077: BACKPORT: ipv6/dccp: do not inherit ipv6_mc_list from parent Like commit 657831ffc38e ("dccp/tcp: do not inherit mc_list from parent") we should clear ipv6_mc_list etc. for IPv6 sockets too.
- CVE-2017-9075: BACKPORT: sctp: do not inherit ipv6_{mc|ac|fl}_list from parent SCTP needs fixes similar to 83eaddab4378 ("ipv6/dccp: do not inherit ipv6_mc_list from parent"), otherwise bad things can happen.
- CVE-2017-9074: ipv6: Check ip6_find_1stfragopt() return value properly.
- CVE-2017-9074: ipv6: Prevent overrun when parsing v6 header options
- CVE-2016-2550: unix: correctly track in-flight fds in sending process user_struct
- CVE-2013-4312: unix: properly account for FDs passed over unix sockets
- CVE-2016-10208: ext4: fix fencepost in s_first_meta_bg validation
- CVE-2016-10208: ext4: fix condition of validate s_first_meta_bg
- CVE-2017-8890: dccp/tcp: do not inherit mc_list from parent
- CVE-2017-2671: ping: implement proper locking
- CVE-2017-2618: selinux: fix off-by-one in setprocattr
- CVE-2017-1000365: fs/exec.c: account for argv/envp pointers
- CVE-2017-0510: BACKPORT: fiq_debugger: restrict access to critical commands.
- kernel: Only expose su when daemon is running
- mm/mempolicy.c: fix error handling in set_mempolicy and mbind.
- scsi: sg: check length passed to SG_NEXT_CMD_LEN
- BACKPORT: sg: relax 16 byte cdb restriction
- BACKPORT: block: add blk_rq_set_block_pc()
- xfrm_user: validate XFRM_MSG_NEWAE XFRMA_REPLAY_ESN_VAL replay_window
- KEYS: Change the name of the dead type to ".dead" to prevent user access
- sctp: deny peeloff operation on asocs with threads sleeping on it
- irda: Fix lockdep annotations in hashbin_delete().
- packet: fix races in fanout_add()
- net/llc: avoid BUG_ON() in skb_orphan()
- tcp: avoid infinite loop in tcp_splice_read()
- dccp: fix freeing skb too early for IPV6_RECVPKTINFO
- perf: Do not double free
- sctp: avoid BUG_ON on sctp_wait_for_sndbuf
- tcp: do not lock listener to process SYN packets
- time: Remove CONFIG_TIMER_STATS
- ipc/shm: Fix shmat mmap nil-page protection
- trace: resolve stack corruption due to string copy
- fs/proc/array.c: make safe access to group_leader
- ALSA: info: Check for integer overflow in snd_info_entry_write()
- perf: don't leave group_entry on sibling list (use-after-free)
- netlink: Fix dump skb leak/double free
- ALSA: pcm : Call kill_fasync() in stream lock
- UPSTREAM: net: avoid signed overflows for SO_{SND|RCV}BUFFORCE
- UPSTREAM: ring-buffer: Prevent overflow of size in ring_buffer_resize()
- KEYS: Disallow keyrings beginning with '.' to be joined as session keyrings
- splice: introduce FMODE_SPLICE_READ and FMODE_SPLICE_WRITE
- packet: fix race condition in packet_set_ring
- mpi: Fix NULL ptr dereference in mpi_powm() [ver #3]
- net: ping: Fix stack buffer overflow in ping_common_sendmsg()
- block: fix use-after-free in sys_ioprio_get()
- block: fix use-after-free in seq file
- BACKPORT: posix_acl: Clear SGID bit when setting file permissions
- KEYS: Fix short sprintf buffer in /proc/keys show function
- perf: protect group_leader from races that cause ctx double-free
- ppp: take reference on channels netns
- fix infoleak in rtnetlink
- usbnet: cleanup after bind() in probe()
- Replace %p with %pK to prevent leaking kernel address
- ipv4: Don't do expensive useless work during inetdev destroy.
- USB: cdc-acm: more sanity checking
- ext4: validate s_first_meta_bg at mount time
- l2tp: fix racy SOCK_ZAPPED flag check in l2tp_ip{,6}_bind()
- libceph: introduce ceph_crypt() for in-place en/decryption
- mm: Tighten x86 /dev/mem with zeroing reads
- sg_write()/bsg_write() is not fit to be called under KERNEL_DS
- BACKPORT: aio: mark AIO pseudo-fs noexec
- perf: duplicate deletion of perf event
- perf: Tighten (and fix) the grouping condition
- arm: fix handling of F_OFD_... in oabi_fcntl64()
- perf: Fix race in swevent hash
- sg: Fix double-free when drives detach during SG_IO
- fs: ext4: disable support for fallocate FALLOC_FL_PUNCH_HOLE
- Input: aiptek - fix crash on detecting device without endpoints
- net: llc: use correct size for sysctl timeout entries
- KEYS: fix keyctl_set_reqkey_keyring() to not leak thread keyrings
- ion: disable system contig heap
- BACKPORT: fs: limit filesystem stacking depth
- net: cleanups in sock_setsockopt()
- arm: mach-exynos: Fix typo for if declaration

git://github.com/LineageOS/hudson

Changes
- Re-enable LG G2 builds
- hudson: disable devices with unpatched dirty cow
- Revert "hudson: disable athene for now"

git://github.com/LineageOS/mirror

Changes
- Updated to 18-Jul-2017 20:31:00 UTC
- Updated to 14-Jul-2017 20:31:01 UTC

git://github.com/LineageOS/lineageos_updater

Changes
- changelog: Don't crash trying to parse change labels
- Regenerate device dependency mappings
- updater: devices: Better describe which SKUs go with hltetmo build

git://github.com/LineageOS/lineage_wiki

Changes
- wiki: Standardize the templates
- Update Nexus 6P and 5X bootloader unlock commands
- wiki: devices: Add details for supported SKUs in hltetmo build
- wiki: Set G2 maintainer
- Corrected small typos.

git://github.com/LineageOS/android_packages_apps_Gallery2

Changes
- Gallery: Fix potential crash
- Gallery2: Switch to navigationbar from support libs

git://github.com/LineageOS/android_packages_apps_Jelly

Changes
- Jelly: Remove unused variable in SearchBarController
- Jelly: Use proper popup background attr
- Jelly: Add "search in page" feature
- Jelly: Remove unneeded parameter type in addResult
- Jelly: Remove redundant character escape
- Jelly: Make suggestion provider "None" translatable
- Hide Sheet Menu after clicking on an entry
- Jelly: Query an already ordered favorite list
