# Nano-Banana Pro 开发者指南 (Developer Guide)

这是一个为 **Nano-Banana Pro** AI 模型打造的现代化、交互式开发者文档网站。该项目旨在以专业、直观的方式展示 Nano-Banana Pro 从“娱乐”到“专业生产力”的跨越式能力。

## 🌟 项目亮点

*   **沉浸式设计**: 采用高端暗色模式 (Dark Mode) 与香蕉黄 (Banana Yellow) 主色调，营造科技感与专业感。
*   **10 大核心能力详解**: 完整覆盖从“提示词黄金法则”到“高级编辑”、“结构控制”等 10 个关键技术章节。
*   **交互式体验**:
    *   **侧边栏导航**: 快速跳转至任意章节。
    *   **一键复制**: 所有提示词示例均配备代码块与“Copy”按钮，方便开发者直接使用。
*   **响应式布局**: 适配桌面端与移动端阅读体验。
*   **高质量视觉资产**: 包含由 AI 生成的演示图片，直观展示 2D 转 3D、思维链可视化等概念。

## 📂 项目结构

```
.
├── index.html          # 网站主入口，包含所有文档内容与结构
├── style.css           # 核心样式表，定义了设计系统、排版与响应式规则
├── assets/             # 静态资源目录
│   ├── hero_banner.png         # 首页 Hero 概念图
│   ├── feature_text.png        # 文本渲染示例
│   ├── feature_consistency.png # 角色一致性示例
│   ├── feature_2d_3d.png       # 2D 转 3D 示例
│   ├── feature_thinking.png    # 思维链可视化
│   ├── feature_storyboard.png  # 故事板示例
│   └── feature_structure.png   # 结构控制示例
└── README.md           # 项目说明文档
```

## 🚀 快速开始

### 本地预览

由于这是一个纯静态网站，您无需安装复杂的依赖即可运行。

1.  **直接打开**:
    双击 `index.html` 文件，使用任意现代浏览器（Chrome, Edge, Firefox）打开即可。

2.  **使用本地服务器 (推荐)**:
    为了获得最佳的资源加载体验，建议使用简单的 HTTP 服务器运行：

    ```bash
    # Python 3
    python -m http.server 8000

    # 或者使用 Node.js http-server
    npx http-server .
    ```
    然后在浏览器访问 `http://localhost:8000`。

## 📖 文档内容概览

1.  **提示词黄金法则**: 修改不重随、自然语言交互。
2.  **文本渲染**: 信息图表与排版。
3.  **角色一致性**: 身份锁定与病毒式构图。
4.  **搜索赋能**: 结合 Google Search 的实时数据可视化。
5.  **高级编辑**: 重绘、修复与上色。
6.  **维度转换**: 2D 图纸转 3D 渲染。
7.  **高分辨率**: 4K 纹理生成。
8.  **思考与推理**: 视觉逻辑分析。
9.  **故事板**: 单次生成连贯叙事。
10. **结构控制**: 线框图转 UI、像素艺术。

## 🛠️ 技术栈

*   **HTML5**: 语义化标签。
*   **CSS3**: 使用 CSS Variables 定义设计系统，Flexbox & Grid 布局。
*   **JavaScript**: 原生 JS 实现轻量级交互（复制功能）。
*   **Fonts**: Google Fonts (Inter, Noto Sans SC, JetBrains Mono)。

---
© 2025 Nano-Banana Pro Guide. Powered by Google DeepMind.
