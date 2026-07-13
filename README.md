# fx-a2sts · 大学英语视听说 A2 期末复习
> 郑州轻工业大学 · 移动软件专业 · 视听说 A2 听力复习资料
[![在线访问](https://img.shields.io/badge/在线访问-GitHub%20Pages-2563eb?style=flat-square)](https://moqix26.github.io/fx-a2sts/)
面向 **郑州轻工业大学移动软件专业**《大学英语视听说 A2》课程的期末复习网页。题目均摘自 **教材原题**，考试内容基本出自本资料，适合考前背诵与自测。
## 在线访问
**https://moqix26.github.io/fx-a2sts/**
打开 `index.html` 即可使用，无需安装任何依赖。
## 资料说明
本仓库整理了教材 **8 个 Unit** 的全部听力题目，每个单元包含三类题型：
| 题型 | 说明 |
|------|------|
| News Report | 新闻报道 · 通常 3 题 |
| Conversation | 长对话 · 通常 4 题 |
| Passage | 短文理解 · 通常 3 题 |
**共 8 个单元、约 80 道听力题**，附英文原文与中文译文。
## 单元目录
| Unit | 主题 |
|------|------|
| Unit 1 | The Future Me |
| Unit 2 | Handling Stress: Positive Psychology |
| Unit 3 | Enjoying Sports |
| Unit 4 | The Changing World |
| Unit 5 | Love's Magic Moment |
| Unit 6 | A Charitable Heart |
| Unit 7 | Glocalization |
| Unit 8 | The Beauty of Cultural Diversity |
## 功能特点
- **教材原题**：题目、选项、听力原文均来自教材，与考试范围一致
- **中英对照**：题目与选项左右分栏，英文与中文翻译同步展示
- **默认背答案**：默认只高亮显示正确选项，方便快速记忆
- **一键展开**：可切换「显示所有选项」「显示原文与译文」
- **随机答题**：内置全库随机抽题模式，模拟考试自测并自动计分
- **字号调节**：支持放大 / 缩小字体，阅读更舒适
- **记忆进度**：自动记住上次浏览的单元与字号设置
## 项目结构
fx-a2sts/ ├── index.html # 复习网页（单页，含全部题库数据） └── .github/workflows/ └── static.yml # GitHub Pages 自动部署

## 本地运行
本项目为纯静态网页，无需 Node.js 或构建工具。
```bash
# 克隆仓库
git clone https://github.com/moqix26/fx-a2sts.git
cd fx-a2sts
# 启动本地服务器（任选其一）
python -m http.server 8080
# 或
npx serve .
浏览器访问 http://localhost:8080 即可。

##使用建议
按单元复习：顶部导航切换 Unit 1–8，逐单元背诵答案
对照原文：点击「显示原文与译文」，结合听力材料理解语境
遮盖记忆：关闭「显示所有选项」，只看高亮正确答案强化记忆
考前自测：点击「随机答题」，检验掌握程度
##技术栈
HTML5 / CSS3 / 原生 JavaScript
单文件静态站点，无框架、无构建步骤、零依赖
##作者
MoQix26

GitHub：@moqix26
声明
本项目仅供课程复习与交流学习使用，题目内容摘自教材，请勿用于商业用途。

如有问题或建议，欢迎提交 Issue。
