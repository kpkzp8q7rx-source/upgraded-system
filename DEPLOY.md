# 部署说明

这是一个纯静态网页应用，可以直接部署到任意静态站点托管平台。

## 文件

- `index.html`：站点入口，自动跳转到主应用
- `itime_web_app.html`：主应用页面

## 推荐平台

1. GitHub Pages
2. Netlify
3. Vercel

## 最短部署方式

### GitHub Pages

1. 新建一个公开仓库
2. 上传 `index.html` 和 `itime_web_app.html`
3. 在仓库设置里打开 GitHub Pages
4. Pages 会给出一个公网链接

### Netlify

1. 把 `index.html` 和 `itime_web_app.html` 放到同一个目录
2. 登录 Netlify
3. 直接拖拽这个目录到部署区域
4. Netlify 会立刻生成公网链接

### Vercel

1. 用静态站点方式导入这个目录
2. 部署后即可获得公网链接

## 注意

- 这个应用是浏览器本地读取 Excel，不会把文件上传到服务器
- 只要托管平台支持静态文件，就能正常运行
