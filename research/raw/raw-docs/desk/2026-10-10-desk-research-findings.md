---
title: "Desk research — Redesigning grocery delivery"
date: 2026-10-10
activity: desk-research
source: "web sources, see raw-docs/desk/competitors/sources.md"
author: "Simona Correale"
channel: web
method: desk research
tags: [desk-research, grocery-delivery, substitutions, order-receiving, delivery-windows, competitors, market, contradiction]
confidence: medium
grade: tertiary
status: complete
related: [index.md, brief.md, plan.md, raw/raw-docs/interview/2026-10-10-interview-script.md, notes/2026-10-10-interview-note-federica-franco-p1.md, raw/raw-docs/desk/competitors/2026-10-10-desk-research-competitor-evidence.md, raw/raw-docs/desk/competitors/2026-10-10-desk-research-sources.md]
---

# Desk research — Redesigning grocery delivery

Secondary evidence on the three moments named in the [brief](../../../brief.md): building the basket, handling substitutions, receiving the order. The desk research part of the [research plan](../../../plan.md).

Scope: online grocery delivery by supermarket chains in general. Findings about a single chain are labelled with its name.

## How to read this file

- Each finding has an ID, a source reference (S1, S2, ...) and a confidence level.
- **Market** says where the data comes from. Most of it is not Italian.
- Findings marked *to verify* were read in search summaries or press coverage and have not yet been checked against the original source.

## Summary

1. Substitutions are the best documented pain point of online grocery. They are frequent, often unsatisfying, and the interfaces for controlling them are hard to use.
2. Shoppers accept substitutions in principle but want control over specific items.
3. Evidence on delivery windows and on receiving the order is thin in this pass. It is a gap, not a sign that those moments work well.
4. Almost nothing found so far describes how Italian supermarket chains handle unavailable items. The substitution evidence comes from the UK and the US.

## Findings

### Context: the Italian market

| ID | Finding | Market | Source | Confidence |
|----|---------|--------|--------|------------|
| D1 | Online food and grocery was worth about 4.9 billion euros in 2025, up about 7% on the year before. | Italy | S1 | medium, *Evidenche verified by interview* | S13, S14 |
| D2 | In 2026 the category is reported to grow about 5 to 6%, in line with product e-commerce overall (about 42.6 billion euros). | Italy | S2, S3 | medium, *Evidenche verified by interview* |

### Context: Italian supermarket services

| ID | Finding | Market | Source | Confidence |
|----|---------|--------|--------|------------|
| D3 | Esselunga, as an example. The flow is: fill the basket on the site or app, then choose a delivery window. A Fìdaty card is required. | Italy | S4 | low, source may be dated |
| D4 | Esselunga: delivery windows are reported as Monday to Saturday 7:00 to 23:00 and Sunday 8:30 to 20:00. | Italy | S4 | low, source may be dated |
| D5 | Esselunga: besides home delivery there is pickup ("Clicca e Vai") and locker pickup in some stores. | Italy | S5 | low, *Evidenche verified by interview* |
| D20 | Two models coexist: chains that run their own online service, and marketplaces such as Everli, where a personal shopper buys in the store of a partner chain (Coop, Conad, Lidl and others are reported). | Italy | S11 | low, source may be dated |
| D21 | A consumer association survey scores online grocery services between 68 and 76 out of 100 across eight chains, a narrow range. Esselunga, Eurospin and Coop are at the top. | Italy | S12 | medium, *Evidenche verified by interview* |
| D22 | That score reflects site navigation, product availability and delivery reliability, so availability is already a criterion Italian shoppers are asked to judge. | Italy | S12 | medium, *Evidenche verified by interview* |

### Moment: handling substitutions

