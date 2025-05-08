# 📝 FastAPI 日志博客

一个基于FastAPI构建的轻量级博客系统，支持用户注册、登录及文章的完整增删改查(CRUD)操作。适合在实际应用场景中学习FastAPI、JWT认证和SQLAlchemy ORM技术。

---

## 🚀 核心功能

- ⚡ 基于FastAPI的高性能异步RESTful API
- 🧱 支持异步操作的SQLAlchemy数据库ORM
- 🔐 JWT令牌认证系统
- 📦 FastAPI依赖注入系统
- 🧩 可扩展的模块化项目结构
- 📄 交互式API文档（Swagger UI & Redoc）
- ✅ 使用pytest的单元测试
- 🔧 环境配置管理

---
                                                     <!--by 许嘉辉 -->

## 🧰 技术栈

- **Python 3.8+**
- **FastAPI** - Web框架
- **Uvicorn** - ASGI服务器
- **SQLAlchemy** - 异步ORM支持
- **Pydantic** - 数据验证
- **JWT** - JSON Web令牌认证
- **python-dotenv** - 环境变量管理
- **pytest** - 测试框架
- **alembic** (可选) - 数据库迁移工具

---
                                                    <!--by 林俞帆 -->

## 📁 项目结构

```text
fastapi_journalblog/
├── app/
│   ├── main.py              # 应用入口文件
│   ├── models/              # 数据库模型
│   ├── routers/             # API路由控制器
│   ├── schemas/             # Pydantic数据模型
│   ├── services/            # 业务逻辑层
│   └── dependencies.py      # 认证依赖项
├── tests/                   # 测试用例集
├── alembic/                 # 数据库迁移脚本（可选）
├── requirements.txt         # 依赖库清单
├── .env.example             # 环境变量示例
├── LICENSE
├── README.md
└── README.zh.md
                                                <!--by 杨樊 -->
