## Niranjan S

I build things that have to survive contact with real data — storefronts that
take payments, dashboards that answer an actual question, pipelines that clean
up after messy inputs. Mostly TypeScript and Python.

---

### What I've been building

**[Grezzo](https://github.com/niranjan6030/grezzo)** · Next.js · TypeScript · PostgreSQL
A menswear denim store, built as a whole system rather than a shop front. Stock
is tracked per product, colour, size **and** warehouse with an append-only
movement ledger; checkout takes a time-limited reservation instead of
decrementing immediately, so an abandoned payment never costs a sale. Payments
run through Razorpay across UPI, cards, net banking, wallets, EMI and cash on
delivery, with coupon rules evaluated once on the server so the price shown and
the price charged cannot diverge. A PyTorch sequence model handles
recommendations and CLIP matches a photographed pair of jeans to the closest
cut in the range.

**[Carbon Ledger](https://github.com/niranjan6030/Carbon-Ledger)** · Python · pandas
270 years of global CO₂ emissions, built around four questions — including the
one that matters most for SDG 13: which countries have grown their economies
while cutting emissions. Per-capita ranking changes the picture substantially
from the per-country one, which is rather the point.

**[E-commerce Analytics Dashboard](https://github.com/niranjan6030/ecommerce-dashboard)** · Next.js · Recharts
Revenue plotted against customer acquisition on one timeline, because the
useful signal is whether they move together. Includes a query inspector that
shows the request behind whatever is on screen — a dashboard that can't tell
you where its numbers came from is one you have to take on faith.

**[Hardware Inventory & Reorder Analytics](https://github.com/niranjan6030/hardware_inventory_supply_chain)** · SQL · Python
A GPU and hardware supply chain modelled relationally: multi-table joins and
CTEs to find stock shortages, supplier lead-time tracking, and a Python job
that exports reorder alerts before anything goes out of stock.

**[VisionMetric Dashboard](https://github.com/niranjan6030/VisionMetric-Dashboard)** · OpenCV · Streamlit
Real-time video processing with the engine deliberately separated from the
interface, measuring FPS and per-frame inference latency — so a change can be
shown to be faster rather than assumed to be.

**[Food Delivery Analysis](https://github.com/niranjan6030/food-delivery-analysis)** · Python · pandas
Delivery times and revenue across cities and cuisines, starting from order logs
with the duplicates and missing values left in on purpose. Missing delivery
times are imputed from city medians rather than a global one, since a slow city
is slow for reasons that don't apply elsewhere.

---

### Tools

`TypeScript` · `Python` · `React` · `Next.js` · `Node` · `PostgreSQL` · `SQL`
`pandas` · `PyTorch` · `OpenCV` · `Streamlit` · `Tailwind` · `Firebase` · `Supabase` · `Git`

---

📫 [niranjan6030@gmail.com](mailto:niranjan6030@gmail.com)
