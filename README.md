# 发票匣子 · Windows 桌面版发布页

本仓库只发布 Windows 桌面版安装包、更新清单和更新日志，不包含源代码。

> 本仓库是发票匣子 Windows 桌面版的唯一发布渠道；请只从这里下载。

> 当前安装包暂未做代码签名，Windows SmartScreen 可能提示“未知发布者”。请只从本仓库下载，并用下方的 SHA-512 核对文件。

## 下载

请到 [Releases](https://github.com/kkeven0911/Fapiaobox/releases) 查看所有版本。当前最新为 [v1.0.3](https://github.com/kkeven0911/Fapiaobox/releases/tag/v1.0.3)，可直接下载 [FapiaoBox-Setup-1.0.3.exe](https://github.com/kkeven0911/Fapiaobox/releases/download/v1.0.3/FapiaoBox-Setup-1.0.3.exe)。

## 安装

1. 下载 `FapiaoBox-Setup-x.y.z.exe`；
2. 关闭正在运行的发票匣子；
3. 运行安装包，按提示覆盖安装；
4. 覆盖安装通常保留原安装目录中的数据、备份和设置。升级前建议先复制整个安装目录（至少 `data`、`bak`、`config`）。

## 验证

每个 Release 附带 `latest.yml`，其中包含安装包的 SHA-512。如需手动核对，可在 PowerShell 中执行：

```powershell
Get-FileHash .\FapiaoBox-Setup-x.y.z.exe -Algorithm SHA512
```

## 问题反馈

- 邮箱：dorothywild368@gmail.com
- 反馈时请附上版本号、操作步骤和截图；请勿发送发票原件、身份证号或邮箱授权码。

## 版权

© 2026 发票匣子 · 保留所有权利。本仓库仅用于发布二进制安装包和更新信息。
