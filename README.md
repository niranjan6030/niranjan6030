<div align="center">
  <img src="./assets/histogram.svg" alt="Niranjan S — data analysis and full-stack engineering" width="100%"/>
</div>

<br/>

Third-year BCA student at Christ University, Bangalore, working toward data
analysis — and building the applications that produce the data as well as the
ones that read it. On one side that means SQL and pandas over inputs arriving
with duplicates and gaps rather than arriving clean; on the other, storefronts
taking real payments and dashboards people actually use.

What I care about across both: a number should be traceable to where it came
from. A dashboard that cannot show you the query behind it is one you have to
take on faith, and the price a customer is shown should be the price they are
charged — computed once, in one place.

**Open to data analytics internships.**

<br/>

## Applications

Built end to end and debugged until they worked.

### [Grezzo](https://github.com/niranjan6030/grezzo) &nbsp;·&nbsp; [live](https://grezzo-ruddy.vercel.app)
`next.js` `javascript` `postgres` `firebase` `razorpay` `pytorch`

Menswear denim commerce platform. Stock is held per product, colour, size **and**
warehouse on an append-only movement ledger. Checkout takes a fifteen-minute
reservation rather than decrementing immediately, so an abandoned payment never
costs a sale. Pricing and coupon rules evaluate once on the server, so the price
displayed and the price charged cannot diverge.

<sub>[schema.sql](https://github.com/niranjan6030/grezzo/blob/main/supabase/schema.sql) · [deploy.md](https://github.com/niranjan6030/grezzo/blob/main/DEPLOY.md)</sub>

### [Macro](https://github.com/niranjan6030/macro) &nbsp;·&nbsp; [live](https://macrofitness.vercel.app)
`next.js` `javascript` `supabase` `firebase` `three.js`

Food, training and progress tracking, on one principle: a model identifies the
food, a nutrition database supplies the numbers, and the arithmetic happens in
code. Ask a vision model for a calorie count and it answers fluently and
wrongly — so it is never asked. Training is counted per session rather than by a
blanket activity multiplier, which is the largest source of inflation in
ordinary calculators.

<sub>[fitness/](https://github.com/niranjan6030/macro/tree/main/web/src/lib/fitness) · [nutrition/](https://github.com/niranjan6030/macro/tree/main/web/src/lib/nutrition)</sub>

<br/>

## Team projects

### [Smart Cafeteria](https://github.com/niranjan6030/smart-cafeteria)
`react` `firebase` `firestore` `razorpay`

Final-year project — campus food ordering across six canteen stalls, with
student, kitchen and admin portals over one Firestore database. **My areas:** the
admin and kitchen modules, order lifecycle and stall management, and the
intelligence layer — an M/M/c queueing model for wait times, a walk-forward
validated demand forecast, a four-signal recommender, voice ordering, and a
tool-constrained food assistant.

<sub>[kitchenAnalytics.js](https://github.com/niranjan6030/smart-cafeteria/blob/main/src/kitchenAnalytics.js) · [recommender/](https://github.com/niranjan6030/smart-cafeteria/tree/main/src/recommender)</sub>

### [God's View](https://github.com/niranjan6030/gods-view) &nbsp;·&nbsp; [live](https://gods-view-demo.netlify.app)
`three.js` `webxr` `netlify` `supabase`

A four-person WebXR cosmos explorer for teaching space — stand on a planet's
surface, then climb out to the observable universe. Led on the engineering side
by [@Hamzyzz-k](https://github.com/Hamzyzz-k). **My areas:** the promotional
video, researching and verifying the astronomical sources the app presents, and
polishing the desktop interface.

## Data & analysis

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


<br/>

## Toolkit

| | |
|---|---|
| **Languages** | Python · SQL · JavaScript |
| **Data** | pandas · NumPy · PostgreSQL · MySQL · matplotlib |
| **BI** | Power BI · Tableau |
| **Web** | Next.js · React · Node · Tailwind |
| **ML / CV** | PyTorch · OpenCV · CLIP |
| **Platform** | Firebase · Supabase · Vercel · Git |

<br/>

**Visual Artist**, Interactive Avenues — internship, Apr–May 2025, Bengaluru.

<br/>

---

<div align="center">
<sub><b>niranjan6030@gmail.com</b> &nbsp;·&nbsp; <a href="https://www.linkedin.com/in/niranjan-s-8b9283306">LinkedIn</a> &nbsp;·&nbsp; Bengaluru, India</sub>
</div>
