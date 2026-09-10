# firejail

[中文版本](./README.cn.md)

Linux namespaces and seccomp-bpf sandbox

![firejail](https://repo.x-cmd.io/firejail.svg)

## Install

```sh
x install firejail
```

## Code insight

Total: **59,247** lines of code across **290** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| C | 33,992 | 5,891 | 5,194 | 143 |
| CHeader | 14,134 | 727 | 344 | 56 |
| Autoconf | 5,416 | 178 | 736 | 14 |
| Bitbake | 2,568 | 264 | 143 | 32 |
| Sh | 1,684 | 363 | 471 | 45 |

## OpenSSF Scorecard

Overall score: **6.8 / 10**

Lowest-scoring checks:

- **Packaging** (-1/10) — packaging workflow not detected
- **Code-Review** (3/10) — Found 5/16 approved changesets -- score normalized to 3
- **CII-Best-Practices** (0/10) — no effort to earn an OpenSSF best practices badge detected

## Source

- **Upstream**: <https://github.com/netblue30/firejail>
- **Homepage**: <https://firejail.wordpress.com>
- **License**: GPL-2.0

## Release

- **Latest**: `0.9.80` (2026-03-14)
- **Last commit**: 2026-09-10
- **Assets in release**: 4

## Popularity

- **Stars**: 7,639 · **Forks**: 675 · **Open issues**: 3,522 · **Contributors**: 344

## Totals (cumulative)

- **Releases**: 16 · **Merged PRs**: 2666 · **Open PRs**: 21 · **Closed issues**: 3020 · **Open issues**: 502 · **Commits**: 11144

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-11 | 0 | 8 | 1 | 1 | 0 | 26 |
| last60d | 2026-07-12 | 0 | 19 | 1 | 13 | 1 | 93 |
| 90d | 2026-06-12 | 0 | 24 | 1 | 15 | 2 | 148 |
| last180d | 2026-03-14 | 1 | 63 | 3 | 23 | 14 | 233 |
| 360d | 2025-09-15 | 2 | 143 | 10 | 71 | 42 | 570 |
| last720d | 2024-09-20 | 4 | 320 | 11 | 136 | 99 | 994 |

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
| [firejail-0.9.80.asc](https://github.com/netblue30/firejail/releases/download/0.9.80/firejail-0.9.80.asc) | 724 B | `other` |
| [firejail-0.9.80.tar.xz](https://github.com/netblue30/firejail/releases/download/0.9.80/firejail-0.9.80.tar.xz) | 536.0 KiB | `other` |
| [firejail-0.9.80.tar.xz.asc](https://github.com/netblue30/firejail/releases/download/0.9.80/firejail-0.9.80.tar.xz.asc) | 488 B | `other` |
| [firejail_0.9.80_1_amd64.deb](https://github.com/netblue30/firejail/releases/download/0.9.80/firejail_0.9.80_1_amd64.deb) | 551.5 KiB | `runtime/deb/amd64` |

## Distribution status

Reported by **100** distros on [repology.org](https://repology.org/project/firejail). **39** are ✅ on the latest upstream release, **51** are ⚠️ on an older version.

| Distro | Version | Status |
|--------|---------|--------|
| Debian unstable | `0.9.80` | ✅ latest |
| Debian 13 | `0.9.74` | ⚠️ outdated |
| Ubuntu 26.04 LTS | `0.9.72` | ⚠️ outdated |
| Ubuntu 24.04 LTS | `0.9.72` | ⚠️ outdated |
| Arch | `0.9.80` | ✅ latest |
| Fedora rawhide | `0.9.80` | ✅ latest |
| Nix unstable | `0.9.80` | ✅ latest |
| Void | `0.9.80` | ✅ latest |
| openSUSE Tumbleweed | `0.9.80` | ✅ latest |

## Improve this data

Install metadata for firejail lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `firejail` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/firejail.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/260910.yml` · 2026-09-10T23:11:09Z._
