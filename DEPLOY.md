# 发布到 GitHub Pages

## 最简单的方法

1. 在 GitHub 新建一个公开仓库，例如 `beidehui-poem-mvp`。
2. 上传本目录中的全部文件，保持 `assets` 目录结构不变。
3. 打开仓库 `Settings` → `Pages`。
4. `Build and deployment` 选择 `Deploy from a branch`。
5. Branch 选择 `main`，目录选择 `/ (root)`，保存。
6. 等待 GitHub 显示公开网址，再实际打开测试第 15 页图片与本地记录。

本项目使用相对路径，放在仓库根目录即可运行，无需构建命令。

## 更新

修改后重新提交 `index.html` 或对应资源。发布完成不等于功能验收完成，仍需按 `DELIVERY_CHECKLIST.md` 逐项测试。
