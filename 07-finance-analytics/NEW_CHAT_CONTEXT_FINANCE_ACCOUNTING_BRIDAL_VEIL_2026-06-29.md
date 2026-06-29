# New Chat Context: Finance & Accounting For DTC Bridal Veil Brand

Date: 2026-06-29

Use this file to start a new conversation focused only on finance, accounting, bookkeeping, startup costs, cash flow, tax/admin finance, financial model maintenance, inventory cash, and reconciliation for the DTC bridal veil project. Do not start from zero.

## 1. Project Context

We are building a modern DTC bridal veil and bridal accessories brand for the U.S. market.

The launch focus is bridal veils first, with possible future expansion into bridal accessories and bridal apparel / wedding dresses.

Current company/legal structure:

- LLC has been created / approved in New Jersey.
- Legal entity name: `YZ & Co Group LLC` for IRS purposes. The original LLC name included punctuation as `YZ & Co. Group`; IRS legal name field only allows `-` and `&`, so the period should be removed in IRS fields.
- EIN application is being handled through the IRS official website, not paid third-party services.
- DBA / NJ Alternate Business Name is likely needed because the founder wants customer-facing payment/collection to show the brand name rather than `YZ & Co Group LLC`.

Important legal/admin distinction:

- Legal entity: `YZ & Co Group LLC`
- Customer-facing brand / DBA: TBD
- In NJ, LLC DBA is usually handled as an `Alternate Business Name`.

## 2. Current Recommended Legal / Banking Sequence

If the founder wants payments to show the DBA/brand name, the recommended sequence is:

```text
1. LLC approved
2. EIN obtained
3. Apply for NJ Alternate Business Name / DBA
4. Open business bank account with LLC + DBA documentation
5. Set up Stripe / Shopify Payments using the DBA / statement descriptor where allowed
6. Complete NJ-REG / tax-employer registration if not already complete
```

NJ Alternate Business Name official route:

```text
NJ Business Charter Amendment Service
File an Amendment or an Alternate Business Name
```

Do not store sensitive info in GitHub:

- EIN
- SSN
- Home address
- Bank account numbers
- Credit card numbers
- LegalZoom order number
- Full receipts containing personal information

## 3. Current Finance Files In Repo

Finance folder:

```text
/Users/misakiki/Documents/Codex/DTC-Veil/07-finance-analytics/
```

Key files:

- `modern_bridal_veil_financial_model_v8_lean_launch_69_units_startup_fixed.xlsx`
- `modern_bridal_veil_financial_model_v7_calibrated_channel_mix.xlsx`
- `startup_cost_tracker.md`
- `active-projects/launch_finance_actions.md`
- `README.md`

Current source-of-truth model:

```text
modern_bridal_veil_financial_model_v8_lean_launch_69_units_startup_fixed.xlsx
```

This version reflects the lean launch inventory plan and repaired startup cost assumptions.

## 4. Current Launch Inventory / Model Assumptions

Current lean launch inventory plan:

```text
Total initial production/order quantity: 69 units
True sellable inventory: 59 units
Sample / buffer / creator / replacement: 8 units
Editorial visual samples: 2 units
```

Sellable split:

| SKU | Sellable Units |
|---|---:|
| Simple Cathedral Veil | 20 |
| Pearl Scatter Cathedral Veil | 14 |
| Affordable Lace Mantilla Veil | 8 |
| Premium Lace Cathedral Veil | 6 |
| Satin Edge Mid-Length Veil | 5 |
| Pearl Puff Short Veil | 6 |
| Total | 59 |

Editorial samples:

- 3D Floral Long Veil: 1
- Ruffled Visual Veil: 1

Known v8 model notes:

- Startup costs sheet was repaired.
- Base case after formula repair had approximately:
  - Revenue: about $218.6K
  - Orders: 1,142
  - Operating profit: about $99K
  - Lowest ending cash: about $1.68K in M2
  - First replenishment: M4, 26 units
  - Formula scan: 0 errors

Use these as context, but verify directly from the workbook when doing detailed model work.

## 5. Startup Cost Tracker

File:

```text
07-finance-analytics/startup_cost_tracker.md
```

