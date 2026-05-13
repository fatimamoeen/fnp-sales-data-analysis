# FNP Sales Analysis

I built this dashboard as part of a data analytics case study using FNP's (Ferns and Petals) sales data. FNP is a gifting platform — think flowers, sweets, soft toys delivered for occasions like Holi, Diwali, Valentine's Day, birthdays, anniversaries, and Raksha Bandhan.

The dataset had about 1,000 orders from 2023 and I wanted to figure out what was actually driving their revenue, which cities were buying the most, and whether their delivery was holding up under load.

#What I found

•	Holi is their biggest occasion.Not Valentine's Day, not Diwali — Holi. It pulls roughly 3x the revenue of birthday orders. Once I saw this I went back and checked twice because it genuinely surprised me. The Colors category basically flatlines every other month and then explodes in March.

•	February is their best month** — Valentine's Day does a lot of heavy lifting. August-September is decent too (Raksha Bandhan + early festive season). June and July are quiet. Like, really quiet. No major occasions = barely any orders. That's probably where a corporate gifting or birthday-focused push could make a difference.

•	Soft Toys and Sweets carry the catalogue.** The top 5 products bring in a disproportionate chunk of total revenue. The rest of the catalogue is pretty long tail — most products barely move.

•	Smaller cities showed up unexpectedly.** I expected metros to dominate and they do, but Imphal and Kavali appearing in the top 10 was interesting. Organic demand in places FNP probably isn't heavily marketing to.

•	Delivery holds up okay.** Higher order volumes don't seem to stretch delivery times much — average sits at 5.53 days. Tuesday is the busiest order day which is a bit counterintuitive but consistent across the data.

•	Diwali underperforms.** For how culturally significant it is, the revenue numbers are underwhelming compared to Holi. Either the pricing is off or they're losing to competitors during that window.


# The dashboard

•	Built entirely in Excel — pivot tables, slicers, and charts. You can filter everything by delivery date, order date, and occasion using the slicers on the right side panel.

Covers: total revenue, average delivery time, monthly sales trend, revenue by occasion, top categories, top products, orders by city, and orders by day of week.

```
