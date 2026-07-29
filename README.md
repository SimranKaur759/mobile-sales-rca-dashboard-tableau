# Mobile Sales Dashboard: Root Cause Analysis & Proposed Solution

A Tableau workbook analyzing global smartphone sales performance, diagnosing the drivers behind underperformance across brands and markets, and using predictive + prescriptive modeling to recommend a data-backed turnaround strategy.

## 📁 File
`Mobile_Sales_Dashboard_with_Root_Cause_Analysis_and_Proposed_Solution.twbx`

> Open with [Tableau Desktop](https://www.tableau.com/products/desktop) or [Tableau Public](https://public.tableau.com/) (free) to view interactively.

## 🔗 Live Version
View the interactive dashboard on Tableau Public: [Mobile Sales Dashboard with Root Cause Analysis and Proposed Solution](https://public.tableau.com/app/profile/simran.kaur4111/viz/MobileSalesDashboardwithRootCauseAnalysisandProposedSolution/1_Overview)

## 🎯 Business Problem
The company was operating at a **loss of -$28.86K**. Historical trends pointed to continued stagnation (~770K units), but the analysis was built to test whether an aggressive expansion strategy, rather than "business as usual," could turn the business profitable.

## 🔮 Predictive Analysis
- Set a new **Q2 2025 target of 835K units**, an **+8.4% YoY growth** target, versus a flat ~770K "business as usual" forecast.
- Targeted a **+10% volume increase** in the high-velocity **Mid-Range 5G** and **Flagship** segments.
- **China:** demand is highly volatile, so the plan recommends shifting to a **dynamic inventory model** to avoid stockouts during demand spikes.
- **Canada:** flagship sales show structural weakness in Online and Retail channels, so the plan recommends a **proactive engagement strategy** to re-stimulate demand rather than accept the forecasted decline.
- Recommended a **15% increase in Q1 trade spend** to fund both the Canadian recovery and Chinese demand response, supporting the required 1.1x growth.

## 💡 Prescriptive Analysis: Two Optimization Strategies

### Strategy 1: Product Optimization
- **Eliminate the 2 least profitable models** (Google Model 1, Realme Model 3) and **increase sales of the top 4 models by 10%** (Xiaomi Model 1, Motorola Model 4, Motorola Model 5, Google Model 4).
- Result: simulated profit of **~$1.7M**, a swing of roughly **+5,888%** from the original -$28.9K loss.
- Takeaway: cutting underperforming products while doubling down on top performers had an outsized effect on total profit.

### Strategy 2: Market Optimization
- Built a **Market Attractiveness (MA) index** weighting **Profit** and **Growth Rate** equally to rank countries.
- Simulated **+10% units in the top 2 markets** (e.g. UK, India) and **-30% units in the bottom 5 markets**.
- Result: **$283K scenario profit**, a **$311K improvement**, and a **~1,079% increase** vs. current profit.
- Takeaway: reallocating volume toward high-attractiveness markets and shrinking exposure to weak ones drives major profitability gains on its own.

### Combined Impact
Running both strategies together produced a **combined simulated profit of $1,655.88K**, showing that product-level focus and market-level reallocation are complementary levers, not substitutes.

## 📊 Dashboard Contents
- **Root Cause Analysis story:** guided narrative connecting the diagnosis to the proposed solutions
- **KPI Simulation tool:** interactive parameters (Bottom M, Top N, Increase %) letting a user re-run the product optimization scenario live
- **Market Attractiveness map:** geographic view of market size, growth rate, and profit ratio by country
- **Top/Bottom model comparisons:** scatter and bar charts isolating best- and worst-performing models
- **Brand & category breakdowns:** profit and units sold by brand, product type, and channel
- **Trend & forecast:** historical sales trend with the 2025 target overlay
- **Customer insights:** price vs. customer rating, 5G adoption rate

## 🖼️ Screenshots

**Overview**
![Overview](./1.%20Overview.png)

**Predictive Analysis**
![Predictive Analysis](./1.%20Predictive%20Analysis.png)

**Market and Channel**
![Market and Channel](./2.%20Market%20and%20channel.png)

**Prescriptive Analysis**
![Prescriptive Analysis](./2.%20Prescriptive%20Analysis.png)

**Product Analysis**
![Product Analysis](./3.%20Product%20Analysis.png)

**Solution 1**
![Solution 1](./3.%20Solution%201.png)

**Solution 2**
![Solution 2](./4.%20Solution%202.png)

**Diagnostic Analysis**
![Diagnostic Analysis](./4.Diagnostic%20Analysis.png)

**Root Cause Analysis (Story)**
![Root Cause Analysis Story](./5.%20Root%20Casue%20Analysis(Story).png)

## 🛠️ Tools & Skills Demonstrated
- Tableau: calculated fields, parameters, KPI/scenario simulation, dashboards, story points, dual-axis and dumbbell charts, forecasting, geographic mapping
- Predictive analysis (trend forecasting, target-setting)
- Prescriptive analysis (scenario modeling, optimization)
- Data storytelling for executive/business audiences

