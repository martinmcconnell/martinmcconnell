
```
┌─ martinthebad.sys ─────────────────────────────────────── ─ □ ✕ ┐
│                                                                  │
│   Martin McConnell                                               │
│   Linux kernel engineer · ARM64 · C                              │
│   ex-Red Hat (RHIVOS automotive)  ·  Waterford, Ireland          │
│                                                                  │
└──────────────────────────────────────────────────────────────────┘
```

<p>
<img src="https://img.shields.io/badge/arch-aarch64-ff4fd8?style=flat-square" alt="aarch64">
<img src="https://img.shields.io/badge/lang-C11-7b2ff7?style=flat-square" alt="C11">
<img src="https://img.shields.io/badge/kernel-backports%20%2B%20bring--up-1a3cff?style=flat-square" alt="kernel">
<img src="https://img.shields.io/badge/learning-Rust-ff4fd8?style=flat-square" alt="Rust">
<a href="https://martinthebad.neocities.org"><img src="https://img.shields.io/badge/web--log-neocities-7b2ff7?style=flat-square" alt="web-log"></a>
<a href="https://martinthebad.neocities.org/blog/feed.xml"><img src="https://img.shields.io/badge/rss-feed-1a3cff?style=flat-square" alt="RSS"></a>
</p>

### `▸ whoami.exe`

I work at the point where Linux meets hardware. I spent about 2.5 years at Red Hat carrying a distro kernel
(CentOS Stream 9 / RHEL 9) for ARM64 automotive SoCs (TI Jacinto, Renesas, Qualcomm), from driver
backports and device tree changes through to building images and flashing boards. Now I'm working on the
weird-machine end of things: IBM Z, the Rockchip RK3576, and kernel Rust.

### `▸ shipped.log`: merged work (it lives on GitLab, not here)

| what | where |
| --- | --- |
| Cadence USB3 (cdns3/cdnsp) driver backport, upstream v5.14 → v6.9, TI Jacinto j784s4, about 19 commits with hand-resolved conflicts | [centos-stream-9 !5116](https://gitlab.com/redhat/centos-stream/src/kernel/centos-stream-9/-/merge_requests/5116) |
| TI OMAP2+ mailbox enablement for j784s4: device tree + Kconfig | [centos-stream-9 !4905](https://gitlab.com/redhat/centos-stream/src/kernel/centos-stream-9/-/merge_requests/4905) |
| Configurable image compression limit, verified by flashing a Qualcomm RideSX4 | [aboot-update !21](https://gitlab.com/CentOS/automotive/rpms/aboot-update/-/merge_requests/21) · [osbuild-auto !14](https://gitlab.com/CentOS/automotive/rpms/osbuild-auto/-/merge_requests/14) |

### `▸ kernel.log`: notes from the web-log

- [getting back into it: lkml, neomutt, lei, b4](https://martinthebad.neocities.org/blog/22-05-2026.html)
- [the lay of the land: IBM Z (s390x)](https://martinthebad.neocities.org/blog/kernel-00.html)
- [ibm z: running arm64 guests on a mainframe](https://martinthebad.neocities.org/blog/kernel-01.html)
- [rust: upskilling toward kernel rust](https://martinthebad.neocities.org/blog/kernel-02.html)
- [rockchip rk3576: picking a board for the flipper one](https://martinthebad.neocities.org/blog/kernel-03.html)
- [rockchip rk3576: build, boot, baseline](https://martinthebad.neocities.org/blog/kernel-04.html)

### `▸ junkers.log`: a from-scratch C game engine

A 2D parkour platformer written in C11 on SDL3, with an arena allocator, swept collision, parkour as a state machine and
baked lighting. It's kept clean under ASan, Valgrind and clang-tidy, and the art and music are mine too.
[8-part devlog →](https://martinthebad.neocities.org/blog/junkers-00.html)

### `▸ toolbox.ini`

```ini
[kernel]     arm64 · device tree · kconfig · usb · perf/pmu · kselftest · cross-compile (gcc / clang)
[distro]     rpm spec files · osbuild · createrepo_c · fastboot/aboot images · beaker · tmt
[checks]     asan · ubsan · valgrind · clang-tidy · checkpatch · sparse · smatch
[workflow]   git at patch-series scale · lei · b4 · neomutt
[re/hw]      ghidra · rizin · gdb · jtag/uart · libreboot · proxmark3 · rtl-sdr
```

```
┌─ contact.ini ─── ─ □ ✕ ┐
│ ▸ web-log   martinthebad.neocities.org
│ ▸ linkedin  linkedin.com/in/martin-mcconnell1
│ ▸ medium    medium.com/@martinthebad
└────────────────────────┘
```

<sub>LIBRE CULTURE · OPEN SOURCE IT ALL · MAKE ART · ENCRYPT EVERYTHING</sub>
