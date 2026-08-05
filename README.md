# 新版人气值补量 · 推算模型

单页工具，用于模拟新版/旧版人气值补量规则对作者端单日人气的影响。

在线访问：推送并开启 GitHub Pages 后，地址为  
`https://<你的用户名>.github.io/<仓库名>/`

## 本地打开

直接双击或用浏览器打开 `index.html` 即可。

## 部署到 GitHub Pages

### 1. 在 GitHub 新建仓库

- 打开 https://github.com/new
- 仓库名例如：`popularity-boost-model`
- 选 **Public**
- 不要勾选「Add a README」（本地已有）

### 2. 推送代码

在项目目录执行（把 `YOUR_USER` 和 `YOUR_REPO` 换成你的）：

```bash
git remote add origin https://github.com/YOUR_USER/YOUR_REPO.git
git branch -M main
git push -u origin main
```

### 3. 开启 Pages

1. 仓库 → **Settings** → **Pages**
2. **Build and deployment** → Source 选 **GitHub Actions**
3. 推送后 Actions 会自动部署，约 1～2 分钟完成
4. Pages 设置页会显示访问地址

## 说明

- 依赖 Chart.js CDN，需联网使用
- 所有跑数在浏览器本地完成，不上传数据
