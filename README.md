# 多功能录制工具 更新发布源

本仓库只用于发布更新，程序启动时会读取这里的 version.json 检查新版本。

- version.json —— 版本清单（含版本号、更新说明、安装包下载地址、sha256 校验值与数字签名）
- 安装包本身放在 Releases 里
- 清单经过 ECDSA P-256 数字签名，程序内置公钥验签，验签不通过一律拒绝更新

手机版的发布源是另一个仓库：multifunction-recorder-android-updates