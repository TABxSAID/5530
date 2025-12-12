# Comprehensive EDA Report
Integrated analysis of behavior, customers, categories. Detailed for jury: Visuals clear with annotations; interpretations highlight insights like high browsing, category dominance for business decisions.

## Basic Stats
### Event Types
| event_type   |           count |
|:-------------|----------------:|
| view         |     4.07766e+06 |
| cart         | 91991           |
| purchase     | 74646           |
Interpretation: Views dominate, indicating exploration phase.
### Top Brands
| brand   |   count |
|:--------|--------:|
| unknown |  611856 |
| samsung |  528577 |
| apple   |  412034 |
| xiaomi  |  308870 |
| huawei  |  111963 |
| lucente |   65732 |
| lg      |   56317 |
| bosch   |   55690 |
| oppo    |   48469 |
| sony    |   45511 |
Interpretation: Focus marketing on top brands.
### Top Categories
| category_code                    |            count |
|:---------------------------------|-----------------:|
| unknown                          |      1.35044e+06 |
| electronics.smartphone           |      1.15178e+06 |
| electronics.clocks               | 131290           |
| computers.notebook               | 113656           |
| electronics.video.tv             | 111265           |
| electronics.audio.headphone      | 110321           |
| appliances.kitchen.refrigerators |  89059           |
| appliances.kitchen.washer        |  87084           |
| appliances.environment.vacuum    |  79800           |
| apparel.shoes                    |  76673           |
Interpretation: Electronics lead, suggest inventory priority.
### Top Pairs
[((1004856, 1004856), 4310), ((1004767, 1004767), 3528), ((4804056, 4804056), 2069), ((1004833, 1004833), 1963), ((1004870, 1004870), 1878), ((1005115, 1005115), 1863), ((5100816, 5100816), 1826), ((1002544, 1002544), 1475), ((1004249, 1004249), 1436), ((1004741, 1004741), 1373)]
Interpretation: Co-views for bundling.
## Visitor Analysis
|    | date       |   unique_visitors | day_of_week   |
|---:|:-----------|------------------:|:--------------|
|  0 | 2019-10-28 |             70560 | Monday        |
|  1 | 2019-10-21 |             79080 | Monday        |
|  2 | 2019-10-07 |             67822 | Monday        |
|  3 | 2019-10-14 |             79501 | Monday        |
|  4 | 2019-10-01 |             69588 | Tuesday       |
|  5 | 2019-10-29 |             68758 | Tuesday       |
|  6 | 2019-10-22 |             79856 | Tuesday       |
|  7 | 2019-10-08 |             78827 | Tuesday       |
|  8 | 2019-10-15 |             85170 | Tuesday       |
|  9 | 2019-10-23 |             77933 | Wednesday     |
| 10 | 2019-10-30 |             68821 | Wednesday     |
| 11 | 2019-10-16 |             84762 | Wednesday     |
| 12 | 2019-10-09 |             76248 | Wednesday     |
| 13 | 2019-10-02 |             66759 | Wednesday     |
| 14 | 2019-10-31 |             71033 | Thursday      |
| 15 | 2019-10-10 |             73155 | Thursday      |
| 16 | 2019-10-17 |             77902 | Thursday      |
| 17 | 2019-10-03 |             62830 | Thursday      |
| 18 | 2019-10-24 |             74237 | Thursday      |
| 19 | 2019-10-11 |             83082 | Friday        |
| 20 | 2019-10-18 |             82798 | Friday        |
| 21 | 2019-10-25 |             80055 | Friday        |
| 22 | 2019-10-04 |             78291 | Friday        |
| 23 | 2019-10-26 |             73994 | Saturday      |
| 24 | 2019-10-05 |             73008 | Saturday      |
| 25 | 2019-10-19 |             79438 | Saturday      |
| 26 | 2019-10-12 |             79314 | Saturday      |
| 27 | 2019-10-06 |             71882 | Sunday        |
| 28 | 2019-10-27 |             75081 | Sunday        |
| 29 | 2019-10-20 |             83806 | Sunday        |
| 30 | 2019-10-13 |             86336 | Sunday        |
Interpretation: Peaks inform ad timing.
## Customer Analysis
- total_customers: 1389584
- repeat_customers: 537268
- avg_sessions: 2.008085153542355
- avg_purchases: 0.053718235097698304
- repeat_buyers: 8398
Interpretation: Low repeats suggest retention strategies.
## Category Analysis
- total_activities: 4244293
- total_visits: 2790396
- total_visitors: 1389584
- total_categories: 127
- total_brands: 3151
- total_products: 125264
### Visits per Category
|    | main_category   |   visits |
|---:|:----------------|---------:|
|  7 | electronics     |  1159088 |
| 13 | unknown         |   928493 |
|  2 | appliances      |   323457 |
|  4 | computers       |   150937 |
|  1 | apparel         |   104904 |
|  8 | furniture       |    87507 |
|  3 | auto            |    71820 |
|  5 | construction    |    48364 |
|  9 | kids            |    37255 |
|  0 | accessories     |    16617 |
| 11 | sport           |    13325 |
| 10 | medicine        |     1148 |
|  6 | country_yard    |     1101 |
| 12 | stationery      |      585 |
### Top Subcategories
| sub_category   |   visits |   visitors |
|:---------------|---------:|-----------:|
| unknown        |   928493 |     580563 |
| smartphone     |   837721 |     511714 |
| clocks         |    93273 |      67083 |
| headphone      |    86290 |      65258 |
| tv             |    79354 |      59147 |
| notebook       |    73402 |      48962 |
| refrigerators  |    61076 |      45459 |
| washer         |    59982 |      44035 |
| vacuum         |    53251 |      40741 |
| shoes          |    51603 |      39986 |
Interpretation: Subcats reveal niches.
Visuals in visuals/eda/