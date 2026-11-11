# 发票匣子 · Windows 桌面版发布页

本仓库只发布 Windows 桌面版安装包、更新清单和更新日志，不包含源代码。

> GitHub 与 GitCode 均提供完整安装包，请只从这两个发布页下载。
>
> 当前安装包暂未做代码签名，Windows SmartScreen 可能提示“未知发布者”。请核对下方 SHA-256 后再安装。

## 下载

当前最新版本：**v1.10.21**

- GitHub：[FapiaoBox-Setup-1.10.21.exe](https://github.com/kkeven0911/Fapiaobox/releases/download/v1.10.21/FapiaoBox-Setup-1.10.21.exe)（完整安装包，201.7 MB）
- GitCode 国内下载：[v1.10.21 发行版](https://gitcode.com/ssss33/FapiaoBox/releases/tag/v1.10.21)（完整安装包）
- 所有版本：[GitHub Releases](https://github.com/kkeven0911/Fapiaobox/releases)

## 校验

- SHA-256：`be0178b82ef3521020fd7a7a3db0c6123079dba5e02481bd7ee30eac4734d981`
- SHA-512：`onttIL9cCz+IpOmwh8f2d39Enpc9V/X8hy7IWh/p7pnUkcyVaRtU4Wx1GmEZP9OLrt2LOmlNF3uI+oxV8DAyAw==`
- 大小：211528328 字节

每个 Release 附带 `latest.yml`，其中包含安装包的 SHA-512。如需手动核对，可在 PowerShell 中执行：

```powershell
Get-FileHash .\FapiaoBox-Setup-1.10.21.exe -Algorithm SHA256
```

## 安装

1. 下载 `FapiaoBox-Setup-1.10.21.exe`；
2. 关闭正在运行的发票匣子（包括托盘里的进程）；
3. 运行安装包，按提示覆盖安装；
4. 覆盖安装通常保留原安装目录中的数据、备份和设置。升级前建议先复制整个安装目录（至少 `data`、`bak`、`config`）。

## 问题反馈

- 邮箱：dorothywild368@gmail.com
- 反馈时请附上版本号、操作步骤和截图；请勿发送发票原件、身份证号或邮箱授权码。

## 版权

© 2026 发票匣子 · 保留所有权利。本仓库仅用于发布二进制安装包和更新信息。
