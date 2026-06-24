# Merchandising Source Coverage

This file records how the provided merchandising and fashion marketing textbooks were used to build `merchandising_decision_rules_v1.md`.

## Primary Source

### James Clark, Fashion Merchandising: Principles and Practice, 2nd Edition

Role in system: primary framework for merchandise management.

Chapters/sections reviewed:

- Buyer and merchandiser roles
- Research and analysis
- Budgeting
- Open-to-buy
- Range planning
- Sizing, deliveries, and allocation
- E-commerce and the merchandiser role
- Supply chain
- Glossary

Concepts extracted:

- Merchandising as a bridge between product, buying, and finance
- KPI-based planning
- Retail mathematics plus commercial interpretation
- OTB as buying control
- Range balance
- Option planning / width and depth logic
- Allocation and delivery timing
- Sell-through and stock productivity
- Online metrics: visits, conversion, basket, reviews, product views
- Supply chain models: push, pull, quick response, replenishment

How translated for bridal veil DTC:

- Reframed large-retail OTB into cash-capped reorder rules
- Reframed allocation into sellable vs sample/creator/editorial stock
- Reframed e-commerce merchandising into PDP + search + content + review metrics
- Reframed supply chain into one-month lead-time reorder planning

## Supporting Source

### James Clark, Fashion Merchandising: Principles and Practice, 2015 Edition

Role in system: terminology and structure validation.

Use:

- Confirmed that the 2021 edition preserves and updates the same core merchandising architecture.
- Used as backup for original concept structure around research, budgeting, OTB, range planning, deliveries/allocation, e-retailing, and supply chain.

## Supporting Source

### Dimitris Koumbis, Fashion Retailing: From Managing to Merchandising

Role in system: retail operating context.

Sections reviewed:

- Retailing basics
- Consumer markets
- Retail corporate offices
- Store management and merchandise controls

Concepts extracted:

- Retail is an operating system, not only product selection
- Consumer market definition and behavior matter before assortment planning
- Corporate retail functions divide accountability across product, operations, and marketing
- Merchandise controls and loss prevention are part of inventory discipline

How translated for bridal veil DTC:

- Reinforced need for clear SKU ownership, controls, and inventory visibility
- Reinforced that Shopify / spreadsheet / future system should support operating discipline, not just reporting
- Helped separate brand taste decisions from merchandise control decisions

## Supporting Source

### Introduction to Fashion Marketing

Role in system: consumer and pricing context.

Sections reviewed:

- Consumer fashion marketing
- Marketing research and segmentation
- Diffusion
- Product life cycle
- Consumer motivation and decision making
- Business buying behavior
- Price

Concepts extracted:

- Fashion purchase is identity-driven as well as functional
- Segmentation matters before assortment and messaging
- Product adoption/diffusion is uneven
- Products have lifecycle stages
- Consumer decision making includes risk, perception, motivation, and social meaning
- Price must reflect value perception, not only cost

How translated for bridal veil DTC:

- Added bride anxiety/trust logic into SKU performance interpretation
- Added SKU lifecycle states: test, active, core, pause, exit, editorial only
- Added pricing rules using cost floor + competitor reference + perceived value
- Added caution that content engagement and purchase intent are not the same signal

## Current Rule Output

Generated file:

- `merchandising_decision_rules_v1.md`

Status:

- v1 is usable as an execution rule base.
- It is not yet a software specification.
- Next step, when requested: translate v1 into a spreadsheet schema, Shopify metafields, or automated dashboard logic.

