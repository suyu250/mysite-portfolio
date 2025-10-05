# 个人作品集网站

一个展示个人视频作品的静态网站，支持视频播放和分类展示。

## 🚀 部署到 Vercel

### 方式一：通过 Git 仓库部署（推荐）

1. 将代码推送到 GitHub/GitLab/Bitbucket
2. 访问 [Vercel](https://vercel.com)
3. 点击 "Add New Project"
4. 导入你的 Git 仓库
5. 点击 "Deploy" - Vercel 会自动识别为静态网站并部署

### 方式二：通过 Vercel CLI 部署

```bash
# 安装 Vercel CLI
npm install -g vercel

# 在项目目录下运行
vercel

# 生产环境部署
vercel --prod
```

## 📁 项目结构

```
mysite/
├── index.html          # 主页面（入口文件）
├── mysitesource/       # 资源文件夹
│   ├── 背景.png
│   ├── 头像.jpg
│   ├── *.mp4          # 视频文件
│   └── 封面/          # 封面图片
├── vercel.json        # Vercel 配置文件
├── .gitignore         # Git 忽略文件
└── README.md          # 说明文档
```

## ✨ 功能特性

- 📱 响应式设计，支持移动端和桌面端
- 🎬 视频弹窗播放
- 🏷️ 作品分类展示（內娱、韩娱、欧美）
- 🎨 现代化 UI 设计
- ⚡ 静态部署，加载速度快

## 🛠️ 技术栈

- HTML5
- CSS3
- Vanilla JavaScript
- Vercel（部署平台）

## 📝 注意事项

1. 确保所有媒体文件都在 `mysitesource` 目录下
2. 视频文件较大时，建议使用 CDN 或压缩视频
3. Vercel 免费版有带宽限制，大量视频可能需要升级套餐

## 🌐 自定义域名

在 Vercel 项目设置中：
1. 进入 "Settings" → "Domains"
2. 添加你的自定义域名
3. 按照指示配置 DNS 记录

## 📄 许可证

MIT License

