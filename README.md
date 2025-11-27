
# Sales Case Study | Analytics Plan, Data, Methods & Deliverables

## 1) Purpose & Scope
This README describes what I will do with the provided retail sales dataset, the tools I will use to complete the analysis, and the specific outputs I will deliver. It is aligned to the case‑study instructions that define required metrics (unit price, average price, daily % gross profit, gross profit per unit, price elasticity during promotions) and encourages additional insights via visuals, reports, dashboards and KPIs.

---

## 2) Data Assets

### 2.1 Raw Data
**File:** `Raw Data (2) sorted.csv` 

### 2.2 Processed
**File:** `Processed Data Excel.xlsx`  
**Key derived columns (examples):**
- `GROSS_PROFIT` (Sales − Cost Of Sales)
- `DAILY_UNIT_PRICE` (Sales / Quantity)
- `DAILY_GROSS_PROFIT_PERCENT` (Gross Profit / Sales)
- `DAILY_GROSS_PROFIT_PER_UNIT` (Gross Profit / Quantity)

### 2.3 Questionnaire / Brief
Case Study - Sales Analysis.pdf`  
**Objective:** Calculate the specified metrics, identify at least three promotion/special periods and estimate **Price Elasticity of Demand** for each, then render additional insights via visuals, reports, dashboards, and KPIs.

---

## 3) What I Will Do (Work Plan)

   - Verify row counts and basic aggregates between raw CSV and processed workbook to ensure consistency (e.g., totals for Sales, Cost of Sales, Quantity).  
   - Spot‑check formula logic against sample dates to confirm derived fields (unit price, gross profit and %).

2. **Metric build & summary stats**  
   - Confirm daily metrics are correct (`DAILY_UNIT_PRICE`, `DAILY_GROSS_PROFIT_PERCENT`, `DAILY_GROSS_PROFIT_PER_UNIT`).  
   - Compute **average unit sales price** over the full period and per relevant sub‑periods (e.g., pre‑promo vs promo).

3. **Promotion period identification**  
   - Detect at least **three promotional windows** using a rule‑based approach (e.g., sustained negative gross margin percentage, unit price dips, or external flags if present).  
   - Tag each window in the processed dataset for downstream analysis.

4. **Price Elasticity of Demand (PED)**  
   - For each tagged promotion period, estimate PED using log‑difference or midpoint formula
   - Interpret PED values (elastic/inelastic) and assess whether the product performs better or worse under promotional pricing, using realized gross profit and quantity uplift.

5. **Additional insights**  
   - Identify seasonality, event spikes (e.g., month‑end, holidays) and profitability anomalies.

6. **Reporting & visualization**  
   - Build concise visuals (time series of unit price, quantity, gross profit %; scatter of price vs quantity; promo vs non‑promo comparisons).  
   - Assemble a short narrative report and a compact dashboard highlighting KPIs and promotion findings, as requested by the brief.

## 4) Avenues / Programs I Will Use (and for what)

- **Microsoft Excel**  
  - Inspect and validate formulas already present in `Processed Data Excel.xlsx`.  
  - Create pivot tables, slicers and charts for quick checks and exhibits

- **Power BI (or Excel Dashboard)**  
  - Build an interactive dashboard for KPIs (Avg Unit Price, Avg GP%, Elasticity per promo), with filters for dates and promo periods.  
  - Publish or export insights for faculty review.

3. **Dashboard (Power BI or Excel):**  
   - Interactive visuals:  
     - Time series of Sales, Cost, Quantity, Unit Price, GP%  
     - Scatter: Unit Price vs Quantity (with promo highlights)  
     - KPI tiles: Avg Unit Price, Avg GP%, GP per unit, #Promo periods, Avg PED  




