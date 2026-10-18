# Token Bite 0.33.3-rc.1 · Windows 试用版

> 已开放公开下载，版本标记为试用预发布（Pre-release）。[打开发布页](https://github.com/Bernie311/Token-Bite/releases/tag/v0.33.3-rc.1)。

把本机 Codex 的用量、额度和任务状态，放进一个 Windows 浮窗。

**闭源分发，仅提供可运行程序。当前版本为 Pre-release，未进行数字签名。**

## 下载

[下载 Windows x64 程序包](https://github.com/Bernie311/Token-Bite/releases/download/v0.33.3-rc.1/TokenBite-v0.33.3-rc.1-windows-x64.zip)，或在[发布页](https://github.com/Bernie311/Token-Bite/releases/tag/v0.33.3-rc.1)下方的 **Assets** 中选择 `TokenBite-v0.33.3-rc.1-windows-x64.zip`，完整解压后双击 `TokenMini.exe`，保留同级 `_internal` 文件夹。无需另装 Python。

`SHA256SUMS.txt` 提供校验值；`TokenBite-v0.33.3-rc.1-demo-videos.zip` 为可选的 24 段 MP4 演示。GitHub 自动生成的 Source code 文件只包含展示仓库文档和媒体，不包含程序。

## 可以做什么

- 查看今日与本次任务批次的确认 Token 消耗，分辨普通输入、缓存输入和输出。
- 查看 Codex 实际返回的官方剩余额度，以及可见文字输出的本地估算 TPS。
- 使用用量、模型和工具明细，按日期筛选、展开聊天构成并导出 CSV。
- 查看工具、技能和用户消息趋势，放大、平移、筛选曲线和读取日期数值。
- 使用浅色、深色或跟随系统外观，调整窗口大小、置顶、贴边隐藏和可选跟随启动。

产品动图和各项操作入口见仓库首页及功能演示文档。多数片段使用隔离演示数据；趋势图放大平移片段按素材包标注采用脱敏真实统计快照，以离屏方式演示（非桌面录屏）。

## 相比 0.33.2 的修复

- 补充冷缓存中跨日重叠任务所依赖的日志发现。
- 设置内容异常时保留原始文件并恢复可用字段，减少启动失败。
- 当前来源日志消失或不可读时保留最后确认值，并提示用量未同步。
- 必需图标、状态素材缺失，或数据目录不可读写时，给出中文启动处理提示；底层运行库缺失仍可能出现通用启动错误。

## 使用条件与已知限制

本版核实环境为 **Windows 11 x64**。本地统计需要可读的 Codex 日志；官方额度需要本机已登录的 Codex CLI。

历史仅覆盖已发现并缓存的本地记录；普通 ChatGPT、其他设备及未落盘的云端活动不计入本机统计。TPS 只估算连续可见输出，不代表隐藏推理或官方计费速度。没有覆盖所有 Windows 版本、ARM 或新机器环境。

录制时，精简／展开和显示大小切换曾观察到短暂黑块，原因尚未确认；对应动态片段已撤下，文档仅提供静态状态对照。尚未将其判定为已修复。

本版候选构建的已有记录包含 431 项源码测试及打包程序检查；本次仅整理分发文件、复核文件一致性和媒体解码，没有重新执行完整设备或物理交互验收。

## 升级与反馈

升级前退出 Token Bite 及其跟随启动待命进程，备份旧程序和退出后的 `data`。新旧 EXE 与 `_internal` 需成套使用；保留数据备份，不要通过删除缓存尝试升级。

问题请提交到本仓库 Issues，附版本、系统版本、重现步骤和脱敏截图。不要公开认证信息、原始聊天日志或 `data` 文件夹。

Token Bite 源代码不公开；使用条款与第三方许可随包提供。它是独立项目，与 OpenAI、Anthropic 无隶属或背书关系。

[完整安装说明](https://github.com/Bernie311/Token-Bite/blob/main/docs/DOWNLOAD.md) · [隐私说明](https://github.com/Bernie311/Token-Bite/blob/main/docs/PRIVACY.md) · [使用条款](https://github.com/Bernie311/Token-Bite/blob/main/LICENSE.txt) · [第三方组件与素材说明](https://github.com/Bernie311/Token-Bite/blob/main/THIRD-PARTY-NOTICES.md)
