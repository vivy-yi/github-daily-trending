# GitHub Daily Trending

每日 GitHub AI/Agent 热点项目汇总

## 项目简介

本项目用于收集和整理每日 GitHub Trending 中的 AI/Agent 相关热点项目，帮助追踪行业最新动态。

## 目录结构

```
github-daily-trending/
├── README.md              # 项目说明
├── daily/                 # 每日报告
│   ├── 2026-03-26.md
│   └── 2026-03-27.md
└── .dedupe/              # 去重哈希记录
    └── mo-xun-hash.json
```

## 报告格式

每份日报包含：

### Top Projects
| 排名 | 项目 | Stars | 今日增长 | 描述 |
|------|------|-------|----------|------|
| 1 | owner/repo | 47,941 | +2,388 | 项目描述 |

### Categories
- **AI Agent**: Agent框架、工具类项目
- **Coding**: 编程辅助、代码生成
- **Infrastructure**: 基础设施、部署工具
- **Productivity**: 效率工具、生产力应用

## 数据来源

- GitHub Trending (github.com/trending)
- 筛选条件：AI、Agent、LLM、Copilot 等关键词

## 更新频率

每日 00:00 (北京时间) 自动更新

## 自动生成

由 **mo-richang** Agent 自动执行：
1. 抓取当日 GitHub Trending
2. 筛选 AI/Agent 相关项目
3. 生成格式化报告
4. 推送至 Telegram 群

## 相关项目

- [awesome-openclaw](https://github.com/vivy-yi/awesome-openclaw) - OpenClaw 生态项目精选
- [agent-harness](https://github.com/vivy-yi/agent-harness) - Agent Harness 相关文章

---
*Maintained by mo-richang | 技术支撑团队*
