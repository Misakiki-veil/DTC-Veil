# Merchandising Decision Rules v1

Purpose: internal operating rules for a lean bridal veil DTC brand. This is not a study note. It is the decision logic Codex should use when asked to plan inventory, review SKU performance, recommend reorders, or design the future merchandise management system.

Source base reviewed:

- James Clark, *Fashion Merchandising: Principles and Practice*, 2nd edition: buyer/merchandiser roles, research and analysis, budgeting, open-to-buy, range planning, sizing/deliveries/allocation, e-commerce merchandising, supply chain.
- James Clark, 2015 edition: overlapping first-edition structure and terminology.
- Dimitris Koumbis, *Fashion Retailing: From Managing to Merchandising*: retail organization, consumer markets, store/merchandise controls, operational framing.
- *Introduction to Fashion Marketing*: consumer fashion marketing, segmentation, diffusion, product life cycle, consumer decision making, business buying behavior, pricing.

Working assumption: the brand is not fast fashion. It is a bridal veil and bridal accessories DTC brand with low SKU count, high trust requirement, slow purchase frequency, one-month replenishment lead time including logistics, and early-stage cash constraints.

## 1. Core Principle

Merchandising is the financial management of a product range.

For this brand, every product decision must consider:

- Product role
- Customer demand
- Search/content value
- Gross margin
- Inventory depth
- Lead time
- Cash availability
- Stockout risk
- Exit risk
- Brand value

Do not make SKU decisions from aesthetics alone.

## 2. Product Role System

Every SKU must have a primary role. A SKU without a role should not enter the launch range.

Allowed roles:

| Role | Purpose | Typical Decision Logic |
|---|---|---|
| Traffic Driver | Brings high-intent search/social visitors | Protect stock, improve SEO/PDP, keep available |
| Volume Core | Expected to sell consistently | Highest reorder priority once validated |
| Margin Builder | Raises AOV and gross profit | Reorder only if conversion/margin justify inventory cash |
| SEO Door | Captures specific keyword/category demand | Keep small but visible; improve landing pages |
| Content Hook | Creates social/Pinterest/creator attention | Judge with content + traffic metrics, not sales alone |
| Brand Visual | Establishes aesthetic authority | Do not evaluate with normal sell-through rules |
| Test SKU | Low-confidence demand test | Small buy, strict review window |
| Exit SKU | Product to clear or discontinue | No reorder unless new evidence appears |

Initial launch mapping:

| SKU | Role |
|---|---|
| Simple Cathedral Veil | Traffic Driver / Volume Core |
| Pearl Scatter Cathedral Veil | Volume Core / Margin Builder |
| Affordable Lace Mantilla Veil | SEO Door / Support |
| Premium Lace Cathedral Veil | Margin Builder / Price Anchor |
| Satin Edge Mid-Length Veil | Support / City Hall Door |
| Pearl Puff Short Veil | Content Hook / Second Look Test |
| 3D Floral Long Veil | Brand Visual |
| Ruffled Visual Veil | Brand Visual |

## 3. SKU Lifecycle Status

Each SKU must have one current lifecycle status.

Allowed statuses:

- Concept
- Sample
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

Status rules:

- New sellable launch SKUs start as `Launch Test`.
- Editorial samples start as `Editorial Only`.
- A SKU can become `Core` only after real sales and conversion support it.
- A SKU with poor sell-through but meaningful traffic becomes `Improve PDP`, not immediate exit.
- A SKU with strong conversion but low traffic becomes `Push Traffic`.
- A SKU with weak traffic, weak conversion, weak content response, and no strategic role becomes `Exit`.

## 4. Initial Buy Rules

Initial buy is not a bet on full-year demand. It is a controlled test to buy information.

Initial buy should answer:

- Which SKU gets traffic?
- Which SKU converts?
- Which SKU raises AOV?
- Which SKU generates content response?
- Which SKU deserves reorder capital?
- Which SKU should be paused or reworked?

Current launch rule:

```text
Lean formal launch:
50-60 sellable units
+ 8-10 sample / shoot / creator / replacement buffer
= about 60-70 total units
```

This is acceptable because the current Base model projects:

```text
M1-M3 units: 33
M1-M4 units: 59
```

