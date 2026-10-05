# 帧好 GenWow · UI 验收站

这是 [AI-camera](https://github.com/chiiiiiiing/AI-camera) 项目导出的**静态 UI 预览**，包含 23 个可独立打开的页面和演示图片。它不是 Android App，也不会访问真实相机、账号或社区服务。

## Vercel 部署

在 Vercel 导入此仓库，Framework Preset 选择 **Other**，Root Directory 保持仓库根目录。`vercel.json` 已指定静态输出目录为 `.`，无需构建命令。生产分支设为 `main`；之后此仓库每次推送都会更新固定生产网址。

## 更新方式

页面源代码与图片来自原 AI-camera 仓库，**修改原仓库不会自动更新这里**。在原仓库本机执行 `ui-review/publish.ps1`，脚本会重新导出、检查此仓库工作区是否干净，并提交、推送新的静态文件。不要在此仓库直接编辑生成的 HTML；改动会在下次导出时被覆盖。

预览中的点赞、关注、评论和验收意见只保存在各自浏览器；要汇总意见，请使用网页的导出功能。
