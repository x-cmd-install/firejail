# firejail

[English version](./README.md)

Linux namespaces and seccomp-bpf sandbox

![firejail](https://repo.x-cmd.io/firejail.svg?lang=zh)

## 安装

```sh
x install firejail
```

## 代码洞察

合计: **59,247** 行代码（覆盖前 5 种语言、共 **290** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| C | 33,992 | 5,891 | 5,193 | 143 |
| CHeader | 14,134 | 727 | 344 | 56 |
| Autoconf | 5,416 | 178 | 736 | 14 |
| Bitbake | 2,568 | 264 | 143 | 32 |
| Sh | 1,684 | 363 | 464 | 45 |

## OpenSSF Scorecard 评分

总评分: **6.8 / 10**

评分最低的几项:

- **Packaging** (-1/10) — packaging workflow not detected
- **Code-Review** (3/10) — Found 5/16 approved changesets -- score normalized to 3
- **CII-Best-Practices** (0/10) — no effort to earn an OpenSSF best practices badge detected

## 源代码

- **上游仓库**: <https://github.com/netblue30/firejail>
- **官网**: <https://firejail.wordpress.com>
- **许可证**: GPL-2.0

## 发布

- **最新版本**: `0.9.80` (2026-03-14)
- **最近提交**: 2026-09-11
- **Release 含资产**: 4 个

## 流行度

- **Star**: 7,639 · **Fork**: 675 · **开放 issue**: 3,522 · **贡献者**: 344

## 累计统计

- **发布数**: 16 · **已合并 PR**: 2666 · **开放 PR**: 21 · **已关闭 issue**: 3020 · **开放 issue**: 502 · **提交数**: 11153

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-12 | 0 | 8 | 1 | 1 | 0 | 35 |
| last60d | 2026-07-13 | 0 | 19 | 1 | 8 | 1 | 102 |
| 90d | 2026-06-13 | 0 | 24 | 1 | 15 | 2 | 157 |
| last180d | 2026-03-15 | 0 | 62 | 3 | 22 | 14 | 242 |
| 360d | 2025-09-16 | 2 | 143 | 10 | 70 | 42 | 579 |
| last720d | 2024-09-21 | 4 | 320 | 11 | 136 | 98 | 1003 |

## Release 资产

| 资产 | 大小 | 目标平台 |
|------|-----:|----------|
| [firejail-0.9.80.asc](https://github.com/netblue30/firejail/releases/download/0.9.80/firejail-0.9.80.asc) | 724 B | `other` |
| [firejail-0.9.80.tar.xz](https://github.com/netblue30/firejail/releases/download/0.9.80/firejail-0.9.80.tar.xz) | 536.0 KiB | `other` |
| [firejail-0.9.80.tar.xz.asc](https://github.com/netblue30/firejail/releases/download/0.9.80/firejail-0.9.80.tar.xz.asc) | 488 B | `other` |
| [firejail_0.9.80_1_amd64.deb](https://github.com/netblue30/firejail/releases/download/0.9.80/firejail_0.9.80_1_amd64.deb) | 551.5 KiB | `runtime/deb/amd64` |

## 发行版状态

在 [repology.org](https://repology.org/project/firejail) 上共有 **100** 个发行版报告此项目。**39** 个 ✅ 已是最新上游版本，**51** 个 ⚠️ 使用旧版本。

| 发行版 | 版本 | 状态 |
|--------|------|------|
| Debian unstable | `0.9.80` | ✅ latest |
| Debian 13 | `0.9.74` | ⚠️ outdated |
| Ubuntu 26.04 LTS | `0.9.72` | ⚠️ outdated |
| Ubuntu 24.04 LTS | `0.9.72` | ⚠️ outdated |
| Arch | `0.9.80` | ✅ latest |
| Fedora rawhide | `0.9.80` | ✅ latest |
| Nix unstable | `0.9.80` | ✅ latest |
| Void | `0.9.80` | ✅ latest |
| openSUSE Tumbleweed | `0.9.80` | ✅ latest |

## 改进这些数据

firejail 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `firejail` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/firejail.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/260911.yml` · 2026-09-11T05:22:02Z._