If starting sellable stock is below 50 units, classify the launch as `Validation Drop`, not full launch.

Suggested 50-unit sellable split:

| SKU | Units |
|---|---:|
| Simple Cathedral Veil | 16 |
| Pearl Scatter Cathedral Veil | 12 |
| Affordable Lace Mantilla Veil | 7 |
| Premium Lace Cathedral Veil | 5 |
| Satin Edge Mid-Length Veil | 5 |
| Pearl Puff Short Veil | 5 |

For a 60-unit sellable split:

| SKU | Units |
|---|---:|
| Simple Cathedral Veil | 19 |
| Pearl Scatter Cathedral Veil | 14 |
| Affordable Lace Mantilla Veil | 8 |
| Premium Lace Cathedral Veil | 6 |
| Satin Edge Mid-Length Veil | 6 |
| Pearl Puff Short Veil | 7 |

## 5. True Sellable Inventory

Do not confuse total inventory with sellable inventory.

```text
True sellable inventory =
total units on hand
- shoot samples
- creator/PR allocated samples
- QC hold
- replacement buffer
- editorial-only samples
```

All replenishment decisions must use true sellable inventory.

## 6. Lead Time Rule

The brand's practical replenishment lead time is one month including:

- Reorder decision
- Supplier confirmation
- Production
- QC
- Packing
- Logistics
- Receipt
- Stock update

Customer shipping promise and replenishment lead time are not the same.

For inventory planning:

```text
Lead time = 4 weeks
```

unless updated by actual supplier performance.

## 7. Reorder Point

Reorder point must be based on whether inventory can survive until the next stock arrives.

Formula:

```text
Reorder point =
expected units sold during lead time
+ safety stock
```

For a four-week lead time:

```text
Reorder point =
4-week expected demand
+ safety stock
```

Safety stock guideline:

| SKU Type | Safety Stock |
|---|---:|
| Core / Traffic Driver | 2-4 weeks of average demand |
| Support / SEO Door | 1-2 weeks of average demand |
| Test SKU | 0-1 week of average demand |
| Editorial Only | No reorder point |

For early launch with low data:

- Simple Cathedral: reorder consideration begins below 10-14 sellable units.
- Pearl Scatter: reorder consideration begins below 7-10 sellable units.
- Mantilla: reorder consideration begins below 4-5 sellable units.
- Premium Lace: reorder only after proof; do not auto-reorder.
- Satin Edge: reorder consideration below 3-4 units if conversion is healthy.
- Pearl Puff: reorder only if sales or content data justify it.

## 8. Reorder Quantity

Reorder quantity must be constrained by demand and cash.

Formula:

```text
Suggested reorder quantity =
expected demand over next planning window
+ safety stock
- true sellable inventory
- incoming inventory
```

Then apply cash cap:

```text
final reorder quantity =
min(suggested quantity, quantity affordable within open-to-buy)
```

Default planning window:

- Core SKUs: 6-8 weeks
- Support SKUs: 4-6 weeks
- Test SKUs: 2-4 weeks
- Editorial SKUs: no automatic reorder

## 9. Open-to-Buy Cash Rule

Open-to-buy is the cash still allowed for inventory after protecting operating runway.

For this brand:

```text
Open-to-buy cash =
available cash
- next 60 days fixed/operating expenses
- committed marketing/content spend
- emergency buffer
- already committed inventory purchases
```

No reorder recommendation is valid unless it passes open-to-buy.

If open-to-buy is limited, prioritize in this order:

1. Core SKU at stockout risk
2. High-conversion SKU with strong sell-through
3. High-margin SKU with proven demand
4. SEO Door with consistent traffic and acceptable conversion
5. Content Hook only if content is generating qualified traffic or sales
6. Test SKU
7. Editorial SKU

## 10. Metrics Required for Weekly Review

Each SKU should be reviewed with both merchandise metrics and e-commerce metrics.

Merchandise metrics:

- Opening inventory
- Units sold
- Current sellable inventory
- Incoming inventory
- Sell-through
- Weeks of supply
- Gross revenue
- Gross margin dollars
- Gross margin %
- Return/defect rate
- Reorder point
- Reorder recommendation

E-commerce metrics:

