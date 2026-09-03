# 达哒商城官网 🦆

> 好物达哒，惊喜到家 —— 达哒商城品牌官方网站

## 🎨 设计特色

- **奶油黄主题** - 温暖柔和的奶油黄配色，营造软萌购物氛围
- **达哒鸭 IP** - 可爱的小鸭子品牌形象贯穿全站
- **快递包裹概念** - 胶带跑马灯、贴纸元素、开箱惊喜感
- **响应式设计** - 完美适配桌面、平板、手机

## 📁 项目结构

```
dada-mall-website/
├── index.html          # 主页面
├── css/
│   └── style.css       # 样式文件
├── js/
│   └── main.js         # 交互脚本
├── assets/
│   ├── logo.png        # 达哒鸭 Logo
│   └── qrcode.png      # 小程序码
└── README.md
```

## 🚀 快速开始

### 本地预览

直接用浏览器打开 `index.html` 即可预览。

或者使用本地服务器（推荐，避免相对路径问题）：

```bash
# Python 3
python3 -m http.server 8080

# Node.js
npx serve .
```

然后访问 `http://localhost:8080`

### 部署到 GitHub Pages

1. 在 GitHub 上创建新仓库，例如 `dada-mall-website`
2. 将本项目文件推送到仓库的 `main` 分支
3. 进入仓库 Settings → Pages
4. Source 选择 `Deploy from a branch`
5. Branch 选择 `main`，目录选择 `/ (root)`
6. 点击 Save，等几分钟后即可访问 `https://<username>.github.io/dada-mall-website/`

## 📝 页面模块

1. **导航栏** - 固定顶部，滚动时背景变化
2. **首屏 Hero** - 主视觉 + 小鸭子包裹 + 漂浮贴纸
3. **胶带跑马灯** - 服务承诺横向滚动展示
4. **达哒之旅** - 四步购物流程卡片
5. **好物橱窗** - 八大品类展示
6. **IP 故事** - 达哒鸭品牌故事
7. **用户口碑** - 评价展示
8. **CTA / 小程序码** - 快递面单风格的二维码区域
9. **页脚** - 品牌信息 + 导航链接

## 🎯 技术栈

- 纯 HTML + CSS + JavaScript
- 无任何外部依赖
- 原生 Intersection Observer 滚动动画
- CSS 变量主题系统

## 📄 License

© 2026 达哒商城 Dada Mall
