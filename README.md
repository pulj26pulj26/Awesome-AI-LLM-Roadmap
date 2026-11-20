# 🚀 AI 大模型应用开发学习路线 (LLM Dev Roadmap)

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

> 一条从零基础到模型优化的 AI 大模型应用开发开源学习路径：**4 个阶段、12 个模块、20 个高 Star 项目**。
> 本项目不仅提供项目清单，更附带了以过来人视角总结的**难度分级、必学建议与避坑指南**。
> *注：Star 数据采集于 2026-11-20，通过 GitHub 官方 API 实时获取。*

---

## 📖 目录 (Table of Contents)
- [🗺️ 核心学习路线图 (Roadmap)](#️-核心学习路线图-roadmap)
- [📚 第一阶段：零基础入门](#-第一阶段零基础入门)
- [🔍 第二阶段：RAG 开发](#-第二阶段rag-开发)
- [🤖 第三阶段：智能体与架构](#-第三阶段智能体与架构)
- [⚙️ 第四阶段：模型优化](#️-第四阶段模型优化)
- [🎯 学习成果自测 Checklist](#-学习成果自测-checklist)
- [🤝 如何贡献](#-如何贡献)

---

## 🗺️ 核心学习路线图 (Roadmap)

建议按以下依赖关系循序渐进，切勿跳跃式学习：

```mermaid
graph TD
    subgraph Phase1 [第一阶段 零基础入门]
        A1[Python 基础] --> A2[提示词工程]
        A2 --> A3[API 实战]
    end

    subgraph Phase2 [第二阶段 RAG开发]
        A3 --> B1[LangChain 核心]
        B1 --> B2[RAG 开源项目实战]
        B2 --> B3[知识库平台构建]
    end

    subgraph Phase3 [第三阶段 智能体与架构]
        B3 --> C1[LlamaIndex 进阶]
        B1 --> C2[Transformer 底层原理]
        C2 --> C1
        C1 --> C3[AI Agent 开发]
    end

    subgraph Phase4 [第四阶段 模型优化与部署]
        C2 --> D1[模型微调 Fine-tuning]
        D1 --> D2[模型量化与高效部署]
        C2 --> D3[多模态 CLIP 原理与实践]
    end

    style Phase1 fill:#e1f5fe,stroke:#01579b
    style Phase2 fill:#e8f5e9,stroke:#2e7d32
    style Phase3 fill:#fff3e0,stroke:#e65100
    style Phase4 fill:#fce4ec,stroke:#880e4f
```
