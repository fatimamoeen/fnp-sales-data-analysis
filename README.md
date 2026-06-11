![header](https://capsule-render.vercel.app/api?type=waving&color=0:c94b4b,100:4b134f&height=200&section=header&text=FNP%20Sales%20Analysis&fontSize=50&fontColor=ffffff&animation=fadeIn)

## Table of Contents
- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Data Transformation](#data-transformation)
- [Key Insights](#key-insights)
- [Business Recommendations](#business-recommendations)
- [Dashboard Preview](#dashboard-preview)

---

## Introduction

I had the opportunity to complete a project using **FNP's (Ferns N Petals) Sales Dataset**. FNP is one of India's leading gifting platforms — delivering flowers, sweets, soft toys, and curated gifts for occasions like Holi, Diwali, Valentine's Day, Raksha Bandhan, birthdays, and anniversaries.

My goal was to journey through this dataset and create visual representations of the data to assess what was actually driving their revenue — which occasions performed, which cities were buying the most, and whether their delivery was holding up under load.

By exploring this data with **Microsoft Excel**, I aimed to identify trends and patterns that can help FNP make smarter decisions around inventory, marketing timing, and untapped city-level demand.

---

## Project Overview

| Aspect | Details |
|--------|---------|
| **Business Goal** | Identify revenue drivers across occasions, cities, and product categories — and surface actionable gaps in FNP's sales strategy |
| **Dataset** | FNP Sales Dataset — ~1,000 orders from 2023 (raw data file included in this repository) |
| **Time Frame** | FY 2023 (full year) |
| **Grain** | One record per order |
| **Key Dimensions** | Occasion, Category, Product, City, Order Date, Delivery Date, Day of Week |
| **Key Facts** | Total Revenue, Average Delivery Time, Order Volume, Monthly Sales Trend |
| **Tools Used** | Microsoft Excel — Pivot Tables, Slicers, Bar Charts, Line Charts |

---

## Data Transformation

- Cleaned raw order data — removed duplicates and standardized categorical values
- Created calculated fields for **delivery time** (Delivery Date − Order Date)
- Built pivot tables segmented by occasion, category, city, and day of week
- add slicers (Delivery Date, Order Date, Occasion) to pivot tables for full interactivity

---

## Key Insights

**Holi is the real revenue driver — not Valentine's Day**
Holi pulls roughly 3x the revenue of birthday orders. The Colors category flatlines every other month and then explodes in March. This was counterintuitive enough that I went back and verified it twice.

**February is their strongest month**
Valentine's Day carries heavy lifting. August–September is decent too (Raksha Bandhan + early festive season). June and July are noticeably quiet — no major occasions means barely any orders.

**Soft Toys and Sweets carry the catalogue**
The top 5 products bring in a disproportionate share of total revenue. The rest of the catalogue is long-tail — most products barely move.

**Smaller cities showed up unexpectedly**
Metros dominate as expected — but Imphal and Kavali appearing in the top 10 was a genuine surprise. Organic demand in cities FNP is likely not heavily marketing to.

**Delivery holds up under load**
Higher order volumes don't appear to stretch delivery times significantly. Average sits at **5.53 days**. Tuesday is consistently the highest order day — counterintuitive but stable across the data.

**Diwali underperforms**
For how culturally significant it is, Diwali's revenue numbers are underwhelming compared to Holi. Either pricing is off or FNP is losing ground to competitors during that window.

---

## Business Recommendations

**Double down on Holi, rethink Diwali**
The data is clear — Holi is where the money is. Inventory planning, logistics prep, and marketing campaigns should begin at least 6 weeks out. Diwali needs a strategic rethink — whether it's a pricing problem, product-fit problem, or competition from Amazon and Flipkart during that window.

**Build a June–July strategy**
These two months are effectively dead. A B2B corporate gifting push — employee birthdays, work anniversaries, onboarding gifts — doesn't depend on seasonal occasions and could smooth the revenue dip significantly.

**Stop ignoring Tier-2 cities**
Imphal and Kavali appearing organically in the top 10 without an obvious marketing push signals real unserved demand. Even localized campaigns or delivery partnerships in 4–5 such cities could unlock meaningful incremental revenue.

**Fix catalogue concentration risk**
The top 5 products carry everything — a fragile position. If one goes out of stock during Holi or Valentine's Day, revenue takes a direct hit. FNP should either actively promote mid-catalogue products or cut dead SKUs and reinvest in proven sellers.

**Time campaigns around Tuesday**
Tuesday is consistently the highest order day — likely when customers plan ahead for weekend deliveries. A well-timed Monday evening email or push notification could capture buyers right as they're already thinking about FNP.

---

## Dashboard Preview

![FNP Sales Dashboard](./dashboard%20of%20sales%20analysis.png)

---


