# 发票匣子 · Windows 桌面版发布页

本仓库只发布 Windows 桌面版安装包、更新清单和更新日志，不包含源代码。

> GitHub 提供完整安装包，Gitee 提供国内镜像（按 100MB 分卷）。请只从这两个发布页下载。
>
> 当前安装包暂未做代码签名，Windows SmartScreen 可能提示“未知发布者”。请核对下方 SHA-256 后再安装。

## 下载

当前最新版本：**v1.10.6**

- GitHub：[FapiaoBox-Setup-1.10.6.exe](https://github.com/kkeven0911/Fapiaobox/releases/download/v1.10.6/FapiaoBox-Setup-1.10.6.exe)（完整安装包，198.9 MB）
- Gitee 国内镜像：[v1.10.6 发行版](https://gitee.com/deng_meng0911/FapiaoBox/releases/tag/v1.10.6)（下载全部 `.part` 文件与 `install.cmd` 到同一文件夹，运行 `install.cmd` 合并并校验）
- 所有版本：[GitHub Releases](https://github.com/kkeven0911/Fapiaobox/releases)

## 校验

- SHA-256：`e4bdf5f4c2addd88835340383193d9d22110b99065d8379362c0b07a05d850e5`
- SHA-512：`mK970I1XK3pqMcQMmOGNxNZHZfvxv/pQUtWoW2Zg/k3VwDZ9p9mp2hkQ5tN1m9Ex6E2YBDnyImP9JCO+RXLDrw==`
- 大小：208528829 字节

每个 Release 附带 `latest.yml`，其中包含安装包的 SHA-512。如需手动核对，可在 PowerShell 中执行：

```powershell
Get-FileHash .\FapiaoBox-Setup-1.10.6.exe -Algorithm SHA256
```

## 安装

1. 下载 `FapiaoBox-Setup-1.10.6.exe`；
2. 关闭正在运行的发票匣子（包括托盘里的进程）；
3. 运行安装包，按提示覆盖安装；
4. 覆盖安装通常保留原安装目录中的数据、备份和设置。升级前建议先复制整个安装目录（至少 `data`、`bak`、`config`）。

## 问题反馈

- 邮箱：dorothywild368@gmail.com
- 反馈时请附上版本号、操作步骤和截图；请勿发送发票原件、身份证号或邮箱授权码。

## 版权

© 2026 发票匣子 · 保留所有权利。本仓库仅用于发布二进制安装包和更新信息。
