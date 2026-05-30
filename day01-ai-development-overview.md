# Day 1 - AI 应用开发概述

## 日期：2026-05-31

## 今天学到的内容

### 1. AI 应用开发工程师 vs 算法工程师

| | 算法工程师 | AI 应用开发工程师 |
|--|-----------|-----------------|
| 角色 | 造发动机的人 | 用发动机造汽车的人 |
| 技能 | 数学、PyTorch、论文 | Python、API、LangChain、RAG |
| 我的匹配 | 不匹配 | 匹配 |

### 2. AI 应用开发的本质

三件事：
1. **调 API** — 把请求发给 AI 模型，拿回结果
2. **编排流程** — 把多个步骤串起来
3. **处理数据** — 文档切片、向量化、检索

### 3. 我现有技能对应 AI

| 我已经会的 | AI 开发中对应的 |
|-----------|---------------|
| Java 调数据库（JDBC） | Python 调 AI API（requests） |
| 写存储过程处理数据 | 用 LangChain 编排 AI 流程 |
| Spring Boot 搭后端服务 | FastAPI 搭 AI 服务 |
| 托管行 CP API 接口对接 | Claude/OpenAI API 接口对接 |
| Oracle 存储和查询数据 | 向量数据库存储和检索数据 |

### 4. Git & GitHub 搭建

- Git 已安装并配置
- GitHub 账号已创建：https://github.com/zkcc
- 第一个仓库已创建：ai-learning-journey
- 学会了：git config, git clone, git add, git commit, git push

### 5. Git 提交流程

**命令行方式：**
```bash
# 进入项目目录
cd C:\SVN\AADE_Projects\Deliveries\文档\ai-learning-journey

# 添加要提交的文件（. 表示所有变更）
git add .

# 提交（写上说明）
git commit -m "提交说明"

# 推送到 GitHub
git push origin main
```

**VS Code 方式：**
1. 左侧边栏点第3个图标（源代码管理，分支图标）
2. 点文件右边的 `+` 号（暂存文件）
3. 在输入框写提交说明
4. 按 `Ctrl + Enter` 提交
5. 点"同步更改"推送到 GitHub

**Git 配置：**
```bash
# 配置用户名和邮箱（必须配置，否则提交会报错）
git config --global user.name "zhaokuo"
git config --global user.email "zhaokuo66324132@163.com"
```

**常见问题：**
- push 失败 → 网络问题（国内访问 GitHub 可能需要代理）
- 提交报错 → 检查 git config 是否配置了用户名和邮箱

## 面试高频问题

**问：你为什么从 Java 转 AI？**
答：AI 应用开发能用上我已有的编程和全流程能力，同时在一个增长中的市场有更好的机会。

**问：AI 应用开发工程师做什么？**
答：用 AI 模型（通过 API）构建应用——调 API、编排流程、处理数据。不是训练模型。
