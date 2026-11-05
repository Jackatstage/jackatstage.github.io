# jackatstage.github.io

Jack (Erfeng) Jiang 的个人作品集网站，由 GitHub Pages 托管：<https://jackatstage.github.io>

## 本地开发

需要 [Node.js](https://nodejs.org/) 18 或以上版本。

```bash
npm install      # 第一次运行时安装开发工具
npm run dev      # 启动本地服务器 http://localhost:3000 ，保存文件后浏览器自动刷新
```

## 常用命令

| 命令               | 作用                                              |
| ------------------ | ------------------------------------------------- |
| `npm run dev`      | 本地预览，带自动刷新（live reload）               |
| `npm run validate` | 检查 HTML 是否有错误                              |
| `npm run format`   | 用 Prettier 统一代码格式                          |
| `npm run check`    | 发布前检查（GitHub Actions 每次推送也会自动运行） |

## 项目结构

```
index.html            整个网站（HTML + CSS + JS 都在这一个文件里）
images/               图片资源（例如 og-image.png 分享预览图）
.nojekyll             让 GitHub Pages 直接发布原文件，不经过 Jekyll 处理
.github/workflows/    自动检查
```

## 发布

把改动合并到 `main` 分支并推送，GitHub Pages 会自动更新网站（通常一两分钟内生效）。
