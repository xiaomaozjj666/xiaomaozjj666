# 👋 Hi there，我是 J

<p align="center">
  <img src="https://img.shields.io/badge/Full-Stack-React%20%2B%20Express-61DAFB" alt="Full-Stack" />
  <img src="https://img.shields.io/badge/AI%20Agent-LLM%20%2B%20MCP-4D6BFE" alt="AI Agent" />
  <img src="https://img.shields.io/badge/Quant-A%E8%82%A1%E5%9B%9E%E6%B5%8B-00B894" alt="Quant" />
  <img src="https://img.shields.io/badge/Python-3.11%2B-3776AB" alt="Python" />
  <img src="https://img.shields.io/badge/TypeScript-5-3178C6" alt="TypeScript" />
  <img src="https://img.shields.io/badge/C%2B%2B-11-00599C" alt="C++" />
</p>

热爱把 AI 变成真正可用的工具。这里是我 10 个公开项目中的精选，全部可独立运行：

## 🏗️ 项目矩阵

| 项目 | 一句话简介 | 亮点 |
|---|---|---|
| 🏦 [stock-research-system](https://github.com/xiaomaozjj666/stock-research-system) | A 股全栈智能投研平台 | 多专家协同研判 · 量化回测（DSR / CSCV / Walk-Forward）· 模拟盘闭环 |
| 📊 [data-analysis-agent](https://github.com/xiaomaozjj666/data-analysis-agent) | LLM 端到端数据分析工作台 | 上传数据 → 自动清洗 → 统计 → 可视化报告，Plan-and-Execute + ReAct |
| 🐛 [issue-agent](https://github.com/xiaomaozjj666/issue-agent) | GitHub Issue 根因分析智能体 | 有界工具循环 + 行级证据 + 修复补丁，默认只读 |
| 🕷️ [web-crawler](https://github.com/xiaomaozjj666/web-crawler) | Scrapling 风格隐身爬虫库 | TLS 指纹隐身 · 自适应选择器 · JS 逆向 Agent · 验证码识别 |
| 🛡️ [relay-audit](https://github.com/xiaomaozjj666/relay-audit) | OpenAI 兼容中转 API 质检工具 | 20+ 项安全/质量检测，一键 HTML 报告 |
| 🔢 [base-conversion](https://github.com/xiaomaozjj666/base-conversion) | 三语言进制转换 + 算法演示 | C++ / Python / JS 同函数对照，真实耗时实测图表 |
| 📚 [programming-exercises](https://github.com/xiaomaozjj666/programming-exercises) | 多语言编程入门练习 | C / C++ / JS / Python 示例，CI 自动编译校验 |
| 🧰 [code-practice](https://github.com/xiaomaozjj666/code-practice) | 多语言练习项目骨架 | 标准化目录结构，四种语言开箱即用 |

## 🧰 技术栈

```mermaid
flowchart LR
    subgraph AI["AI / Agent"]
        A1["LLM 应用（DeepSeek / OpenAI）"]
        A2["LangGraph · FastAPI · MCP"]
    end
    subgraph WEB["Web 全栈"]
        W1["React 19 · Vite · ECharts"]
        W2["Express 5 · TypeScript"]
    end
    subgraph DATA["数据 / 量化"]
        D1["pandas · numpy · 回测引擎"]
        D2["SQLite · 图表引擎"]
    end
    subgraph LANG["语言"]
        L1["Python · TypeScript · C++ · JavaScript"]
    end
    AI --> WEB
    AI --> DATA
    WEB --> LANG
    DATA --> LANG
```

## 📈 数据一览

| 指标 | 数值 |
|---|---|
| 公开仓库 | 10 个（含 8 个精选项目） |
| 语言覆盖 | Python · TypeScript · JavaScript · C++ · C · Java · Vue · C# |
| 测试习惯 | 单测 / E2E / CI 门禁全覆盖 |

---

> 💡 所有项目均提供一键启动（Windows `.bat` / `.cmd`）与 Docker 部署方式，欢迎 Star ⭐ 与 Issue 交流。
