# Bridal Veil Merchandising Summary

这份文件是给当前 bridal veil 品牌用的 merchandising 总结。它不是教材笔记，而是我们后续做首批备货、补货、SKU review、Shopify 字段和自动化系统时要遵循的商品逻辑。

## 1. Merchandising 到底是什么

Merchandising 不是“选好看的货”。

对我们来说，它是：

```text
用商品组合、库存、现金和数据，决定卖什么、卖多少、什么时候补、什么时候停。
```

它要解决的问题：

- 哪些 SKU 值得首发？
- 每个 SKU 首批备多少？
- 哪些 SKU 该补货？
- 哪些 SKU 不该补货？
- 哪些 SKU 是品牌视觉，不该用普通销量标准评判？
- 库存会不会压死现金？
- 哪些 SKU 需要改页面、改图片、改内容，而不是直接淘汰？

## 2. 我们的商品系统核心原则

每个 SKU 必须有角色。

不能因为“好看”“供应商能做”“竞品有”就加入。每个商品都要回答：

```text
它在这个品牌里负责什么？
```

## 3. 当前首发 SKU 角色

| SKU | 商品角色 | 判断标准 |
|---|---|---|
| Simple Cathedral Veil | 主入口 / 走量核心 | 如果它卖不动，要认真检查产品页、价格、图片和流量 |
| Pearl Scatter Cathedral Veil | 升级走量 / 提高客单 | 如果转化好，应优先补货 |
| Affordable Lace Mantilla Veil | SEO 分类入口 / support | 不一定最大量，但要承接 mantilla 搜索需求 |
| Premium Lace Cathedral Veil | 高价锚点 / margin test | 不要求卖最多，补货要谨慎 |
| Satin Edge Mid-Length Veil | city hall / clean support | 小量验证，关注是否有明确人群 |
| Pearl Puff Short Veil | 内容款 / second look test | 不能只看点赞，要看有没有进站和转化 |
| 3D Floral Long Veil | Editorial visual | 首发不按销售 SKU 备货 |
| Ruffled Visual Veil | Editorial visual | 首发不按销售 SKU 备货 |

## 4. 首批备货逻辑

首批库存不是为了满足全年销量，而是为了买信息。

它要帮我们验证：

- 哪个 SKU 有人点？
- 哪个 SKU 有人买？
- 哪个 SKU 只是好看但不转化？
- 哪个 SKU 需要重拍图？
- 哪个 SKU 值得变成 core？
- 哪个 SKU 不值得补货？

当前推荐首批：

```text
总生产量：69 条
可售库存：59 条
sample / buffer：8 条
editorial visual：2 条
```

首批可售分配：

| SKU | 可售数量 |
|---|---:|
| Simple Cathedral Veil | 20 |
| Pearl Scatter Cathedral Veil | 14 |
| Affordable Lace Mantilla Veil | 8 |
| Premium Lace Cathedral Veil | 6 |
| Satin Edge Mid-Length Veil | 5 |
| Pearl Puff Short Veil | 6 |

非可售：

| 用途 | 数量 |
|---|---:|
| 主 SKU 拍摄 / creator / replacement buffer | 8 |
| 3D Floral Long Veil | 1 |
| Ruffled Visual Veil | 1 |

## 5. True Sellable Inventory

以后所有库存判断都必须看“真实可售库存”，不是总库存。

```text
真实可售库存 =
总库存
- 拍摄样品
- creator 样品
- replacement buffer
- QC hold
- editorial-only samples
```

如果不分清楚，会误以为库存够，实际可卖库存已经很薄。

## 6. 补货周期

当前按 **1 个月补货周期** 计算。

补货周期包括：

- 决定补货
- 供应商确认
- 生产
- QC
- 包装
- 物流
- 到货
- 入库

所以不能等卖完才补货。

## 7. Reorder Point 补货点

补货点不是“快卖完了”。

补货点是：

```text
库存是否能撑到下一批货到？
```

公式：

```text
补货点 = 补货周期内预计销量 + 安全库存
```

如果某 SKU 每周卖 3 条，补货周期 4 周：

```text
4 周 × 3 条 = 12 条
```

再加安全库存 3-4 条，库存低于 15-16 条就要考虑补货。

## 8. Sell-through 卖穿率

Sell-through 是最重要的早期指标之一。

公式：

```text
Sell-through = 已卖数量 ÷ 初始可售库存
```

例子：

```text
Simple Cathedral 首批 20 条，卖了 10 条
Sell-through = 50%
```

判断：

