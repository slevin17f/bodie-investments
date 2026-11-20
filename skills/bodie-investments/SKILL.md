---
name: bodie-investments
description: |
  按 Bodie、Kane、Marcus《Investments》第 13 版复核投资学算例与组合案例。适用于基金费用、风险配置、CAPM、事件研究、债券久期、股权估值、期权与期货、国际投资、业绩归因和投资政策说明书。
metadata:
  cangjie.generated-by: cangjie-tools v2.5.0
  cangjie.variant: single
  cangjie.bundle-id: bundle.bodie-investments
  cangjie.capability-count: 29
  cangjie.entrypoint-count: 1
---
# Investments（投资学，第 13 版） — 全书能力入口

## 触发与不触发

**适用**：与本书能力域相关的咨询与任务（见下方路由表的意图列）。
**不适用**：
- 全套教材题库、未经验证的实时行情与具体账户下单。

## 核心原则（常驻速览，概览类问题读到这里即可回答）

1. 题目求的是期望、实际业绩、所需回报，还是无套利价值？先标明日期、持有期、币种、复利及费用口径。
2. 从投资目标与约束选基准，再判断资产自身风险、它对整个组合的风险贡献以及残余风险。
3. 列出输入来源、计算步骤、带单位的答案和可独立复核的等式。区分教材例题、合成案例和当期市场观察。
4. 综合题分步处理，每一步根据下表调用相应卡片并将结果带入下一步。查原书章节用 references/overview.md。

## 能力路由（先读本表，按意图加载 1 张能力卡）

| 用户意图 | 先读 | 补读/备注 |
|---|---|---|
| 重建基准权重与拆股后的指数点位 | references/capabilities/a-index.md | references/capabilities/a-fund.md |
| 复核成交价格、融资融券账户与追保线 | references/capabilities/a-margin.md | references/capabilities/a-fund.md |
| 比较基金净值、收费方式与持有期净回报 | references/capabilities/a-fund.md | references/capabilities/a-returns.md |
| 把历史收益、通胀与尾部损失换到同一口径 | references/capabilities/a-returns.md | references/capabilities/c-performance-attribution.md |
| 按风险厌恶与借贷约束分配风险组合 | references/capabilities/a-allocation.md | references/capabilities/a-diversify.md |
| 用协方差求组合风险并区分最小方差与切点 | references/capabilities/a-diversify.md | references/capabilities/a-index-model.md |
| 用单指数回归分解市场与残差风险 | references/capabilities/a-index-model.md | references/capabilities/a-capm.md |
| 用 CAPM 必要收益检验给定预期收益 | references/capabilities/a-capm.md | references/capabilities/b-factor-test.md |
| 按因子暴露复制组合并核查 APT 定价差 | references/capabilities/a-apt.md | references/capabilities/b-factor-test.md |
| 用事件窗口检验公告后的异常收益 | references/capabilities/b-event-study.md | references/capabilities/b-behavioral-audit.md |
| 把行为解释转成可检验的假设 | references/capabilities/b-behavioral-audit.md | references/capabilities/b-event-study.md |
| 用两步回归审阅风险溢价证据 | references/capabilities/b-factor-test.md | references/capabilities/a-capm.md |
| 按票息时点审阅债券价格和收益率 | references/capabilities/b-bond-yield.md | references/capabilities/b-term-structure.md |
| 从零息折现因子还原远期利率 | references/capabilities/b-term-structure.md | references/capabilities/b-duration-match.md |
| 以久期、凸性和现值检查债务免疫 | references/capabilities/b-duration-match.md | references/capabilities/b-bond-yield.md |
| 把宏观冲击落实到行业利润 | references/capabilities/b-industry-shock.md | references/capabilities/b-roe-bridge.md |
| 匹配股利、自由现金流与估值假设 | references/capabilities/b-equity-model.md | references/capabilities/b-roe-bridge.md |
| 用五因素杜邦分解定位 ROE 差异 | references/capabilities/b-roe-bridge.md | references/capabilities/b-equity-model.md |
| 用到期现金流检查期权策略与看涨看跌平价 | references/capabilities/c-option-payoff.md | references/capabilities/black-scholes.md、references/capabilities/c-binomial-replication.md |
| 给无股息股票的欧式期权定价 | references/capabilities/black-scholes.md | references/capabilities/c-binomial-replication.md、references/capabilities/c-option-payoff.md |
| 用二叉树复制期权并核对节点价值 | references/capabilities/c-binomial-replication.md | references/capabilities/black-scholes.md、references/capabilities/c-option-payoff.md |
| 核算期货逐日盈亏与持有成本 | references/capabilities/c-futures-carry.md | references/capabilities/c-hedge-exposure.md |
| 按风险敞口核算期货套保及互换净额 | references/capabilities/c-hedge-exposure.md | references/capabilities/c-futures-carry.md |
| 按管理责任衡量业绩并核对归因 | references/capabilities/c-performance-attribution.md | references/capabilities/black-litterman.md、references/capabilities/c-treynor-black.md |
| 按本币重算海外收益与分散效果 | references/capabilities/c-currency-return.md | references/capabilities/c-performance-attribution.md |
| 按高水位和分配顺序还原另类基金净收益 | references/capabilities/c-alternative-fees.md | references/capabilities/c-performance-attribution.md |
| 用一个带置信度的观点更新均衡风险溢价 | references/capabilities/black-litterman.md | references/capabilities/c-treynor-black.md、references/capabilities/c-performance-attribution.md |
| 用预测精度和残差风险分配主动权重 | references/capabilities/c-treynor-black.md | references/capabilities/black-litterman.md、references/capabilities/c-performance-attribution.md |
| 把投资者目标和现金需求写成可复核的 IPS | references/capabilities/c-ips-design.md | references/capabilities/a-allocation.md |

**非能力类查询**：
- 书名/作者/章节/整书概览 → references/overview.md
- 术语解释 → references/glossary.md
- 决策规则速查（不需要原文依据时） → references/cheatsheet.md
- 完整意图与关键词索引（本表未覆盖的意图先查这里） → references/capability-index.md

## 加载规则

- 每次任务先读本文件，再按路由表加载 **1** 张能力卡；任务明确跨域时最多加载 2 张。
- 概览/书名类问题不加载能力卡，用「核心原则」与 overview.md 回答。
- 路由表与 capability-index.md 都无法命中的意图，明确告知超出本书范围，不要硬套。

## 边界与判停

- 缺少现金流时点、计价货币、基准或合约条款，且不同假设会改变答案时，列出条件结果并指出所需输入。
