# 🚀 Actions-BBR-v3 备份版

> 一个用于备份与长期维护的 BBRv3 GitHub Actions 自动编译项目。  
> 支持自动构建 Linux 内核，并集成 BBRv3 / TCP 网络加速优化。

![BBRv3](https://img.shields.io/badge/BBRv3-enabled-success?style=flat-square)
![GitHub Actions](https://img.shields.io/badge/GitHub-Actions-blue?style=flat-square)
![Kernel Build](https://img.shields.io/badge/Kernel-Build-green?style=flat-square)
![Backup Fork](https://img.shields.io/badge/Fork-Backup-orange?style=flat-square)

---

# ✨ 项目特点

- ⚡ 支持 **BBRv3** 拥塞控制算法
- 🛡️ 针对高延迟 / 丢包网络优化
- 🔄 基于 GitHub Actions 自动编译
- 📦 自动生成内核安装包
- 🌐 适用于 VPS / 云服务器 / 路由器
- 🧩 可自定义 Patch 与 Kernel Config
- 🪄 Fork 备份，防止上游仓库失效

---

# 📌 关于本 Fork

本仓库 Fork 自：

https://github.com/byJoey/Actions-bbr-v3

建立此仓库的目的：

- 🗂️ 作为长期备份镜像
- 🔒 防止原仓库失效或删除
- ⚙️ 方便个人修改与维护
- 🧪 测试实验性网络优化 Patch
- 🚀 持续维护自定义功能

---

# 🛠 功能支持

| 功能 | 状态 |
|---|---|
| BBRv3 | ✅ |
| TCP Brutal | ✅ |
| ECN 支持 | ✅ |
| GitHub Actions 自动编译 | ✅ |
| 自定义 Kernel Config | ✅ |
| IPv6 | ✅ |
| OpenWrt 相关使用 | ⚠️ 部分支持 |

---

# 🚀 如何使用？

## 1️⃣ 一键运行

```bash
bash <(curl -l -s https://raw.githubusercontent.com/caddaric9527/Actions-bbr-v3/refs/heads/main/install.sh)