| Sell-through | 含义 | 动作 |
|---:|---|---|
| 0-15% | 很慢 | 先看有没有流量 |
| 15-30% | 偏慢 | 改页面/内容，不急着补 |
| 30-50% | 健康 | 开始观察补货风险 |
| 50-70% | 强 | 准备补货 |
| 70%+ | 很强 | 需要立即判断是否补货 |

## 9. 不能只看销量

每个 SKU 要看“流量 × 转化”。

| 流量 | 转化 | 说明 | 动作 |
|---|---|---|---|
| 高 | 高 | winner | 补货、加内容、保护库存 |
| 高 | 低 | 有兴趣但没买 | 改图、改页面、改价格/信任表达 |
| 低 | 高 | hidden winner | 给它更多内容和入口 |
| 低 | 低 | 弱 SKU 或曝光不足 | 如果没有战略角色，暂停或退出 |

## 10. Open-to-Buy 现金刹车

卖得好不等于可以无限补货。

补货前必须看 open-to-buy：

```text
Open-to-buy =
当前可用现金
- 未来 60 天运营费用
- 已计划营销/内容费用
- 应急缓冲
- 已承诺采购款
```

如果现金不够，补货优先级：

1. 核心款 / 主入口款，且有断货风险
2. 高转化、高 sell-through SKU
3. 高毛利且有真实需求 SKU
4. SEO support SKU
5. 内容款
6. 测试款
7. editorial visual

## 11. SKU Lifecycle

每个 SKU 要有状态，不要永远模糊地“在卖”。

状态可以是：

- Launch Test
- Active
- Core
- Reorder Watch
- Reorder Now
- Improve PDP
- Push Traffic
- Pause
- Exit
- Editorial Only

例子：

Simple Cathedral 如果转化好、sell-through 健康，可以从 `Launch Test` 升级为 `Core`。

Pearl Puff 如果内容互动高但没订单，可能是 `Content Hook / Improve CTA`，不是立刻补货。

3D Floral 和 Ruffled 初期是 `Editorial Only`，不该用普通销量标准淘汰。

## 12. 每周 Merch Review 要看什么

每周看一次 SKU 表，每个 SKU 输出一个动作。

必看指标：

- 当前可售库存
- 已售数量
- Sell-through
- Weeks of Supply
- Product sessions
- Conversion rate
- Add to cart rate
- Revenue
- Gross margin
- Return / complaint
- 是否低于 reorder point
- 是否有在途库存
- 是否有内容/SEO/creator 流量

每个 SKU 的动作只能是类似：

- Reorder now
- Watch
- Improve PDP
- Push traffic
- Hold
- Pause
- Exit
- Editorial only

## 13. Bridal Veil 特殊性

Bridal 不是快时尚，所以不能照搬快时尚逻辑。

特殊点：

- 决策周期更长
- 顾客更怕买错
- 信任和图片比普通服装更重要
- 低频高情绪价值
- 用户会提前几个月购买
- 发货可以不是 24-48 小时，但时间承诺必须清楚
- review、真实佩戴图、dress pairing 很重要

所以判断一个 SKU 时，不能只看“卖得快不快”，还要看：

- 它有没有降低选择焦虑？
- 它有没有帮助品牌建立信任？
- 它有没有承接搜索词？
- 它有没有提升视觉记忆点？

## 14. Shopify / 系统未来要支持什么

未来商品管理系统至少要能自动算：

- 可售库存
- 非可售库存
- sell-through
- weeks of supply
- reorder point
- suggested reorder qty
- open-to-buy
- stockout risk
- SKU status
- SKU role
- 每周建议动作

Shopify 可以做库存和订单底层，但不能完全替代 merchandising brain。

最终系统应该是：

```text
Shopify = 订单 / 库存事实来源
Spreadsheet or Airtable = 商品逻辑和人工判断
Future automation = 每周自动生成补货和 SKU review 建议
```

## 15. 当前执行结论

当前首批备货采用 lean launch：

```text
69 total units
59 sellable units
10 non-sellable units
```

这不是为了赌爆单，而是为了验证：

- Simple Cathedral 是否能成为核心入口
- Pearl Scatter 是否能成为升级走量款
- Mantilla 是否有 SEO/category demand
- Premium Lace 是否值得作为高价锚点
- Satin Edge 是否有 city hall / clean bride 需求
- Pearl Puff 是否能从内容款转化成真实订单

第一阶段最重要的目标：

```text
用最少库存，测出哪些 SKU 值得变成长期 core。
```

