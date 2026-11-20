# Bodie《投资学》中文 Skill

用 Bodie、Kane、Marcus 的《Investments》第 13 版做投资学演算与案例评审。给出一组收益、价格、现金流或组合约束，Skill 会选取对应方法，列出假设、推导、复核结果和原书章节。仓颉将七篇的代表任务编译为一个入口，支持按任务调用，也可以从任一章开始学习。

## 安装到 Codex

在个人技能目录下首次安装可运行以下命令，随后新开会话。

```sh
git clone https://github.com/slevin17f/bodie-investments.git
mkdir -p ~/.agents/skills
cp -R bodie-investments/skills/bodie-investments ~/.agents/skills/
```

## 试用

> 用 $bodie-investments 复核一笔海外投资。我用美元记账，把 14,000 美元按 1.40 美元兑 1 英镑换汇，英镑资产赚了 10%，期末汇率为 1.20 美元兑 1 英镑。分别给我英镑收益、美元终值和美元收益率。

英镑资产从 10,000 增至 11,000，折回为 13,200 美元。美元收益率为 13,200 / 14,000 − 1 ≈ −5.71%。可以用增长因子 1.10 × (1.20 / 1.40) 独立复核。原书例 25.1 的文字给出 −4%，与其金额不一致。

其他入口包括比较两只基金的费用、复核债券久期、给欧式期权估值、评审超额收益证据、拟定案例的投资政策说明书。

[技能入口](skills/bodie-investments/SKILL.md) · [能力索引](skills/bodie-investments/references/capability-index.md) · [28 章阅读地图](skills/bodie-investments/references/overview.md) · [术语口径](skills/bodie-investments/references/glossary.md)

来源为 Zvi Bodie、Alex Kane、Alan J. Marcus，《Investments》，第 13 版，McGraw Hill，版权页 ©2024，ISBN 978-1-264-41266-2。仓库提供原创中文操作说明、来源定位与练习，按指定版次核对。
