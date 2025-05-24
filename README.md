# 🌟 个人主页网站

一个现代化、响应式的个人主页网站模板，专为展示个人技能、项目和联系信息而设计。

## ✨ 功能特点

- 🎨 **现代化设计**: 使用最新的CSS技术和设计趋势
- 📱 **完全响应式**: 适配所有设备（桌面、平板、手机）
- ⚡ **性能优化**: 快速加载和流畅的用户体验
- 🎭 **动画效果**: 精美的CSS动画和交互效果
- 📧 **联系表单**: 功能完整的联系表单（带验证）
- 🔗 **平滑导航**: 页面内平滑滚动导航
- 💻 **打字特效**: 动态打字效果展示职业角色
- 🌙 **现代UI**: 使用CSS变量和现代布局技术

## 🛠️ 技术栈

- **HTML5**: 语义化标记
- **CSS3**: 
  - CSS Grid & Flexbox
  - CSS变量
  - 动画与过渡效果
  - 响应式设计
- **JavaScript (ES6+)**:
  - DOM操作
  - 事件处理
  - 动画控制
  - 表单验证
- **外部资源**:
  - Google Fonts (Inter字体)
  - Font Awesome图标

## 📂 项目结构

```
├── index.html          # 主页面文件
├── styles.css          # 样式文件
├── script.js           # JavaScript功能文件
├── README.md           # 项目说明文档
└── .gitignore         # Git忽略文件
```

## 🚀 快速开始

### 本地运行

1. **克隆项目**
   ```bash
   git clone https://github.com/yourusername/your-homepage.git
   cd your-homepage
   ```

2. **直接在浏览器中打开**
   ```bash
   # 使用默认浏览器打开
   open index.html
   
   # 或者使用Live Server（推荐）
   # 如果你有VS Code，安装Live Server扩展
   # 然后右键index.html -> "Open with Live Server"
   ```

### 自定义内容

1. **个人信息**
   - 编辑 `index.html` 中的个人信息
   - 更换个人照片链接
   - 修改联系方式

2. **技能和项目**
   - 在技能部分添加你的技术栈
   - 在项目部分展示你的作品
   - 添加项目链接和GitHub链接

3. **颜色主题**
   - 在 `styles.css` 顶部的CSS变量中修改颜色
   - 自定义你喜欢的配色方案

## 📦 部署到GitHub Pages

### 方法一：直接上传

1. **创建GitHub仓库**
   - 登录GitHub，创建新仓库
   - 仓库名建议使用: `yourusername.github.io`

2. **上传文件**
   ```bash
   git init
   git add .
   git commit -m "初始化个人主页"
   git branch -M main
   git remote add origin https://github.com/yourusername/yourusername.github.io.git
   git push -u origin main
   ```

3. **启用GitHub Pages**
   - 进入仓库设置 (Settings)
   - 滚动到 "Pages" 部分
   - Source选择 "Deploy from a branch"
   - Branch选择 "main" / "root"
   - 点击Save

4. **访问网站**
   - 几分钟后，访问: `https://yourusername.github.io`

### 方法二：GitHub Desktop

1. 下载并安装 GitHub Desktop
2. 点击 "Create a New Repository"
3. 设置本地路径，拖拽文件到仓库
4. 提交并推送到GitHub
5. 在GitHub网站上启用Pages

## 🎨 自定义指南

### 更换配色方案

在 `styles.css` 文件顶部找到CSS变量：

```css
:root {
    --primary-color: #4f46e5;      /* 主色调 */
    --secondary-color: #06b6d4;    /* 次要色调 */
    --accent-color: #f59e0b;       /* 强调色 */
    /* 修改这些值来改变整体配色 */
}
```

### 添加新功能

1. **新增部分**: 在HTML中添加新的section
2. **样式定制**: 在CSS中添加对应样式
3. **交互功能**: 在JavaScript中添加交互逻辑

### 个性化内容

- 📝 修改关于我的描述
- 🏷️ 更新技能标签
- 🖼️ 替换项目截图
- 📞 更新联系信息
- 🔗 添加社交媒体链接

## 📱 响应式特性

- **桌面端** (≥1200px): 完整布局
- **平板端** (768px-1199px): 调整网格布局
- **手机端** (≤767px): 单列布局，汉堡菜单

## 🔧 常见问题

### Q: 如何更换个人照片？
A: 将你的照片上传到图片托管服务（如GitHub、Imgur），然后替换HTML中的图片链接。

### Q: 联系表单可以真正发送邮件吗？
A: 当前是模拟功能。要实现真正的邮件发送，需要后端服务支持或使用第三方服务如Formspree、Netlify Forms等。

### Q: 如何添加更多项目？
A: 复制项目卡片的HTML结构，修改内容和链接即可。

### Q: 可以添加博客功能吗？
A: 可以集成GitHub Pages支持的Jekyll，或者链接到外部博客平台。

## 📄 许可证

MIT License - 可自由使用、修改和分发。

## 🤝 贡献

欢迎提交Issue和Pull Request来改进这个项目！

## 📞 联系作者

如果你在使用过程中遇到问题，可以通过以下方式联系：

- 📧 Email: your.email@example.com
- 🐙 GitHub: [yourusername](https://github.com/yourusername)
- 💼 LinkedIn: [your-profile](https://linkedin.com/in/your-profile)

---

⭐ 如果这个项目对你有帮助，请给个Star支持一下！ 