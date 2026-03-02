# chat-porter
> chatGPT和Claude聊天记录解析以及导出md前端页面

🌌 Chat Porter (GPT & Claude to Obsidian)

这是一个专门为 Obsidian 用户设计的聊天记录转换工具。它可以将 ChatGPT 和 Claude 官方导出的 JSON 文件，转换成符合个人排版习惯的 .md 格式。

✨ 功能亮点

多平台支持：完美兼容 ChatGPT 和 Claude 的官方导出 JSON。

Obsidian 适配排版：

用户输入自动识别为 > #user 格式。

AI 回复自动添加模型标签（如 #4o, #o3, #claude）。

每个对话块都带有精确到分钟的时间戳 [YY-MM-DD HH:mm]。

呼吸感布局：移除了冗余的分割线，在标签与正文间增加空行，防止 Obsidian 代码块渲染错误。

批量处理：支持一键将所有聊天记录打包成 .zip，方便直接拖入 Obsidian 库。

🚀 如何使用

下载或运行：下载本仓库的 聊天记录整理.html 文件。

浏览器打开：直接双击文件，在任何现代浏览器中运行。

上传 JSON：将你从 ChatGPT 或 Claude 官方导出的 conversations.json 上传。

预览与导出：在左侧搜索并选择对话，点击“保存到 Obsidian”或“批量打包”。

🛠️ 技术背景

这个项目诞生于我对知识管理的热爱。通过简单的 HTML/JS 实现本地化处理，保护隐私的同时，让 AI 的智慧能够无缝沉淀到我的本地知识库中
