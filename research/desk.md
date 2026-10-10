---
title: "Desk research — Redesigning grocery delivery"
date: 2026-10-10
activity: desk
source: "web sources, see Sources section"
author: "Simona Correale"
channel: web
method: desk research
tags: [desk-research, grocery-delivery, substitutions, delivery-windows, esselunga, market]
confidence: medium
grade: secondary
status: in-progress
related: [brief.md, plan.md, interview.md, index.md]
---

# Desk research — Redesigning grocery delivery

Secondary evidence on the three moments named in the [brief](brief.md): building the basket, handling substitutions, receiving the order. The desk research part of the [research plan](plan.md).

## How to read this file

- Each finding has an ID, a source reference (S1, S2, ...) and a confidence level.
- **Market** says where the data comes from. Most of it is not Italian.
- Findings marked *to verify* were read in search summaries or press coverage and have not yet been checked against the original source.

## Summary

1. Substitutions are the best documented pain point of online grocery. They are frequent, often unsatisfying, and the interfaces for controlling them are hard to use.
2. Shoppers accept substitutions in principle but want control over specific items.
3. Evidence on delivery windows and on receiving the order is thin in this pass. It is a gap, not a sign that those moments work well.
4. Almost nothing found so far describes how Esselunga handles unavailable items.

## Findings

### Context: the Italian market

| ID | Finding | Market | Source | Confidence |
|----|---------|--------|--------|------------|
| D1 | Online food and grocery was worth about 4.9 billion euros in 2025, up about 7% on the year before. | Italy | S1 | medium, *to verify* |
| D2 | In 2026 the category is reported to grow about 5 to 6%, in line with product e-commerce overall (about 42.6 billion euros). | Italy | S2, S3 | medium, *to verify* |

### Context: Esselunga's service

| ID | Finding | Market | Source | Confidence |
|----|---------|--------|--------|------------|
| D3 | The flow is: fill the basket on the site or app, then choose a delivery window. A Fìdaty card is required. | Italy | S4 | low, source may be dated |
| D4 | Delivery windows are reported as Monday to Saturday 7:00 to 23:00 and Sunday 8:30 to 20:00. | Italy | S4 | low, source may be dated |
| D5 | Besides home delivery there is pickup ("Clicca e Vai") and locker pickup in some stores. | Italy | S5 | low, *to verify* |

### Moment: handling substitutions

| ID | Finding | Market | Source | Confidence |
|----|---------|--------|--------|------------|
| D6 | In usability testing of grocery sites, 76% of participants had at least some difficulty with substitutions. It was among the hardest scenarios tested. | US | S6 | high |
| D7 | Choosing a substitution preference item by item was found tedious. The study suggests one global preference, or asking only about items at risk of being unavailable. | US | S6 | high |
| D8 | Asking only about at-risk items requires near real-time stock data. | US | S6 | medium |
| D9 | On one major service, the default was "best match" replacement, and refusing replacements meant changing a setting on each product. | US | S6 | medium, may be dated |
| D10 | 30 to 45% of shoppers are reported dissatisfied with the substitute they receive after an out-of-stock. | International | S7 | medium, *to verify* |
| D11 | About 70% of consumers would allow substitutions when their first choice is unavailable, but about 90% have at least one item they will not compromise on. | International | S8 | low, vendor survey, *to verify* |
| D12 | Substitutes are more readily accepted when they are the same brand, or a product the shopper has bought before. Personalised substitutes are accepted more often. | International | S7, S8 | medium, *to verify* |
| D13 | Fewer than a third of surveyed retailers use purchase history to personalise substitutes. | International | S8 | low, *to verify* |
| D14 | In a UK consumer survey, 19% (Ocado) and 26% (Tesco) of online shoppers had a substitution in their most recent shop. | UK | S9 | medium, 2024 data |
| D15 | Substitutes that ignore dietary needs occur, for example a meat product sent to a vegan customer. | UK | S9 | medium, anecdotal |

### Moment: receiving the order

