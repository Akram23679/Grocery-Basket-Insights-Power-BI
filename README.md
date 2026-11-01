# Grocery Basket Insights

**CDACL-006 Market Analysis** · Power BI project by **Akram Ali**

What 63,100 online grocery shoppers buy, when they shop, and six actions to grow orders.

![Power BI overview page](3_Dashboard/Power_BI_Screenshots/Page1_Overview.png)

## At a glance

| | |
|---|---|
| **Data** | 49,355 products · 63,100 customers · 1,048,575 order rows · 5 joined tables |
| **Questions** | 20 business questions from the client brief |
| **Tools** | MySQL · Power Query · DAX · Power BI |
| **Output** | 8-page Power BI dashboard, client report, presentation, video walkthrough |

## Key findings

- **59.9% of items are repeat buys.** Fresh produce and dairy drive the business; Banana is the top product (14,136 orders) and milk is reordered 79% of the time.
- **Demand starts the week high.** Sunday and Monday carry 35% of orders; orders peak at 10 am (88,228).
- **Weekend baskets are bigger.** 11.6 items on Sunday against 9.6 on Wednesday.
- **Customers return about every 15 days.** 431 loyal customers have placed 100 orders each.

## Recommendations

1. Never run out of top staples (milk, bananas, berries, eggs, bread), especially before Sunday and Monday.
2. Add delivery slots and staff from 10 am to 5 pm and on Sunday and Monday.
3. Run weekend "big basket" offers.
4. Send reorder reminders about 14 days after a customer's last order.
5. Start a loyalty programme for the most frequent customers.
6. Bundle low-reorder aisles (spices, baking, kitchen, health and beauty) with staples.

## Repository

```
index.html, style.css      project web page (HTML and CSS only)
assets/walkthrough.mp4     recorded report walkthrough
1_Brief/                   client brief and the 20 questions
2_Data/                    aisles, departments and products tables (CSV)
3_Dashboard/               Power BI page screenshots and an interactive web dashboard
4_Report/                  client report (PDF)
5_Presentation/            presentation (PPTX and PDF)
```

The `orders` and `order_products_train` tables (about 50 MB) are not included.

## Data notes

- The orders tables stop at 1,048,575 rows (the database export limit), so exact totals would be somewhat higher.
- 1,254 products have no aisle or department; 249 product IDs are not in the products table (0.65% of rows).
- The data has no prices, so performance is measured by orders and reorders rather than revenue.