- Product sessions
- Product views
- Add-to-cart rate
- Conversion rate
- Revenue per product session
- Traffic source
- Search terms if available
- Content-driven sessions
- Review count and rating
- PDP exit rate if available

Do not judge a product only by units sold.

## 11. Sell-Through Rules

Formula:

```text
Sell-through =
units sold / initial sellable units
```

Launch-stage thresholds:

| Sell-Through | Meaning | Action |
|---:|---|---|
| 0-15% after 30 days | Weak early movement | Check traffic before judging product |
| 15-30% after 30 days | Slow but not dead | Improve content/PDP if role matters |
| 30-50% after 30-45 days | Healthy for launch | Watch reorder point |
| 50-70% before reorder lead time | Strong | Prepare reorder if conversion/margin OK |
| 70%+ quickly | Potential winner or underbought | Reorder decision required |

For bridal, do not punish slower movement as aggressively as fast fashion. Use traffic and conversion context.

## 12. Traffic x Conversion Decision Matrix

Use this for product diagnosis:

| Traffic | Conversion | Interpretation | Action |
|---|---|---|---|
| High | High | Winner | Protect stock, reorder, add content |
| High | Low | Demand exists but product/PDP is not closing | Improve images, copy, price, trust, color guidance |
| Low | High | Hidden winner | Push SEO/internal links/content/ads |
| Low | Low | Weak SKU or weak exposure | If no strategic role, pause or exit |

For content hooks:

- High content engagement + low sales = content asset, not necessarily core SKU.
- If content engagement does not create product sessions, improve CTA/path before reordering.

## 13. Margin Rules

A SKU must be reviewed by contribution dollars, not only revenue.

For each SKU:

```text
Contribution =
realized price
- unit cost
- payment/platform fee
- loss/return reserve
- shipping subsidy if not included
```

Decision guidance:

- Low margin + high volume can be acceptable only for traffic-driver/core role.
- High margin + low volume can be acceptable as price anchor or premium support.
- Low margin + low conversion is a bad SKU unless it has strong strategic value.
- High revenue does not justify reorder if margin and return risk are poor.

## 14. Markdown and Exit Rules

Bridal brands should avoid constant public markdowns because trust and premium perception matter.

Preferred clearance methods:

1. Private sample sale
2. Bundle
3. Gift with purchase
4. Creator seeding
5. Archive/outlet section
6. Controlled markdown

Exit candidate rules:

- 60 days: sell-through below 20% and low traffic -> improve exposure or pause.
- 90 days: sell-through below 30% and low conversion -> do not reorder.
- 120 days: sell-through below 40% with no strategic role -> clear/exit.

Do not exit editorial samples based on sell-through.

## 15. Range Planning Rules

Before adding a SKU, check whether it fills a real range gap.

Valid reasons to add:

- Distinct search demand
- Distinct bride occasion
- Distinct price band
- Distinct material/style not already represented
- Validated customer request
- Validated content angle
- Bundle/upsell logic

Invalid reasons:

- It is pretty
- A competitor has it
- It might sell
- It makes the collection look bigger
- A supplier can make it cheaply

Range balance checks:

- Do we have too many pearl SKUs?
- Do we have too many high-price SKUs?
- Do we have enough entry trust?
- Do we have enough visual distinction between products?
- Does every SKU have a clear page/title/search angle?
- Can we support each SKU with photos, PDP education, and inventory?

## 16. Product Lifecycle Rules

Use lifecycle status changes rather than emotional decisions.

Upgrade rules:

- `Launch Test` -> `Active`: at least 30 days live, real traffic, at least some conversion signal.
- `Active` -> `Core`: strong sell-through, acceptable conversion, acceptable margin, recurring demand.
- `Active` -> `Reorder Watch`: stock risk within next 4-6 weeks.
- `Reorder Watch` -> `Reorder Now`: below reorder point and open-to-buy available.

Downgrade rules:

- `Active` -> `Improve PDP`: traffic exists but conversion is weak.
- `Active` -> `Push Traffic`: conversion is good but traffic is weak.
- `Launch Test` -> `Pause`: weak traffic and weak conversion after review period.
- `Pause` -> `Exit`: no recovery after PDP/content/traffic test.