| ID | Finding | Market | Source | Confidence |
|----|---------|--------|--------|------------|
| D16 | UK supermarkets in the survey let customers hand unwanted substitutes back to the driver for a refund. | UK | S9 | medium, 2024 data |
| D17 | Price rules for substitutes differ by retailer: some never charge more than the original item, others charge the price of the substitute. | UK | S9 | medium, 2024 data |
| D18 | Substitutions are communicated in different ways: by email or text before delivery, or by the driver at the door. | UK | S9 | medium, 2024 data |
| D19 | Retailers often miss the chance to tell shoppers about substitutions in advance. | US | S10 | low, *to verify* |

### Moment: building the basket

No specific findings yet. See Gaps.

## Competitor practice

To be completed on 2026-10-11: a first-hand walkthrough of Esselunga a Casa, and one more service from its help pages. Fill one row per service.

| Service | Basket building | Substitution control | Substitution notice | Delivery windows | At the door |
|---------|-----------------|----------------------|---------------------|------------------|-------------|
| Esselunga a Casa | | | | | |
| | | | | | |
| | | | | | |

## Implications for the design

- A substitution feature should ask less, not more: a global default plus exceptions for the items the shopper cares about (D7, D11).
- Purchase history is an underused basis for choosing substitutes (D12, D13).
- Dietary and household constraints must limit what can be substituted (D15).
- The time of notice matters: before delivery the shopper can still decide, at the door they can only accept or refuse (D16, D18, D19).

These are hypotheses to test in the [interviews](interview.md), not conclusions.

## Gaps

- How Esselunga a Casa handles unavailable items today: preference options, notice, refund.
- Current delivery fees, minimum spend and window availability for Esselunga.
- Research on choosing delivery windows and on missed or late deliveries.
- Research on freshness and on trust in someone else picking fresh produce.
- Research on basket building: recurring lists, reorder, time spent.
- Italian consumer data on any of the three moments.
- The 2026 value of the Italian online food and grocery market.

## Sources

| Ref | Source | Type |
|-----|--------|------|
| S1 | ItaliaOggi, "E-commerce, l'esperienza paga" — https://www.italiaoggi.it/marketing-e-media/marketing/e-commerce-lesperienza-paga-ac0bdv38 | Press, reporting Politecnico di Milano data |
| S2 | Pagamenti Digitali, "eCommerce B2c nel 2026" — https://www.pagamentidigitali.it/ecommerce/ecommerce-b2c-nel-2026-litalia-vale-426-mld/ | Press, reporting Politecnico di Milano data |
| S3 | Il Sole 24 Ore (English edition) — https://en.ilsole24ore.com/art/the-secrets-of-the-italian-ecom-how-much-it-is-worth-and-what-they-buy-online-AIo4Yb9C | Press |
| S4 | Businessonline, Esselunga online grocery coverage — https://www.businessonline.it/news/esselunga-la-spesa-online-su-internet-arriva-in-8-regioni-funzionamento-copertura-e-costi_n81799.html | Press |
| S5 | Scatti di Gusto, Esselunga lockers — https://www.scattidigusto.it/locker-esselunga-cosa-sono-e-come-si-ritira-la-spesa-fatta-da-casa | Press |
| S6 | Baymard Institute, grocery substitutions research article — https://baymard.com/research-articles/grocery-substitutions | UX research, usability testing |
| S7 | Hoang and Breugelmans, out-of-stock products and substitutions in online grocery retailing (summary) — https://www.mecalux.com/logistics-articles/effect-substitutions-online-retailing | Summary of academic research |
| S8 | RetailWire, "Substitutions improved online grocery" — https://retailwire.com/discussion/substitutions-improved-online-grocery | Trade press, cites vendor surveys |
| S9 | Which?, supermarket substitutions survey — https://www.which.co.uk/policy-and-insight/article/sanitary-towels-instead-of-sandwich-wraps-which-reveals-the-worst-supermarkets-for-substitutions-avmh87E2rQmk | Consumer survey |
| S10 | Grocery Dive, substitution alerts — https://www.grocerydive.com/news/grocers-often-miss-chances-to-alert-shoppers-about-online-substitutions-su/622775/ | Trade press |
