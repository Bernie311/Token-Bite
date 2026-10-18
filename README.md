# Token Bite

**把本机 Codex 的用量、额度和任务状态，放进一个 Windows 浮窗。**

Windows 11 x64 · 免安装 · 0.33.3-rc.1 试用版 · 闭源分发

**[下载 Windows x64 试用版（v0.33.3-rc.1）](https://github.com/Bernie311/Token-Bite/releases/download/v0.33.3-rc.1/TokenBite-v0.33.3-rc.1-windows-x64.zip)** · [查看发布页](https://github.com/Bernie311/Token-Bite/releases/tag/v0.33.3-rc.1)

[安装与升级说明](docs/DOWNLOAD.md) · [指标与常见问题](docs/FAQ.md) · [隐私说明](docs/PRIVACY.md)

<img src="media/gifs/overview.gif" width="720" alt="Token Bite：今日用量浮窗和用量明细总览，使用隔离演示数据">

动图以隔离演示数据为主；“趋势图放大与平移”按素材包标注采用已脱敏的真实统计快照，制作为离屏交互演示（非桌面录屏）。这些素材不作为性能测试或实体鼠标操作验收。

## 一眼看到这次用了多少

今日消耗、本次任务批次消耗，以及普通输入／缓存输入／输出构成集中展示。任务状态与输出速率分别显示，避免把思考或工具执行误当作正在输出文字。

<img src="media/gifs/task-progress.gif" width="560" alt="任务开始、文字输出、结束后用量保留的界面演示">

额度按 Codex 实际返回的周／5 小时窗口展示；未知显示横线，过期值变暗。本机 Token 数量与官方额度百分比是两种指标。

## 知道消耗在哪里

用量明细提供今天、近 7 天、近 30 天视图，可按日期筛选，查看模型分布与聊天排行，展开输入、缓存和输出构成，并导出 CSV。

<img src="media/gifs/model-breakdown.gif" width="560" alt="展开模型，查看构成与关联聊天">

历史视图覆盖已发现并缓存的本地记录，不代表完整历史导入。

## 工具结果也能分清

工具页区分成功、失败、结果未知，以及可确认的耗时。用量页还能查看工具、技能和用户消息趋势。

<img src="media/gifs/tool-results.gif" width="560" alt="查看本地记录中的工具执行结果；缺少结果保持未知">

## 趋势图可以放大看

打开独立大图后，可放大、拖动平移、隐藏图例、查看日期读数，再一键复原。

<img src="media/gifs/chart-zoom-pan.gif?v=835bc1d3044e" width="720" alt="真实统计快照的趋势图放大与平移离屏演示">

## 浅色、深色，按习惯摆放

提供纸感浅色、温润深色和跟随系统；支持精简／展开、显示大小、置顶、拖动、贴边自动隐藏及可选跟随启动。

<img src="media/gifs/themes.gif" width="640" alt="通过右键菜单从纸感浅色切换为温润深色">

## 额度与任务状态

### 额度窗口与时效

按实际返回的数据展示周额度、5 小时额度或双窗口；未知和过期样本有不同表现。这是界面状态样本。

<a href="media/gifs/quota-windows.gif"><img src="media/gifs/quota-windows.gif" width="560" alt="额度窗口与时效，隔离演示数据"></a>

### 任务阶段

区分思考、工具执行、等待批准和文字输出。画面展示隔离状态样本，批准动作仍需回到 Codex 完成。

<a href="media/gifs/task-phases.gif"><img src="media/gifs/task-phases.gif" width="560" alt="任务阶段，隔离演示数据"></a>

### 未同步提示与恢复状态

数据不可用时保留最后确认值并提示，恢复后重新显示。这是隔离状态展示，不是真实网络断线恢复测试。

<a href="media/gifs/stale-state.gif"><img src="media/gifs/stale-state.gif" width="560" alt="未同步提示与恢复状态，隔离演示数据"></a>

### 程序内数据说明

从右键菜单打开数据说明，查看指标定义和隐私相关说明。

<a href="media/gifs/data-help.gif"><img src="media/gifs/data-help.gif" width="720" alt="程序内数据说明，隔离演示数据"></a>

## 更多用量分析演示

### 打开用量明细

点击浮窗右下角的用量明细，打开独立分析窗口。

<a href="media/gifs/open-details.gif"><img src="media/gifs/open-details.gif" width="720" alt="打开用量明细，隔离演示数据"></a>

### 切换统计范围

在今天、近 7 天和近 30 天之间切换；范围内只包含已发现并缓存的本地记录。

<a href="media/gifs/date-ranges.gif"><img src="media/gifs/date-ranges.gif" width="560" alt="切换统计范围，隔离演示数据"></a>

### 按日期筛选

点击柱状图中的日期区间，再清除筛选，查看统计如何联动。

<a href="media/gifs/date-filter.gif"><img src="media/gifs/date-filter.gif" width="560" alt="按日期筛选，隔离演示数据"></a>

### 核对统计

在明细菜单中核对当前工具统计。该片不代表外部官方账单核对。

<a href="media/gifs/reconcile.gif"><img src="media/gifs/reconcile.gif" width="720" alt="核对统计，隔离演示数据"></a>

### 聊天排行与详情

展开聊天，查看 Token 构成、模型、推理强度和速度模式等已记录维度。打开聊天的入口仅展示，没有跳转正式 Codex。

<a href="media/gifs/chat-breakdown.gif"><img src="media/gifs/chat-breakdown.gif" width="560" alt="聊天排行与详情，隔离演示数据"></a>

## 更多趋势图操作

### 滚动查看活动趋势

从用量区向下滚动到工具调用趋势。

<a href="media/gifs/scroll-trends.gif"><img src="media/gifs/scroll-trends.gif" width="560" alt="滚动查看活动趋势，隔离演示数据"></a>

### 图例筛选与日期读数

点击图例隐藏或恢复曲线，再按日期查看具体计数。

<a href="media/gifs/chart-legend.gif"><img src="media/gifs/chart-legend.gif" width="720" alt="图例筛选与日期读数，隔离演示数据"></a>

### 复原趋势图

点击复原，将大图返回完整日期范围。

<a href="media/gifs/chart-reset.gif"><img src="media/gifs/chart-reset.gif" width="720" alt="复原趋势图，隔离演示数据"></a>

### 技能与用户消息趋势

向下滚动，分别查看本地记录中的技能使用和用户消息。

<a href="media/gifs/skills-messages.gif"><img src="media/gifs/skills-messages.gif" width="560" alt="技能与用户消息趋势，隔离演示数据"></a>

### 切换消息统计维度

将消息趋势从按模型切换为按使用端。

<a href="media/gifs/message-dimensions.gif"><img src="media/gifs/message-dimensions.gif" width="720" alt="切换消息统计维度，隔离演示数据"></a>

### 打开趋势大图

从活动趋势右上角的放大入口进入独立大图。

<a href="media/gifs/open-chart.gif"><img src="media/gifs/open-chart.gif" width="720" alt="打开趋势大图，隔离演示数据"></a>

## 更多窗口操作

### 跟随启动选项

查看跟随 Codex、跟随 Codex 和 ChatGPT 桌面版、关闭自动启动三项。仅展示菜单，没有改变真实启动项；跟随 ChatGPT 启动不表示统计普通 ChatGPT。

<a href="media/gifs/startup-options.gif"><img src="media/gifs/startup-options.gif" width="720" alt="跟随启动选项，隔离演示数据"></a>

### 退出重开保留设置

隔离副本退出后重新启动，保留外观和窗口位置。

<a href="media/gifs/restore-settings.gif"><img src="media/gifs/restore-settings.gif" width="720" alt="退出重开保留设置，隔离演示数据"></a>

### 置顶与拖动

切换置顶开关，并拖动隔离浮窗；没有操作用户正在使用的正式浮窗。

<a href="media/gifs/pin-drag.gif"><img src="media/gifs/pin-drag.gif" width="720" alt="置顶与拖动，隔离演示数据"></a>

## 下载与使用方式

当前已开放 Windows 11 x64 免安装试用版。下载程序包并完整解压后即可运行。

1. [下载 Windows x64 程序包](https://github.com/Bernie311/Token-Bite/releases/download/v0.33.3-rc.1/TokenBite-v0.33.3-rc.1-windows-x64.zip)，或打开[本次发布页](https://github.com/Bernie311/Token-Bite/releases/tag/v0.33.3-rc.1)选择同名附件。
2. 完整解压到可写文件夹，保留 `TokenMini.exe` 和同级 `_internal` 文件夹；双击 `TokenMini.exe`。无需另装 Python。
3. 使用本机 Codex。首次读取可能需要等待；准确消耗在本地日志确认后更新。
4. 点击浮窗的“用量明细”深入查看；右键可设置外观和窗口行为。

本版核实环境为 Windows 11 x64。用量统计需要本机可读的 Codex 日志；官方额度依赖本机已登录的 Codex CLI。普通 ChatGPT 聊天、其他设备和未落盘的云端活动不计入本机统计。

## 数据与反馈

程序在本地读取日志、会话索引和运行状态，解析过程中会接触可见输出文本。设置与统计保存在程序同级 `data` 文件夹；官方额度查询可能通过 Codex CLI 联网。详情见[隐私说明](docs/PRIVACY.md)。

遇到问题请到本仓库 **Issues → New issue**，提供版本、系统版本、重现步骤和脱敏截图。请勿公开 `data` 文件夹、认证信息或原始聊天日志。

## 分发与许可

本仓库用于产品展示、文档与下载，**不公开 Token Bite 源代码**。程序按[二进制使用条款](LICENSE.txt)分发；第三方组件保留各自许可，见[第三方声明](THIRD-PARTY-NOTICES.md)。

Token Bite 是独立项目，与 OpenAI、Anthropic 无隶属或背书关系。当前为未签名试用版；兼容性与已知边界见[发布说明](docs/RELEASES.md)。
