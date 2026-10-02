# GitHub Pages 部署说明

## 自动部署已配置

项目已经配置了 GitHub Actions 自动部署，每次推送到 `master` 分支都会自动部署到 `gh-pages` 分支。

## 启用 GitHub Pages（首次配置）

由于权限限制，需要手动在 GitHub 仓库中启用 Pages：

1. 访问仓库设置页面：https://github.com/lyloou/floorplan-3d/settings/pages

2. 在 **Source** 部分：
   - 选择 **Deploy from a branch**
   - Branch 选择：`gh-pages`
   - Folder 选择：`/ (root)`

3. 点击 **Save** 保存设置

4. 等待几分钟后，访问部署地址：**https://lyloou.github.io/floorplan-3d/**

## 后续更新

启用后，每次推送到 `master` 分支都会自动触发部署，无需手动操作。

## 查看部署状态

- GitHub Actions 运行记录：https://github.com/lyloou/floorplan-3d/actions
- 部署的 `gh-pages` 分支：https://github.com/lyloou/floorplan-3d/tree/gh-pages
