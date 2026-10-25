# Firekylin 使用文档

Firekylin 是一个简洁、快速且可扩展的 Node.js 博客系统。本文档面向 Firekylin 2.x，包含部署、日常使用、主题与插件扩展、AI 接入及迁移升级等内容。

## 开始使用

请根据运行环境选择部署方式：

| 部署方式 | 适用场景 |
| --- | --- |
| [快速部署](%E5%BF%AB%E9%80%9F%E5%BC%80%E5%A7%8B/%E5%AE%89%E8%A3%85%E9%83%A8%E7%BD%B2/%E5%BF%AB%E9%80%9F%E9%83%A8%E7%BD%B2.md) | 通过 Vercel 模板快速创建并上线站点 |
| [本地部署](%E5%BF%AB%E9%80%9F%E5%BC%80%E5%A7%8B/%E5%AE%89%E8%A3%85%E9%83%A8%E7%BD%B2/%E6%9C%AC%E5%9C%B0%E9%83%A8%E7%BD%B2.md) | 在本地或自己的服务器上创建、运行和开发站点 |
| [Docker 部署](%E5%BF%AB%E9%80%9F%E5%BC%80%E5%A7%8B/%E5%AE%89%E8%A3%85%E9%83%A8%E7%BD%B2/Docker%20%E9%83%A8%E7%BD%B2.md) | 使用官方 `firekylin/firekylin` 镜像和 SQLite 快速启动 |

部署完成后，可继续了解常用的站点管理功能：

- [文章](%E5%BF%AB%E9%80%9F%E5%BC%80%E5%A7%8B/%E5%9F%BA%E6%9C%AC%E6%93%8D%E4%BD%9C/%E6%96%87%E7%AB%A0.md)
- [页面](%E5%BF%AB%E9%80%9F%E5%BC%80%E5%A7%8B/%E5%9F%BA%E6%9C%AC%E6%93%8D%E4%BD%9C/%E9%A1%B5%E9%9D%A2.md)
- [评论](%E5%BF%AB%E9%80%9F%E5%BC%80%E5%A7%8B/%E5%9F%BA%E6%9C%AC%E6%93%8D%E4%BD%9C/%E8%AF%84%E8%AE%BA.md)
- [用户](%E5%BF%AB%E9%80%9F%E5%BC%80%E5%A7%8B/%E5%9F%BA%E6%9C%AC%E6%93%8D%E4%BD%9C/%E7%94%A8%E6%88%B7.md)
- [AI 接入](%E5%BF%AB%E9%80%9F%E5%BC%80%E5%A7%8B/%E5%9F%BA%E6%9C%AC%E6%93%8D%E4%BD%9C/AI%E6%8E%A5%E5%85%A5.md)

## 自定义站点

- [系统设置](%E5%BF%AB%E9%80%9F%E5%BC%80%E5%A7%8B/%E8%87%AA%E5%AE%9A%E4%B9%89/%E7%B3%BB%E7%BB%9F%E8%AE%BE%E7%BD%AE.md)：配置站点的基本信息和运行选项。
- [主题外观](%E5%BF%AB%E9%80%9F%E5%BC%80%E5%A7%8B/%E8%87%AA%E5%AE%9A%E4%B9%89/%E4%B8%BB%E9%A2%98%E5%A4%96%E8%A7%82.md)：选择、配置和管理站点主题。
- [主题列表](%E5%BF%AB%E9%80%9F%E5%BC%80%E5%A7%8B/%E8%87%AA%E5%AE%9A%E4%B9%89/%E4%B8%BB%E9%A2%98%E5%88%97%E8%A1%A8.md)：查看可用的 Firekylin 主题。
- [插件安装](%E5%BF%AB%E9%80%9F%E5%BC%80%E5%A7%8B/%E8%87%AA%E5%AE%9A%E4%B9%89/%E6%8F%92%E4%BB%B6%E5%AE%89%E8%A3%85.md)：通过插件扩展站点功能。

## 特色功能

- [丰富的 AI 能力](%E7%89%B9%E8%89%B2%E5%8A%9F%E8%83%BD/%E4%B8%B0%E5%AF%8C%E7%9A%84%20AI%20%E8%83%BD%E5%8A%9B.md)：统一管理 AI 服务商和模型，支持内容生成与外部 AI 客户端。
- [强大的插件扩展](%E7%89%B9%E8%89%B2%E5%8A%9F%E8%83%BD/%E5%BC%BA%E5%A4%A7%E7%9A%84%E6%8F%92%E4%BB%B6%E6%89%A9%E5%B1%95.md)：通过事件、Widget、模板扩展和路由增强站点。
- [开放的主题模板](%E7%89%B9%E8%89%B2%E5%8A%9F%E8%83%BD/%E5%BC%80%E6%94%BE%E7%9A%84%E4%B8%BB%E9%A2%98%E6%A8%A1%E6%9D%BF.md)：使用 Eta、Widget 和 Slots 构建自定义主题。

## 迁移与升级

- [从其他博客迁移](%E8%BF%81%E7%A7%BB%E6%8C%87%E5%8D%97/%E4%BB%8E%E5%85%B6%E4%BB%96%E5%8D%9A%E5%AE%A2%E8%BF%81%E7%A7%BB.md)
- [更新升级](%E8%BF%81%E7%A7%BB%E6%8C%87%E5%8D%97/Firekylin%20%E6%9B%B4%E6%96%B0%E5%8D%87%E7%BA%A7/%E6%9B%B4%E6%96%B0%E5%8D%87%E7%BA%A7.md)
- [1.x 升级至 2.x](%E8%BF%81%E7%A7%BB%E6%8C%87%E5%8D%97/Firekylin%20%E6%9B%B4%E6%96%B0%E5%8D%87%E7%BA%A7/1.x%E5%8D%87%E7%BA%A7%E8%87%B32.x.md)
- [0.x 升级至 1.x](%E8%BF%81%E7%A7%BB%E6%8C%87%E5%8D%97/Firekylin%20%E6%9B%B4%E6%96%B0%E5%8D%87%E7%BA%A7/0.x%E5%8D%87%E7%BA%A7%E8%87%B31.x.md)

> 升级或迁移前，请备份数据库、站点配置、主题、插件和上传文件，并先在副本中验证。

## 进阶指引

- [AI 管理](%E8%BF%9B%E9%98%B6%E6%8C%87%E5%BC%95/AI%E7%AE%A1%E7%90%86.md)：了解 Firekylin MCP 服务与 OAuth 授权流程。
- [主题开发](%E8%BF%9B%E9%98%B6%E6%8C%87%E5%BC%95/%E4%B8%BB%E9%A2%98%E5%BC%80%E5%8F%91.md)：开发 Eta 主题、文章字段和 Widget。
- [插件开发](%E8%BF%9B%E9%98%B6%E6%8C%87%E5%BC%95/%E6%8F%92%E4%BB%B6%E5%BC%80%E5%8F%91.md)：开发事件、模板扩展、路由和服务端能力。

## 其他资源

- [用户列表](%E5%85%B6%E4%BB%96/%E7%94%A8%E6%88%B7%E5%88%97%E8%A1%A8.md)
- [问题解答](%E5%85%B6%E4%BB%96/%E9%97%AE%E9%A2%98%E8%A7%A3%E7%AD%94.md)
- [贡献代码](%E5%85%B6%E4%BB%96/%E8%B4%A1%E7%8C%AE%E4%BB%A3%E7%A0%81.md)
