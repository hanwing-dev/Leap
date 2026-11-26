<div align="center">
  <img src="assets/leap-icon.png" alt="Leap 图标" width="80" />
  <h1>Leap</h1>
  <p><strong>把学习通和雨课堂的任务，放进一个 Windows 工作台。</strong></p>
  <p>查待办和截止时间、接着看课程视频、接收学习通签到提醒。</p>
  <p>
    <a href="https://github.com/hyx-aero-ai/Leap/releases/latest"><strong>下载 Windows 版</strong></a>
    · <a href="GUIDE.md">中文使用手册</a>
    · <a href="HISTORY.md">开发历程</a>
    · <a href="https://github.com/hyx-aero-ai/Leap/issues">反馈问题</a>
  </p>
  <p>Windows 10 / 11 · x64 · 支持浅色与深色主题</p>
</div>

## 平时能用它做什么？

| 你想做的事 | Leap 的入口 |
| --- | --- |
| 看看还有哪些作业要交 | 在**作业列表**切换学习通或雨课堂，按课程、任务名或完成状态查找。识别到的截止时间会显示在列表里，点击「去完成」进入平台原页。 |
| 接着看一门课的待学视频 | 在**刷课**里选择课程，单独打开一节或连续播放本课程。悬浮小窗可以查看进度、暂停和调整网页支持的倍速。 |
| 及时看到新签到 | 在**签到**页检查学习通活动。开启后台检查并让 Leap 留在托盘，新签到可通过 Windows 通知提醒。 |
| 转写听力或查看 AI 辅助内容 | 部分听力可转写为文字。需要 AI 辅助时，可在**设置**里接入自己的模型服务。只用任务列表、视频和签到提醒，无需 API Key。 |

## 三步开始

1. 在[最新发行版](https://github.com/hyx-aero-ai/Leap/releases/latest)下载 Windows x64 的 MSI。需要 Microsoft Edge WebView2 Runtime，安装包同时提供 SHA-256 校验文件。
2. 安装后打开 Leap，进入 **设置 → 平台登录**，登录你正在使用的教学平台。
3. 回到 **作业列表 → 刷新作业列表**，切换平台查看结果。想接着看课，从左侧进入「刷课」并选一门课程。

安装、备份迁移、AI 配置和常见问题见[中文使用手册](GUIDE.md)。

## 使用前可以了解

- **为什么有些任务显示「待核对」？** 平台可能没有提供可识别的截止时间，或者这一轮有目录未读取完整。可以在扫描详情查看受影响的课程，最终以平台原页为准。
- **关闭窗口后还能收到签到提醒吗？** Leap 必须继续运行。选择收起到托盘即可保留提醒。平台要求扫码、定位或其他验证时，请按网页提示本人完成。
- **要把 API Key 交给谁？** 在软件的模型设置页填写你自己的 Key，只有使用 AI 功能时才需要。Key 由当前 Windows 用户加密保存，备份里不包含密钥。

## 从早期 Beta 到 Leap

项目最早叫 AI Homework Assistant，随后更名为 courseX，最终成为 Leap。正式版从 **1.0.0** 开始，旧版保留原编号并标注为 Beta。可以在[开发历程](HISTORY.md)查看每个阶段和可下载的历史构建。

如果 Leap 帮你少切了几个网页，欢迎给项目点个 Star。遇到识别遗漏、界面问题或想建议一个更顺手的操作，可以在 [Issues](https://github.com/hyx-aero-ai/Leap/issues) 留下平台、版本和复现步骤。

开发者 **Hanyx** · [GitHub](https://github.com/hyx-aero-ai) · [X](https://x.com/han526819930421)
