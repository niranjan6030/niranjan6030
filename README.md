<div align="center">
  <img src="./assets/histogram.svg" alt="Niranjan S — full-stack engineering and data analysis" width="100%"/>
</div>

<br/>

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

## Selected work

### [Grezzo](https://github.com/niranjan6030/grezzo) &nbsp;·&nbsp; [live](https://grezzo-ruddy.vercel.app)
`next.js` `typescript` `postgres` `firebase` `razorpay` `pytorch`

Menswear denim commerce platform. Stock is held per product, colour, size **and**
warehouse on an append-only movement ledger. Checkout takes a fifteen-minute
reservation rather than decrementing immediately, so an abandoned payment never
costs a sale. Pricing and coupon rules evaluate once on the server, so the price
displayed and the price charged cannot diverge.

<sub>[schema.sql](https://github.com/niranjan6030/grezzo/blob/main/supabase/schema.sql) · [deploy.md](https://github.com/niranjan6030/grezzo/blob/main/DEPLOY.md)</sub>

### [Carbon Ledger](https://github.com/niranjan6030/Carbon-Ledger) &nbsp;·&nbsp; [live dashboard](https://carbon-ledger-orpin.vercel.app)
`python` `pandas` `javascript`

270 years of global CO₂ emissions, built around four questions — one of them the
point of the whole thing: which countries grew an economy while cutting
emissions. Ranking per capita rather than per country changes the answer
substantially, which is exactly why both are shown.

<sub>[analysis/](https://github.com/niranjan6030/Carbon-Ledger/tree/main/carbon-ledger/analysis)</sub>


### [Hardware Inventory & Reorder Analytics](https://github.com/niranjan6030/hardware_inventory_supply_chain) &nbsp;·&nbsp; [live](https://hardware-inventory-ten.vercel.app)
`sql` `python` `pandas`

A GPU and hardware supply chain modelled relationally. Multi-table joins and CTEs
surface stock shortages against supplier lead times, and a Python job exports
reorder alerts before anything actually runs out.

<sub>[inventory_analysis.sql](https://github.com/niranjan6030/hardware_inventory_supply_chain/blob/main/hardware_inventory_supply_chain/sql_queries/inventory_analysis.sql) · [inventory_report.py](https://github.com/niranjan6030/hardware_inventory_supply_chain/blob/main/hardware_inventory_supply_chain/python/inventory_report.py)</sub>

### [VisionMetric Dashboard](https://github.com/niranjan6030/VisionMetric-Dashboard) &nbsp;·&nbsp; [live](https://visionmetric-gold.vercel.app)
`opencv` `streamlit` `python` `numpy`

Real-time video processing with the engine deliberately kept separate from the
interface. FPS and per-frame inference latency are both recorded, so an
optimisation can be *shown* to be faster rather than assumed to be. The live
version runs four operators in the browser and times each frame.

<sub>[detector.py](https://github.com/niranjan6030/VisionMetric-Dashboard/blob/main/vision-metric-dashboard/detector.py) · [benchmark.py](https://github.com/niranjan6030/VisionMetric-Dashboard/blob/main/vision-metric-dashboard/benchmark.py)</sub>


<br/>

## Toolkit

| | |
|---|---|
| **Languages** | TypeScript · Python · SQL · JavaScript |
| **Web** | Next.js · React · Node · Tailwind |
| **Data** | pandas · NumPy · PostgreSQL · MySQL · matplotlib |
| **ML / CV** | PyTorch · OpenCV · CLIP |
| **Platform** | Firebase · Supabase · Vercel · Git |

<br/>

---

<div align="center">
<sub><b>niranjan6030@gmail.com</b> &nbsp;·&nbsp; Bangalore, India</sub>
</div>
