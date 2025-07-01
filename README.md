# TechStreamData_economic
calculate the economic metrics in Colab with Python and Pandas for a dataset from Tech Stream Data company

# Data source:
A google drive shared folder containing a SaaS company data:
https://drive.google.com/drive/folders/1qhOW9Y2orRXuzbX-kXEmuJ7TMQiRs2Uv?usp=drive_link

# Goal:
Calculate the following metrics in Colab with Python and Pandas and give insight & recommendation for the company improvement:
- CAC
- ARPU
- COGS
- Gross Margin
- LTV
- LTV / CAC

# Results:
Although most of the figures are excellent, LTV/CAC ratio which is 1.74 point out that CAC is high compared to the LTV.
This means, the profitability is under pressure from acquisition costs

# Summary of key values:
- Gross Margin (75.60%) : Excellent
- Profitability (Revenue > Expenses) : Positive
- Active customer acquisition (63 new customers)
- LTV (2,115.52) : good in general
- ARPU (284.36) : Healthy
- LTV/CAC: 1.74 : Ideally 3:1 or higher

# Key Insights:
**Profitability Under Pressure from Acquisition Costs:**

 While the company is profitable on paper this month and has an excellent gross margin, the low LTV/CAC ratio indicates that their customer acquisition strategy is not sustainable for long-term, scalable growth. They are spending too much to acquire customers compared to the value those customers bring.

**Marketing Efficiency is Low:**

  The significant marketing spend ($68,830) is not translating into a sufficiently high return on investment (as evidenced by the CAC and LTV/CAC). This suggests either:
*  Ineffective marketing channels/campaigns.
*  Targeting the wrong audience.
*  Poor conversion rates within the sales funnel.

**Retention Opportunity:**

A customer lifespan of under 10 months means churn is likely impacting overall LTV. Even a small improvement in retention could significantly boost LTV and, consequently, the LTV/CAC ratio.

**Production is Lean:**

The fact that COGS is entirely attributed to "Production salary" and the gross margin is high suggests that the core service delivery is efficient from a cost perspective.
For more details, please refer to the colab link (or the attached file): 
https://colab.research.google.com/drive/1x9VlA24H_qz44uKOonITMCRq6fQqYyRc?usp=sharing
