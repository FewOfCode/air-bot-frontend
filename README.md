# AirBot 前端

用于存放 `AirBot` 项目的 `monorepo` 仓库.

## 预先准备

[tauri 开发环境安装](https://tauri.app/zh-cn/v1/guides/getting-started/prerequisites)

## 快速开始

```shell
# 安装
pnpm install

# 启动指定 tauri 项目
pnpm --filter <project-name> tauri dev

# 打包指定 tauri 项目
pnpm --filter <project-name> tauri build

# 生成发布包版本信息
pnpm changeset

# 更新包版本并生成 changelog
pnpm changeset version

# 版本发布
pnpm changeset publish

# 代码检测
pnpm eslint

# 代码格式化
pnpm format

# 检测暂存代码
pnpm lint
```
