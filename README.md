# Deadline_app

轻量 Windows 桌面截止时间管理工具，支持任务清单、悬浮倒计时、完成归档与本地数据存储。

A lightweight Windows desktop deadline planner with task lists, floating countdowns, completion archives, and local data storage.

## 当前版本：v2.1.9

[下载 Windows x64 免安装版](https://github.com/frredomerror91-netizen/Deadline_app/releases/download/v2.1.9/Deadline-Desk-2.1.9.exe) · [发布说明与全部附件](https://github.com/frredomerror91-netizen/Deadline_app/releases/tag/v2.1.9)

本次修复语言切换后的顶栏与设置选项显示问题，适度放大截止时间和倒计时文字，取消悬浮窗剩余任务数的反色底块。版本号保持 2.1.9，保留三主题、任务编辑、月份分组及本地存储功能。

使用前从系统托盘完全退出旧版，再运行下载的 EXE。现有任务和设置保留。本次保持版本号不变，已经运行 2.1.9 的用户需要手动下载修复版。

## 发布附件

- `Deadline-Desk-2.1.9.exe`：Windows x64 便携程序。
- `Deadline-Desk-2.1.9.exe.sha256`：EXE 的 SHA-256 校验值。
- `Deadline-Desk-2.1.9-source.zip`：源码、依赖锁文件、测试、构建脚本与说明文档。

源码包不含个人任务、用户配置、依赖目录、缓存或构建产物。解压后按 `SOURCE-README.md` 安装依赖、测试和构建。

## 验证

通过 36 项单元测试、中英日三语言多宽度显示回归、150% 显示缩放、主题与任务编辑、空数据启动及实际便携 EXE 与源码一致性校验。
