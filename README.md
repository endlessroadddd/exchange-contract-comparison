# KCEX 合约产品竞品分析

> 笔试任务：对比各交易所合约产品的优劣势、合约币对数量、主页重新排版

## 项目结构

```
├── README.md                              # 本文件
├── exchange-contract-comparison.md        # 完整竞品分析报告（Markdown）
├── data/
│   └── exchange-data.json                 # 原始数据（JSON格式，可程序化调用）
├── src/
│   └── charts.html                        # 数据可视化（Chart.js，浏览器打开即可）
└── assets/                                # 截图、素材等
```

## 内容说明

### 分析报告 (`exchange-contract-comparison.md`)
以 KCEX 视角撰写的竞品分析，包含：
1. KCEX 市场位置分析
2. 六家交易所全景对比（币对/费率/类型/杠杆/功能）
3. SWOT 分析
4. 用户增长策略建议（短/中/长期）
5. 数据图表建议
6. 核心结论

### 数据可视化 (`src/charts.html`)
浏览器直接打开，包含 7 张交互式图表：
- 永续合约数量柱状图
- 24h 交易量横向柱状图
- 手续费对比分组柱状图
- 最高杠杆柱状图
- 市场份额环形饼图
- 综合能力雷达图（KCEX vs Binance vs MEXC）
- 持仓量对比柱状图

### 原始数据 (`data/exchange-data.json`)
结构化 JSON 数据，包含六家交易所的完整对比数据，可直接用于后续分析或程序化处理。

## 对比交易所

| 交易所 | 核心特色 |
|--------|---------|
| Binance | 综合龙头，交易量第一 |
| OKX | 产品线最全，Web3 整合 |
| Bybit | 合约专业，深度好 |
| Bitget | 跟单功能行业领先 |
| MEXC | 币对最多（919个），杠杆最高（200x） |
| **KCEX** | **零手续费，增长快** |

## 数据来源

- CoinGecko Derivatives Rankings (2026.05)
- 各交易所官网
- Hyperliquid Docs
