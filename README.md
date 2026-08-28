<div align="center">
  <img src="./assets/terminal.svg" alt="niranjan@github — terminal session" width="100%"/>
</div>

<br/>

```console
niranjan@github:~$ cat about.md
```

I work at the join between web engineering and data analysis. On one side that
means storefronts taking real payments and dashboards people actually read; on
the other, SQL and pandas over inputs that arrive with duplicates and gaps
rather than arriving clean.

What I care about across both: a number should be traceable to where it came
from. A dashboard that cannot show you the query behind it is one you have to
take on faith, and the price a customer is shown should be the price they are
charged — computed once, in one place.

Everything below I built end to end and debugged until it worked.

<br/>

```console
niranjan@github:~$ ls -la projects/
```

<pre>drwxr-xr-x  <a href="https://github.com/niranjan6030/grezzo"><b>grezzo/</b></a>            next.js · postgres</pre>

Menswear denim commerce platform. Stock is held per product, colour, size **and**
warehouse on an append-only movement ledger. Checkout takes a fifteen-minute
reservation rather than decrementing immediately, so an abandoned payment never
costs a sale. Pricing and coupon rules evaluate once on the server, so the price
displayed and the price charged cannot diverge.

[live](https://grezzo-ruddy.vercel.app) · [schema.sql](https://github.com/niranjan6030/grezzo/blob/main/supabase/schema.sql) · [deploy.md](https://github.com/niranjan6030/grezzo/blob/main/DEPLOY.md)

<pre>drwxr-xr-x  <a href="https://github.com/niranjan6030/Carbon-Ledger"><b>carbon-ledger/</b></a>     python · pandas</pre>

270 years of global CO₂ emissions, built around four questions — one of them the
point of the whole thing: which countries grew an economy while cutting
emissions. Ranking per capita rather than per country changes the answer
substantially, which is exactly why both are shown.

[live dashboard](https://niranjan6030.github.io/Carbon-Ledger/carbon-ledger/app/index.html) · [analysis/](https://github.com/niranjan6030/Carbon-Ledger/tree/main/carbon-ledger/analysis)

<pre>drwxr-xr-x  <a href="https://github.com/niranjan6030/ecommerce-dashboard"><b>ecommerce-dashboard/</b></a>  next.js · recharts</pre>

Revenue plotted against customer acquisition on one timeline. Revenue rising
while acquisition flattens means the existing base is spending more; the reverse
means growth is being bought — plotting them apart hides that. Includes a query
inspector showing the request behind every figure on screen.

[live](https://ecommerce-dashboard-zeta-livid.vercel.app) · [analytics/route.ts](https://github.com/niranjan6030/ecommerce-dashboard/blob/main/app/api/analytics/route.ts)

<pre>drwxr-xr-x  <a href="https://github.com/niranjan6030/hardware_inventory_supply_chain"><b>hardware-inventory/</b></a>   sql · python</pre>

A GPU and hardware supply chain modelled relationally. Multi-table joins and CTEs
surface stock shortages against supplier lead times, and a Python job exports
reorder alerts before anything actually runs out.

[inventory_analysis.sql](https://github.com/niranjan6030/hardware_inventory_supply_chain/blob/main/hardware_inventory_supply_chain/sql_queries/inventory_analysis.sql) · [inventory_report.py](https://github.com/niranjan6030/hardware_inventory_supply_chain/blob/main/hardware_inventory_supply_chain/python/inventory_report.py)

<pre>drwxr-xr-x  <a href="https://github.com/niranjan6030/VisionMetric-Dashboard"><b>vision-metric/</b></a>     opencv · streamlit</pre>

Real-time video processing with the engine deliberately kept separate from the
interface. FPS and per-frame inference latency are both recorded, so an
optimisation can be *shown* to be faster rather than assumed to be.

[detector.py](https://github.com/niranjan6030/VisionMetric-Dashboard/blob/main/vision-metric-dashboard/detector.py) · [benchmark.py](https://github.com/niranjan6030/VisionMetric-Dashboard/blob/main/vision-metric-dashboard/benchmark.py)

<pre>drwxr-xr-x  <a href="https://github.com/niranjan6030/food-delivery-analysis"><b>food-delivery/</b></a>     python · matplotlib</pre>

Delivery times and revenue from raw order logs, with duplicates and missing
values left in the source on purpose. Missing delivery times are imputed from
city medians rather than a global one, because a slow city is slow for reasons
that do not generalise.

[analysis.py](https://github.com/niranjan6030/food-delivery-analysis/blob/main/food_delivery_analysis/analysis.py) · [generate_data.py](https://github.com/niranjan6030/food-delivery-analysis/blob/main/food_delivery_analysis/generate_data.py)

<br/>

```console
niranjan@github:~$ cat stack.txt
```

| | |
|---|---|
| `languages` | TypeScript · Python · SQL · JavaScript |
| `web` | Next.js · React · Node · Tailwind |
| `data` | pandas · NumPy · PostgreSQL · MySQL · matplotlib |
| `ml / cv` | PyTorch · OpenCV · CLIP |
| `platform` | Firebase · Supabase · Vercel · Git |

<br/>

```console
niranjan@github:~$ contact --email
```

**niranjan6030@gmail.com** &nbsp;·&nbsp; Bangalore, India
