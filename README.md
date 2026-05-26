# CRS Marketplace

CRS 插件的 Marketplace 配置仓库，支持 **Claude Code** 和 **Codex** 两个平台。

## 安装插件

### Claude Code 平台

```bash
# 1. 添加此 Marketplace
/plugin marketplace add zxc1213/crs-marketplace

# 2. 安装 CRS 插件
/plugin install crs
```

### Codex 平台

```bash
# 1. 添加此 Marketplace
codex plugin marketplace add zxc1213/crs-marketplace

# 2. 安装 CRS 插件
codex plugin install claude-req-sys-plugin
```

## 插件功能

CRS 是一个智能需求管理系统，提供：

- **多类型支持**：新功能、Bug 修复、技术问题、需求调整、重构
- **智能自动化**：集成 brainstorming、systematic-debugging 等 skills
- **统一入口**：智能路由到最优流程
- **科学优先级**：多维度评估优先级
- **质量门禁**：4个关键阶段自动检查
- **统一文档**：简化文档结构
- **向量知识图谱**：语义搜索相似需求

## 快速开始

安装完成后：

```bash
# 查看帮助
/crs:r --help

# 创建需求
/crs:r 添加用户登录功能

# 查看仪表板
/crs:r --dashboard
```

## 双平台说明

本仓库提供两个平台的marketplace配置：

- **Claude Code**: `marketplace.json` - 适用于 Claude Code 用户
- **Codex**: `marketplace-codex.json` - 适用于 Codex 用户

两个平台共享相同的插件源代码（[zxc1213/crs-plugin](https://github.com/zxc1213/crs-plugin)），功能完全一致。

## 更多信息

- [插件主页](https://github.com/zxc1213/crs-plugin)
- [完整文档](https://github.com/zxc1213/crs-plugin/blob/main/README.md)
- [安装指南](https://github.com/zxc1213/crs-plugin/blob/main/INSTALL.md)
