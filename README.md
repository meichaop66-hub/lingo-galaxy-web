# 语言银河 · Web 发布版

语言银河是一个可探索的 3D 词源星图。每个词是一颗星，用户通过跃迁与词根关系探索词族。

**在线体验：** https://meichaop66-hub.github.io/lingo-galaxy-web/

## 本仓库的职责

本仓库是 GitHub Pages 的**公开静态发布仓**，不是日常开发真源。

- **产品需求、开发源文件、数据与发布脚本**：位于私有源仓 [lingo-galaxy](https://github.com/meichaop66-hub/lingo-galaxy)（仅授权维护者可访问）。
- **微信小程序原生适配**：位于 [lingo-galaxy-mp](https://github.com/meichaop66-hub/lingo-galaxy-mp)。
- **发布流程**：由源仓的 `publish.ps1` 同步指定发布文件；发布前保留检查与验收，不以每次提交自动上线替代发布闸。

请勿在本仓库直接编辑生成文件来开发新功能。发现问题请使用本仓库的 Issue 表单提交复现信息；功能与源文件修改应回到源仓处理。

## 技术与运行方式

这是静态网页发布物，通过 GitHub Pages 提供访问。GitHub Pages 默认入口为 `index.html`，主要产品页面为 `语言银河.html`；依赖随发布文件一起提供，当前发布版本无需运行本地后端服务。

## 版本与来源

本仓库只包含经挑选的发布文件。产品功能、数据来源、上游依赖与许可信息以源仓的 PRD、选型卡及相关声明为准：
- [源仓 README（私有，需授权）](https://github.com/meichaop66-hub/lingo-galaxy/blob/main/README.md)
- [产品需求文档（私有，需授权）](https://github.com/meichaop66-hub/lingo-galaxy/blob/main/PRD-%E8%AF%AD%E8%A8%80%E9%93%B6%E6%B2%B3-v1.1.md)
