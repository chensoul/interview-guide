<div align="center">

**智能 AI 面试官平台** - 基于大语言模型的简历分析和模拟面试系统

[![Java](https://img.shields.io/badge/Java-21-orange?logo=openjdk)](https://openjdk.org/)
[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-4.0-green?logo=springboot)](https://spring.io/projects/spring-boot)
[![React](https://img.shields.io/badge/React-18.3-blue?logo=react)](https://react.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.6-blue?logo=typescript)](https://www.typescriptlang.org/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-pgvector-336791?logo=postgresql)](https://www.postgresql.org/)


</div>


---

## 项目介绍

InterviewGuide 是一个集成了简历分析、模拟面试和知识库管理的智能面试辅助平台。系统利用大语言模型（LLM）和向量数据库技术，为求职者和 HR 提供智能化的简历评估和面试练习服务。

该项目 forked from [Snailclimb/interview-guide](https://github.com/Snailclimb/interview-guide)，并做了以下优化：

- 新增JSON修复工具类处理LLM响应异常；优化ResumeGradingService增加JSON修复重试机制
- 添加Maven构建支持（mvnw、pom.xml）
- 更新依赖配置和文档说明
- 改进Docker Compose配置和.gitignore
- 升级ANTLR运行时版本至4.13.2，解决ATN反序列化版本不匹配问题
- 前端Docker构建阶段添加Brotli和Gzip压缩，提升静态资源加载性能
- 优化Nginx配置，支持预压缩静态文件并设置更优的缓存策略
- 为数据库连接池添加HikariCP详细配置，提升连接管理稳定性

## 许可证

AGPL-3.0 License（只要通过网络提供服务，就必须向用户公开修改后的源码）
