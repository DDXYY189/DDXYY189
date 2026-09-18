# 发布说明

1. 在 GitHub 新建一个公开仓库，仓库名必须严格为 `DDXYY189`。
2. 不要勾选自动创建 README、`.gitignore` 或许可证，以免与本文件夹冲突。
3. 将本文件夹中的全部内容上传到该仓库根目录：`README.md`、`assets/` 和 `.github/` 都不能漏。
4. 推送到默认分支（通常为 `main`）后，个人主页会自动展示 README。
5. 打开仓库的 **Actions** 页面，执行一次 **Generate contribution snake** 工作流；它会新建 `output` 分支，约一分钟后贪吃蛇动画就会出现。

## 命令行推送（可选）

在此文件夹中打开终端后，依次运行：

```bash
git init
git add .
git commit -m "feat: add cyberpunk profile README"
git branch -M main
git remote add origin https://github.com/DDXYY189/DDXYY189.git
git push -u origin main
```

如果 Git 要求登录，请在浏览器中完成 GitHub 授权；不要把密码或个人令牌写进任何文件。

## 可继续个性化的位置

- 修改 `README.md` 中“身份、方向、信条”三行，让它更像你本人。
- 有新的后端项目后，把“Featured repositories”的链接替换为对应仓库。
- 如果你有 Bilibili、掘金、博客或邮箱，可再加一个社交入口区。
