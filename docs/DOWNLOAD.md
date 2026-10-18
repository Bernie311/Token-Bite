# 下载与安装

当前试用版：**v0.33.3-rc.1** · Windows 11 x64 · 免安装。

**[下载 Windows x64 程序包](https://github.com/Bernie311/Token-Bite/releases/download/v0.33.3-rc.1/TokenBite-v0.33.3-rc.1-windows-x64.zip)** · [打开发布页](https://github.com/Bernie311/Token-Bite/releases/tag/v0.33.3-rc.1)

## 下载哪个文件

在[本次发布页](https://github.com/Bernie311/Token-Bite/releases/tag/v0.33.3-rc.1)下方的 **Assets** 中选择以下附件，或直接点击表中的文件名。

| 文件 | 用途 |
|---|---|
| [`TokenBite-v0.33.3-rc.1-windows-x64.zip`](https://github.com/Bernie311/Token-Bite/releases/download/v0.33.3-rc.1/TokenBite-v0.33.3-rc.1-windows-x64.zip) | 完整免安装程序，下载此文件 |
| [`SHA256SUMS.txt`](https://github.com/Bernie311/Token-Bite/releases/download/v0.33.3-rc.1/SHA256SUMS.txt) | 下载文件的完整性校验值 |
| [`TokenBite-v0.33.3-rc.1-demo-videos.zip`](https://github.com/Bernie311/Token-Bite/releases/download/v0.33.3-rc.1/TokenBite-v0.33.3-rc.1-demo-videos.zip) | 可选：24 个功能演示的 MP4 视频 |
| `Source code (zip / tar.gz)` | GitHub 自动生成的展示仓库快照，只含文档和媒体，不含程序 |

试用版可能不在 GitHub 的 Latest 入口显示，请按版本标签选择。

## 首次使用

1. 将程序 ZIP **完整解压**到有读写权限的普通文件夹。
2. 确认 `TokenMini.exe`、`_internal`、`licenses` 和使用说明位于同一程序文件夹。
3. 双击 `TokenMini.exe`。无需另装 Python；不要只复制 EXE，也不要在压缩包内直接运行。
4. 本地统计需要已有 Codex 日志；官方额度查询需要本机已登录的 Codex CLI。无有效数据时显示横线或读取状态。
5. 单击精简浮窗展开；右下角打开用量明细；右键调整外观、显示大小和自动启动。

当前程序未进行数字签名。下载提示可能因 Windows 版本和安全软件而不同；先确认来源与文件校验值。请保留现有安全防护设置。

## 升级已有版本

1. 先退出 Token Bite，并关闭其跟随启动待命进程；无需关闭 Codex 或 ChatGPT。
2. 完整备份旧程序和退出后的 `data` 文件夹。
3. 将新包完整解压到一个新文件夹，再把旧 `data` 复制到新文件夹。
4. 从新文件夹启动，确认设置与统计。曾启用跟随启动时，在新程序的右键菜单重新选择原选项，使启动路径指向新位置。
5. 若需退回旧版本，先退出新程序；恢复旧程序时保留最新 `data` 的备份，不要删除缓存来尝试修复。

## 如何退出和删除

右键 → 退出 Token Bite。启用了跟随启动时，先在右键 → 自动启动中关闭该功能，避免待命进程重新唤起；退出后可删除程序文件夹。`data` 中包含设置和统计，是否保留由你决定。

[返回首页](../README.md) · [指标与常见问题](FAQ.md)
