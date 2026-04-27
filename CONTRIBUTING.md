# 贡献指南

感谢你对本项目的关注！

## 本项目的特殊性

本项目采用双层架构：公开的Skill文件 + 受保护的规则引擎。核心规则内容存储在私有仓库中，**不接受对规则内容的直接贡献**。但以下方面非常欢迎贡献：

## 你可以贡献什么

### 1. 使用反馈（最有价值）

在 [GitHub Discussions](https://github.com/abwoo/fan-emotion-analysis-skill/discussions) 中分享：
- 你在什么场景下使用了这个Skill
- 哪些建议对你有用，哪些不够精准
- 你希望增加什么类型的分析能力
- 你使用的AI工具和体验（Trae、Cursor等）

### 2. Bug报告

在 [Issues](https://github.com/abwoo/fan-emotion-analysis-skill/issues) 中提交：
- AI没有正确调用规则（回答明显偏离或过于笼统）
- 人物追踪系统出错（搞混了不同的人）
- 离线兜底逻辑有问题
- 指明你使用的AI工具和版本

### 3. 兼容性适配

不同AI工具对Skill的支持方式不同，欢迎贡献：
- 你在某个AI工具上的安装配置方法
- 某个AI工具的适配问题和解决方案
- 新的AI工具的安装教程

### 4. 文档改进

- 修复README中的错误或不清楚的地方
- 补充更详细的使用案例
- 改进安装说明
- 翻译文档为其他语言

## 你不能贡献什么

- 私有仓库中的规则内容（受保护，不接受外部修改）
- Skill文件中的路由规则和API调用逻辑（涉及架构安全）
- .access-token文件（涉及认证安全）

## 如何提交

1. Fork本仓库
2. 创建分支（`git checkout -b feature/your-feature`）
3. 提交修改
4. 发起Pull Request

对于简单的文档修复，也可以直接在GitHub上编辑提交。

## 安全原则

- 不要在Issue、PR或Discussion中粘贴规则原文内容
- 不要尝试逆向或公开规则文件的具体内容
- 不要分享或传播.access-token的内容
