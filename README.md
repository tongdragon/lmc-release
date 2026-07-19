# LMC Release

LMC 竣工图合成系统 - 公开发布仓库

## 用途

此仓库存放 LMC 的发布资产：

- `dist/LMC.exe` - 轻量启动器（<10MB，通过 jsDelivr CDN 分发）
- `update_manifest.json` - 版本元数据（供客户端检查更新）
- GitHub Releases - 离线安装包（`lmc-offline-X.X.X.zip`）

## 源代码

源代码托管在私有仓库。

## 更新机制

客户端通过以下路径检查更新：

1. jsDelivr CDN: `https://cdn.jsdelivr.net/gh/tongdragon/lmc-release@master/update_manifest.json`
2. GitHub Raw: `https://raw.githubusercontent.com/tongdragon/lmc-release/master/update_manifest.json`

## 分支

- `master` - 稳定发布分支（由 CI 自动推送）