Purpose:

Track clean startup-cost summaries in GitHub. Do not use GitHub for sensitive receipts.

Current tracker fields:

| Field | Meaning |
|---|---|
| Date | Expense date |
| Item | What was purchased / filed |
| Vendor | LegalZoom, State of NJ, IRS, supplier, etc. |
| Category | Finance category |
| Amount | Amount paid or pending |
| Status | Paid / Pending / Planned / Complete |
| Receipt Saved | Yes / No / Not needed / TBD |
| Notes | Clean non-sensitive notes |

Current placeholder rows:

- LLC formation filing: LegalZoom / State of NJ, amount TBD
- EIN application: IRS, $0
- DBA / Alternate Name filing: State of NJ, amount TBD, planned

GitHub should contain only clean summary rows. Actual receipts/invoices should be stored privately in Google Drive or local files.

## 6. Recommended Bookkeeping Setup

Simple operating stack:

```text
QuickBooks Online = official bookkeeping / financial records
Shopify = sales and orders
Stripe / Shopify Payments = payment processing
Google Drive or local private folder = receipts and invoices
Excel / Google Sheet = SKU-level inventory and merchandising tracker
GitHub = clean finance summaries, assumptions, decision logs
```

Recommended bookkeeping principle:

Separate company money and personal money as early as possible.

Use business bank account / business card for company expenses:

- Legal & filing
- Samples
- Inventory
- Packaging
- Shipping
- Content production
- Marketing
- Software
- Professional services

If founder pays with personal card, record it as founder reimbursement / owner contribution, not as an invisible mixed expense.

## 7. Finance Categories To Use

Use these categories consistently:

- Legal & Filing
- Professional Services
- Product Development / Samples
- Inventory / COGS
- Packaging
- Shipping / Logistics
- Content Production
- Marketing
- Software
- Bank / Payment Fees
- Office / Admin

Important distinction:

- Product samples used for development/content are not the same as sellable inventory.
- True sellable inventory matters for merchandising.
- Editorial-only samples are not normal sellable inventory.

## 8. Monthly Close Checklist

Each month:

- Reconcile bank account
- Reconcile credit card
- Save receipts privately
- Categorize expenses
- Match Shopify/Stripe deposits to sales
- Review startup costs vs model
- Review cash balance
- Review inventory cash tied up
- Review SKU-level gross margin if sales exist
- Update assumptions in the financial model only when needed

## 9. Open Finance Questions

The finance conversation should help answer:

1. What startup expenses have actually been paid?
2. What is the clean way to record LegalZoom / NJ / DBA / EIN costs?
3. What should go into QuickBooks vs GitHub vs Google Drive?
4. How should founder-paid expenses be recorded before the business bank account is ready?
5. When should QuickBooks be set up?
6. How should initial inventory be treated in the financial model?
7. How should product samples vs sellable inventory be categorized?
8. How should DBA / bank / Stripe / Shopify Payments display-name setup be documented?
9. How should actual costs reconcile against v8 model startup-cost assumptions?

## 10. Next Suggested Tasks For The New Finance Conversation

Start with:

1. Update `startup_cost_tracker.md` with actual paid LLC / LegalZoom / NJ costs.
2. Create a private receipt folder structure recommendation.
3. Create a QuickBooks category mapping for this bridal veil business.
4. Decide how to record founder-paid pre-bank-account expenses.
5. Create a simple monthly bookkeeping SOP.
6. Reconcile actual startup costs against v8 model assumptions.

## 11. Suggested Opening Prompt For New Chat

```text
这是 DTC bridal veil 项目的 Finance / Accounting 新对话。请先阅读我提供的 NEW_CHAT_CONTEXT_FINANCE_ACCOUNTING_BRIDAL_VEIL_2026-06-29.md，不要从 0 开始。

我们现在要做 07 Finance / Analytics 部门的工作：startup cost tracker、LLC/DBA/EIN/银行/Stripe/Shopify Payments 的财务记录、QuickBooks 分类、receipt 保存规则、以及把实际支出和 v8 financial model 对齐。

请先帮我检查目前财务前提，然后带我一步一步更新 startup_cost_tracker.md。
```