## 17. E-Commerce Merchandising Rules

An online product page is a store fixture. It must sell and educate.

For every core or support SKU, PDP must answer:

- What type of veil is this?
- What dress does it work with?
- What length is it?
- What color is it?
- What material/hand feel should the bride expect?
- Does it photograph well?
- What does it look like close up?
- What is the shipping timeline?
- What happens if it does not work?
- How does it compare with similar SKUs?

If product sessions are high and conversion is low, fix PDP before assuming demand is weak.

## 18. Customer Decision Rules

Fashion marketing source logic: customers do not only buy product utility; they buy identity, confidence, social meaning, and risk reduction.

Bridal veil translation:

The bride is not only asking:

> Do I like this veil?

She is asking:

- Will this match my dress?
- Will it look expensive in photos?
- Will it feel cheap?
- Is the color right?
- Is the length too formal?
- Will I regret not wearing a veil?
- Can I trust this brand?
- Will it arrive on time?

Merchandising must therefore treat education, reviews, styling, and delivery promise as part of SKU performance.

## 19. Pricing Rules

Price should not be cost-plus only.

Use three lenses:

1. Cost and margin floor
2. Competitor and market reference
3. Customer value perception

For each SKU:

```text
Minimum viable price =
unit cost / target variable gross margin
```

But final price must also consider:

- Category anchor
- Product role
- Visual quality
- Search intent
- Similar competitor prices
- Discount tolerance
- Bundle potential

Entry products can have lower margin if they create trust and volume. Premium products must justify price with page quality, materials, styling, and brand context.

## 20. Supply Chain Rules

Use a hybrid supply chain:

- Core basics: planned replenishment
- Test/content SKUs: small-batch responsive buying
- Editorial samples: sample-only unless demand emerges

Do not treat every SKU as a fast-fashion trend product.

Do not treat every SKU as a slow wholesale bridal product either.

Best operating model:

```text
Small launch inventory
+ weekly SKU review
+ one-month reorder planning
+ cash-capped replenishment
+ strict SKU lifecycle status
```

## 21. Weekly Merch Review Output

Every weekly review should produce one action per SKU:

- Reorder now
- Watch
- Improve PDP
- Push traffic
- Hold
- Pause
- Exit
- Editorial only / no action

Recommended weekly table columns:

- SKU
- Role
- Status
- Sellable inventory
- Incoming inventory
- Units sold last 7 days
- Units sold last 30 days
- Sell-through
- Weeks of supply
- Product sessions
- Conversion rate
- Add-to-cart rate
- Gross margin %
- Return/issue flag
- Reorder point
- Suggested reorder qty
- Cash required
- Decision
- Reason

## 22. Automation Rules for Future System

The future system should automate calculation, not judgment blindly.

Automate:

- Sell-through
- Weeks of supply
- Reorder point
- Stockout date
- Open-to-buy
- Suggested reorder quantity
- SKU ranking
- Low-stock alerts
- PDP problem flags
- Traffic problem flags

Keep human/brand judgment for:

- SKU role
- Brand visual value
- Product taste
- Editorial importance
- Whether to launch a new SKU
- Whether a slow SKU deserves another content test

## 23. Current Operating Recommendation

For the current launch:

- Use 50-60 sellable units as lean initial buy.
- Keep 8-10 units/sample equivalents outside sellable inventory.
- Treat Simple Cathedral and Pearl Scatter as protected early core candidates.
- Treat Mantilla and Satin Edge as support/SEO tests.
- Treat Premium Lace as margin/anchor test.
- Treat Pearl Puff as content/second-look test.
- Treat 3D Floral and Ruffled as editorial-only until demand proves otherwise.
- Begin weekly merch review immediately after launch.
- Prepare reorder logic by M2, not after stockout.

## 24. Non-Negotiables

- Never reorder from aesthetics alone.
- Never let open-to-buy be ignored.
- Never judge editorial SKUs by normal sales metrics.
- Never judge low sales without checking traffic.
- Never judge high traffic without checking conversion.
- Never treat total inventory as sellable inventory.
- Never wait until sellout to reorder a core SKU with four-week lead time.
- Never add a SKU unless it fills a defined range role.

