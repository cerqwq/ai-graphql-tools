# 🔷 AI GraphQL Tools

AI GraphQL工具，支持Schema设计、查询优化、订阅。

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-blue?logo=python" />
  <img src="https://img.shields.io/badge/OpenAI-API-green?logo=openai" />
  <img src="https://img.shields.io/badge/License-MIT-yellow" />
</p>

## ✨ 特性

- 🏗️ GraphQL Schema设计
- 💻 Resolver生成
- ⚡ 查询优化
- 📡 订阅生成
- 📦 Fragment生成
- 🚪 GraphQL网关设计

## 🚀 快速开始

```bash
pip install openai

python tools.py
```

## 📖 使用

```python
from ai_graphql_tools import create_tools

tools = create_tools()

# Schema设计
schema = tools.design_graphql_schema("博客系统", ["用户", "文章", "评论"])

# Resolver生成
resolvers = tools.generate_resolvers(schema, "python")

# 查询优化
optimized = tools.optimize_query(query, schema)

# 订阅生成
subscriptions = tools.generate_subscriptions(["新消息", "新评论"])

# Fragment生成
fragments = tools.generate_fragments(["用户", "文章"])

# GraphQL网关
gateway = tools.design_graphql_gateway(["用户服务", "内容服务"])
```

## 📁 项目结构

```
ai-graphql-tools/
├── tools.py       # GraphQL工具核心
└── README.md
```

## 📄 许可证

MIT License
