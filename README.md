# AIMA（第 4 版）读书分享

本仓库用于《人工智能：一种现代的方法（Artificial Intelligence: A Modern Approach, 4th Edition）》的读书笔记与分享材料沉淀：包括章节要点整理、思考题/练习记录、扩展阅读链接与个人理解。

项目地址：https://github.com/XiaoJiNu/AIMAReading(https://xiaojinu.github.io/)

## 内容索引

- 第一部分·人工智能基础
  - 第 1 章·绪论：`第一部分-人工智能基础/第1章-绪论/4-AI历史回顾上.html`

## 私有材料（不公开）

推荐把“不想公开但需要跨设备同步”的材料放到一个**独立的 GitHub 私有仓库**里，并在本仓库通过 **Git submodule** 挂载到 `private/`（本仓库只保存子模块指针，不保存私有内容）。

初始化（一次性）：

1. 在 GitHub 新建私有仓库（例如 `AIMAReading-private`）
2. 在本仓库添加子模块：`git submodule add <private-repo-url> private`

拉取/换机器：

- 克隆公共仓库时：`git clone --recurse-submodules <public-repo-url>`
- 或在已克隆仓库里：`git submodule update --init --recursive`

日常提交：

- 提交私有材料：`cd private && git add -A && git commit -m "..." && git push`
- 更新公共仓库里的子模块指针：`cd .. && git add private .gitmodules && git commit -m "Update private submodule" && git push`

## 约定

- 以“章节”为单位组织内容；优先使用 Markdown，必要时附带导出的 HTML/PDF（例如演示稿/网页笔记）。
- 尽量给出引用来源（书中页码/章节、小节标题，或外部链接），并区分“原文观点”和“个人理解”。

## 贡献方式

- 欢迎提交 PR：补充勘误、完善笔记结构、添加练习与解答思路、整理参考资料。
- 文件命名建议：`第X章-标题/`、`序号-标题.md`（保持一致即可）。

## 免责声明

本仓库仅包含学习笔记与个人整理，不提供书籍原文或任何侵权内容；引用内容请控制在合理范围内并注明来源。
