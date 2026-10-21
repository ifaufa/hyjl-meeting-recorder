# HYJL 会议记录 · 发行版

Windows 桌面端会议记录工具：实时字幕 + 会后 PDF / HTML 报告。
**本仓库只用于发布绿色版安装包，不包含源代码。**

## 下载

请到 [Releases](../../releases) 下载**最新版本**，每个 Release 包含两个文件：

- `HYJL-Meeting-Recorder-v<版本>-win64.zip` —— 主程序（解压即用，解压后文件夹名为中文）
- 同名 `.sha256` —— 校验值

## 快速开始

1. 核对 SHA-256（`certutil -hashfile 文件名 SHA256`）；
2. 解压到普通文件夹（不要放 `C:\Program Files`）；
3. 双击「启动.bat」，浏览器打开 <http://localhost:8080/>。

详细安装、SmartScreen 说明、校验方法与使用说明见包内 `软件说明.txt`。

## 系统要求

Windows 10 / 11（64 位），需要联网。无需安装 .NET。

## 许可与隐私

- 许可证：Apache License 2.0（见 `LICENSE.txt`）
- 隐私说明：见包内 `隐私说明.txt`
- 第三方组件：见包内 `第三方组件声明.txt`

## 反馈

ifaufa@hotmail.com（请附 `data\logs\` 日志）