| ID | Finding | Market | Source | Confidence |
|----|---------|--------|--------|------------|
| D6 | In usability testing of grocery sites, 76% of participants had at least some difficulty with substitutions. It was among the hardest scenarios tested. | US | S6 | high |
| D7 | Choosing a substitution preference item by item was found tedious. The study suggests one global preference, or asking only about items at risk of being unavailable. | US | S6 | high |
| D8 | Asking only about at-risk items requires near real-time stock data. | US | S6 | medium |
| D9 | On one major service, the default was "best match" replacement, and refusing replacements meant changing a setting on each product. | US | S6 | medium, may be dated |
| D10 | 30 to 45% of shoppers are reported dissatisfied with the substitute they receive after an out-of-stock. | International | S7 | medium, *Evidenche verified by interview* |
| D11 | About 70% of consumers would allow substitutions when their first choice is unavailable, but about 90% have at least one item they will not compromise on. | International | S8 | low, vendor survey, *Evidenche verified by interview* |
| D12 | Substitutes are more readily accepted when they are the same brand, or a product the shopper has bought before. Personalised substitutes are accepted more often. | International | S7, S8 | medium, *Evidenche verified by interview* |
| D13 | Fewer than a third of surveyed retailers use purchase history to personalise substitutes. | International | S8 | low, *Evidenche verified by interview* |
| D14 | In a UK consumer survey, 19% (Ocado) and 26% (Tesco) of online shoppers had a substitution in their most recent shop. | UK | S9 | medium, 2024 data |
| D15 | Substitutes that ignore dietary needs occur, for example a meat product sent to a vegan customer. | UK | S9 | medium, anecdotal |

### Moment: receiving the order

| ID | Finding | Market | Source | Confidence |
|----|---------|--------|--------|------------|
| D16 | UK supermarkets in the survey let customers hand unwanted substitutes back to the driver for a refund. | UK | S9 | medium, 2024 data |
| D17 | Price rules for substitutes differ by retailer: some never charge more than the original item, others charge the price of the substitute. | UK | S9 | medium, 2024 data |
| D18 | Substitutions are communicated in different ways: by email or text before delivery, or by the driver at the door. | UK | S9 | medium, 2024 data |
| D19 | Retailers often miss the chance to tell shoppers about substitutions in advance. | UA | S10 | low, *Evidenche verified by interview* |


## Competitor practice

Moved to [evidence.md](competitors/2026-10-10-desk-research-competitor-evidence.md), with one file per competitor in [competitors/](competitors/).

## Implications for the design

- A substitution feature should ask less, not more: a global default plus exceptions for the items the shopper cares about (D7, D11).
- Purchase history is an underused basis for choosing substitutes (D12, D13).
- Dietary and household constraints must limit what can be substituted (D15).
- The time of notice matters: before delivery the shopper can still decide, at the door they can only accept or refuse (D16, D18, D19).

These are hypotheses to test in the [interviews](../interview/2026-10-10-interview-script.md), not conclusions.

## Signals

- Shared pain point, substitutions: `notes/2026-10-10-interview-note-federica-franco-p1.md` reports the same pattern as D11 and D12 from one shopper, who accepts most substitutes, protects a few items, and judges a substitute by its brand.
- Shared pain point, substitutions: `raw/raw-docs/interview/2026-10-10-interview-script.md` builds its hypotheses H1 to H4 on D7, D9, D11, D12, D18 and D19, and its synthesis reports how the first interview answers them.
- Shared pain point, stock accuracy: D8 (near real-time stock data) matches the fix P1 asks for in `notes/2026-10-10-interview-note-federica-franco-p1.md`, an app whose stock follows the store.
- Contradiction with `notes/2026-10-10-interview-note-federica-franco-p1.md` and `raw/raw-docs/interview/2026-10-10-interview-script.md`: the competitor table says Esselunga a Casa offers an upfront choice to accept substitutions or not; P1 says the tick box authorising substitutions was mandatory, with no way to refuse. Both versions are kept. The table gives no source; P1 is recalling a past version of the app.
- Contradiction with `notes/2026-10-10-interview-note-federica-franco-p1.md` and `raw/raw-docs/interview/2026-10-10-interview-script.md`: the competitor table says Esselunga a Casa controls freshness from a central warehouse; P1 says the order is picked from the nearest store. Both versions are kept.

## Gaps

- How Italian supermarket services handle unavailable items today: preference options, notice, refund.
- Whether substitution works differently when a marketplace shopper picks the order instead of the chain.
- Current delivery fees, minimum spend and window availability across Italian services.
- Research on choosing delivery windows and on missed or late deliveries.
- Research on freshness and on trust in someone else picking fresh produce.
- Research on basket building: recurring lists, reorder, time spent.
- Italian consumer data on any of the three moments.
- The 2026 value of the Italian online food and grocery market.

## Sources

Moved to [sources.md](competitors/2026-10-10-desk-research-sources.md).
