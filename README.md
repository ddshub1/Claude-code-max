# Claude-code-max / Claude中转站月卡

# DDShub - 高性能 Claude API 接入中转 (GitHub/国内 直连版)

[![Status](https://img.shields.io/badge/Status-Beta-green.svg)](https://www.ddshub.cc)
[![Uptime](https://img.shields.io/badge/Uptime-99.9%25-brightgreen.svg)](https://www.ddshub.cc)
[![Model](https://img.shields.io/badge/Model-Claude--4.6--Opus-purple.svg)](https://www.ddshub.cc)
[![QQ群](https://img.shields.io/badge/QQ-QQ-red.svg)](https://qm.qq.com/q/ihcaDFVKPC)

**DDShub (呆呆兽中转)** 专为深度开发者与 AI 极客设计。我们通过独家号池负载技术，将官方 Claude Max 的性能转化为标准 API，解决国内开发者**网络不稳、并发受限、成本极高**等核心痛点。

---
## 网站：https://www.ddshub.cc/home
## 【DDShub QQ群】：https://qm.qq.com/q/ihcaDFVKPC
## 核心优势

- **极速直连：** 国内骨干网优化，流式输出（Stream）不掉线，响应丝滑。
- **开发适配：** 完美支持 **Claude Code**、**VScode**等全系工具。
- **独家号池：** 自有 Max 订阅号池，100% 完整模型能力，无阉割、无魔改。
- **极致成本：** 官方 1:1 计费倍率，实际使用成本仅为官方价格的 **2 折** 左右。

---

## 明星产品：全功率编程月卡 (Claude Code 专供)

针对重度编程场景（如大规模代码重构、文件扫描），我们提供高并发、高配额的专属包月方案。

| 特性指标               | 参数规格                                           |
| :--------------------- | :------------------------------------------------- |
| **官方计费倍率** | **1.0** (不虚标 Token)                       |
| **单日额度**     | **$60** (约 200万+ Token)                    |
| **单周额度**     | **$360**                                     |
| **并发限制**     | **5 路全开** (支持多线程高频调用)            |
| **模型版本**     | `claude-4-6-opus-latest` / `claude-4-6-sonnet` |
<img width="1905" height="919" alt="image" src="https://github.com/user-attachments/assets/40d973e8-7c8f-4a9a-8e7b-cf9437f1ac68" />

## 快速接入 (Quick Start)

以 **Claude Code** 终端为例，只需简单两步：

### 1. 设置环境变量

在您的终端中执行以下命令（建议写入 `~/.zshrc` 或 `~/.bashrc`）：

```bash
export ANTHROPIC_BASE_URL="https://www.ddshub.cc"
export ANTHROPIC_AUTH_TOKEN="你的API-KEY"
```

### 2. 启动客户端

```
# 安装/更新
npm install -g @anthropic-ai/claude-code

# 开启
claude
```

