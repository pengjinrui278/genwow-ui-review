# 帧好 GenWow · UI 验收站

## 评审体验

- **推荐分享：[产品体验入口](https://pengjinrui278.github.io/genwow-ui-review/experience.html)**（下载、安装步骤、网页预览）
- [直接下载 Android v5 APK](https://github.com/chiiiiiiing/AI-camera/releases/download/v0.5.0-demo.20261020/GenWow-v5-debug.apk)
- [在线界面预览](https://pengjinrui278.github.io/genwow-ui-review/)
- [App 源码与版本说明](https://github.com/chiiiiiiing/AI-camera)

帧好GenWow，面向摄影新手的AI构图辅助相机，实时引导取景，轻松拍出好构图。

Android 安装包支持 Android 7.0 及以上 ARM 手机，约 92 MB。网页是交互示意，真实 AI 与拍摄功能请安装 APK；iPhone 只能浏览网页。

这是 [AI-camera](https://github.com/chiiiiiiing/AI-camera) 项目导出的**静态 UI 预览**，包含 24 个可独立打开的预览页面、一个产品体验入口及演示图片。v5 已同步自动场景识别、连续取景引导、圈内保持一秒自动拍摄示意，以及单行相机控制栏。它不是 Android App，也不会访问真实相机、账号或社区服务。

已上线的固定网址：[https://pengjinrui278.github.io/genwow-ui-review/](https://pengjinrui278.github.io/genwow-ui-review/)。

## Vercel 部署

在 Vercel 导入此仓库，Framework Preset 选择 **Other**，Root Directory 保持仓库根目录。`vercel.json` 已指定静态输出目录为 `.`，无需构建命令。生产分支设为 `main`；之后此仓库每次推送都会更新固定生产网址。

## 更新方式

页面源代码与图片来自原 AI-camera 仓库，**修改原仓库不会自动更新这里**。在原仓库本机执行 `ui-review/publish.ps1`，脚本会重新导出、检查此仓库工作区是否干净，并提交、推送新的静态文件。不要在此仓库直接编辑生成的 HTML；改动会在下次导出时被覆盖。

预览中的点赞、关注、评论和验收意见只保存在各自浏览器；要汇总意见，请使用网页的导出功能。
