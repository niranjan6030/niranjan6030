<div align="center">
  <img src="./assets/banner.svg" alt="Niranjan S — full-stack and data" width="100%"/>
</div>

<br/>

## About

I work at the join between web engineering and data analysis. On one side that
means storefronts that take real payments and dashboards people actually read;
on the other it means SQL, pandas, and pipelines that expect duplicates and
missing values rather than assuming clean input.

The thing I care about across both is that a number can be traced back to where
it came from. A dashboard that can't tell you the query behind it is one you
have to take on faith, and a price shown to a customer should be the same price
they are charged — computed once, in one place.

Everything below I built end to end and debugged until it worked.

**Reach me** — [niranjan6030@gmail.com](mailto:niranjan6030@gmail.com)

<br/>

## Selected work

<table>
<tr><td width="50%" valign="top">

### [Grezzo](https://github.com/niranjan6030/grezzo)
**Menswear denim commerce platform**

Stock held per product, colour, size *and* warehouse on an append-only movement
ledger. Checkout takes a fifteen-minute reservation rather than decrementing
immediately, so an abandoned payment never costs a sale. Coupon and pricing
rules evaluate once on the server, so the displayed price and the charged price
cannot diverge.

`Next.js` `TypeScript` `PostgreSQL` `Firebase` `Razorpay` `PyTorch`

[Live site](https://grezzo-ruddy.vercel.app) ·
[Inventory schema](https://github.com/niranjan6030/grezzo/blob/main/supabase/schema.sql) ·
[Deployment guide](https://github.com/niranjan6030/grezzo/blob/main/DEPLOY.md)

</td><td width="50%" valign="top">

### [Carbon Ledger](https://github.com/niranjan6030/Carbon-Ledger)
**270 years of global CO₂ emissions**

Four questions, one of them the point of the whole thing: which countries have
grown an economy while cutting emissions. Ranking per capita rather than per
country changes the answer substantially, which is exactly why both are shown.

`Python` `pandas` `JavaScript` `Data visualisation`

[Live dashboard](https://niranjan6030.github.io/Carbon-Ledger/carbon-ledger/app/index.html) ·
[Analysis](https://github.com/niranjan6030/Carbon-Ledger/tree/main/carbon-ledger/analysis)

</td></tr>
<tr><td width="50%" valign="top">

### [E-commerce Analytics](https://github.com/niranjan6030/ecommerce-dashboard)
**Revenue against acquisition, on one timeline**

Revenue rising while acquisition flattens means the existing base is spending
more; the reverse means growth is being bought. Plotting them separately hides
that, so they share an axis. Includes a query inspector that shows the request
behind every figure on screen.

`Next.js` `TypeScript` `Recharts`

[Live dashboard](https://ecommerce-dashboard-zeta-livid.vercel.app) ·
[Analytics API](https://github.com/niranjan6030/ecommerce-dashboard/blob/main/app/api/analytics/route.ts)

</td><td width="50%" valign="top">

### [Hardware Inventory & Reorder Analytics](https://github.com/niranjan6030/hardware_inventory_supply_chain)
**GPU supply chain, modelled relationally**

Multi-table joins and CTEs to surface stock shortages against supplier lead
times, plus a Python job that exports reorder alerts before anything actually
runs out.

`SQL` `Python` `pandas`

[SQL queries](https://github.com/niranjan6030/hardware_inventory_supply_chain/blob/main/hardware_inventory_supply_chain/sql_queries/inventory_analysis.sql) ·
[Reorder pipeline](https://github.com/niranjan6030/hardware_inventory_supply_chain/blob/main/hardware_inventory_supply_chain/python/inventory_report.py)

</td></tr>
<tr><td width="50%" valign="top">

### [VisionMetric Dashboard](https://github.com/niranjan6030/VisionMetric-Dashboard)
**Real-time video processing, measured**

The engine is kept deliberately separate from the interface, and both FPS and
per-frame inference latency are recorded — so an optimisation can be shown to
be faster rather than assumed to be.

`OpenCV` `Streamlit` `Python` `NumPy`

[Detector](https://github.com/niranjan6030/VisionMetric-Dashboard/blob/main/vision-metric-dashboard/detector.py) ·
[Benchmark](https://github.com/niranjan6030/VisionMetric-Dashboard/blob/main/vision-metric-dashboard/benchmark.py)

</td><td width="50%" valign="top">

### [Food Delivery Analysis](https://github.com/niranjan6030/food-delivery-analysis)
**Delivery times and revenue from raw order logs**

Duplicates and missing values left in the source data on purpose. Missing
delivery times are imputed from city medians rather than a global one, because
a slow city is slow for reasons that do not generalise.

`Python` `pandas` `matplotlib`

[Analysis](https://github.com/niranjan6030/food-delivery-analysis/blob/main/food_delivery_analysis/analysis.py) ·
[Dataset generator](https://github.com/niranjan6030/food-delivery-analysis/blob/main/food_delivery_analysis/generate_data.py)

</td></tr>
</table>

<br/>

## Toolkit

| | |
|---|---|
| **Languages** | TypeScript · Python · SQL · JavaScript |
| **Web** | Next.js · React · Node · Tailwind CSS |
| **Data** | pandas · NumPy · PostgreSQL · MySQL · matplotlib |
| **ML / CV** | PyTorch · OpenCV · CLIP |
| **Platform** | Firebase · Supabase · Vercel · Git |

<div align="center">
<br/>
<img src="https://skillicons.dev/icons?i=ts,python,react,nextjs,nodejs,postgres,mysql,tailwind,pytorch,opencv,firebase,supabase,vercel,git&theme=dark" />
</div>

<br/>

---

<div align="center">
<sub>Bangalore, India · <a href="mailto:niranjan6030@gmail.com">niranjan6030@gmail.com</a></sub>
</div>
