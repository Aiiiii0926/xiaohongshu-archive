# 分类待看库

这是小红书记录整理后的私人存档，仓库为私有仓库，只有已授权的 GitHub 账号可以读取。

## 本机使用

直接打开 `index.html` 即可浏览分类、标题、原链接和推荐顺序。

## 在另一台设备上使用

1. 在这台设备安装 Git，并在 GitHub 登录同一个账号。
2. 克隆仓库：

   ```bash
   git clone https://github.com/Aiiiii0926/xiaohongshu-archive.git
   ```

3. 进入目录并打开 `index.html`。

也可以直接在 GitHub 私有仓库页面下载仓库为 ZIP，解压后打开 `index.html`。

## 更新内容

每次修改 `index.html`、`source-data.csv` 或其他文件后：

```bash
git add .
git commit -m "更新收藏库"
git push
```

然后在其他设备上执行 `git pull` 拉取最新内容。

## 阅读状态

「已看」和「稍后」状态保存在浏览器本地，不会自动同步。跨设备时需要先在当前浏览器的开发者工具中导出对应 `localStorage`，再在新设备导入。
