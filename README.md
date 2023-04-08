[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-8d59dc4de5201274e310e4c54b9627a8934c3b88527886e3b421487c677d23eb.svg)](https://classroom.github.com/a/elzutNYu)
[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-f4981d0f882b2a3f0472912d15f9806d57e124e0fc890972558857b51b24a6f9.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=10640244)
# **Relocation Social Insurance Program**

**Group 2**

**Team Members: Damian Ewington, Tony Nguyen, Rohan Saini, Matthew Xie**

<div align="center">
<img src="global.gif"  width="960" height="541.5"/>
</div>

## **Overview**

Storslysia is acutely threatened by the impact of natural disasters that are increasing 
over time due to climate change. The leaders of Storslysia are highly motivated to manage the 
risks associated with such catastrophes and wish to consider implementing a 
social relocation insurance program to help manage its exposure to the financial impacts of mass 
displacement.
This page outlines the proposed social relocation insurance program available to all citizens for 
voluntary relocation to help Storslysia manage its exposure to displacement risk 
arising from catastrophic climate-related events.
<br>
This project was based on the 2023 SOA Research Institute Student Research Case Study Challenge.
For more details, please click [here](https://www.soa.org/research/opportunities/2023-student-research-case-study-challenge/).

### **Key Objectives**

There are 3 key objectives for the proposed program:
1. To provide coverage for all citizens of Storslysia against the financial impacts of emergency
displacement.
2. To encourage voluntary, proactive relocation to less risky geographic regions to reduce  economic costs with a high degree of certainty. 
3. To prevent costs arising from relocation (voluntary or catastrophe-related 
displacement) from exceeding 10% of Storslysia’s gross domestic product (GDP) each 
year with a high degree of certainty.

### **Key Metrics**

The following key metrics will be used to monitor the program’s success annually
over the short-term (2023-2028) and long-term (2023-2053) time frames:
1. Number of claims and amounts paid out by each region. 
2. Percentage of population voluntarily relocating by region.
3. Reduction in economic costs of involuntary relocation by region. 
4. Reduction in percentage of GDP expended on relocation. 

### **Key Assumptions**

**Financial Assumptions**

* Inflation: Short term inflation of 3.85% in 2023 is assumed which linearly transitions to a 
long-term baseline at 2.00%. Scenario loadings are applied for the long-term rate.
* Risk-free yields: short term risk-free rates are assumed at 0.79% in 2023 which linearly 
transition to a long-term baseline at 2.50%. Scenario loadings are applied for the long-term rate.
* Historical Population Growth Rate: from years 1960-2020, we assumed that population 
grew at a rate of 0.85% yearly. This was selected based on the projected population 
growth rates for future years provided.

**Relocation Assumptions**

A significant assumption for our voluntary program is that it will cause the population of 
Storslysia to relocate towards safer regions. Hence, we have implemented a relocation model 
with the following assumptions.

* We have assumed that the population of Storylsia will be able to relocate to different 
regions at the start of each year.
* The rates of relocation are decided by a pre-determined matrix transition rate which 
specifies the percentage of a region will relocate with respect to its population.
* This relocation matrix is constant and does not change as the program develops.

We have designed this matrix to replicate the goals of the program and was 
informed by our region risk analysis. More specifically, to move Storylsias citizens away from 
high-risk regions to low-risk regions.

**Yearly Incentives**

Incentive amounts are fixed for each region throughout the program’s timeframe. This is done 
to simplify calculations. To see the assumed yearly incentives. The value of 
these incentives directly influences the costs of the program, as a result, they have a significant 
impact on the projected costs.

**Distribution Assumptions**

* Relocation severity for each hazard event classification (minor, medium or major) is 
assumed to be constant and equal to the estimate based on historical values, with only 
inflation indexing. This is a significant assumption that would impact the variability of 
our total claim cost.
* Hazard event frequency is assumed to follow a Poisson distribution and grows as per the 
projection model provided. Poisson is a natural distribution to use for count data and is 
common practice in the insurance industry.

## **Program Design**

### **Claims Requirements, Coverage, and Limitations**

To be eligible for coverage, Storslysia citizens must be displaced from their home due to a 
climate catastrophe-related event and must file for a claim within 60 days.
The program will cover the costs associated with relocation which includes temporary housing, 
replacement of household items, income loss and medical related costs.
However, no coverage will be provided for costs associated with permanent relocation or 
reconstruction of their original home as the program solely focuses on providing insurance for 
costs pertaining to relocation.

### **Incentives for Voluntary Relocation**

Each citizen receives a monetary incentive if they move to another region. The incentive amount 
is contingent on their current region of residence and the region they will relocate to. The table 
below shows the incentive amounts that citizens from each region will receive.
Citizens of regions 1, 3 and 5 do not receive an incentive as they already reside in low-risk regions.
Furthermore, citizens of region 2, 4, and 6 are only eligible for incentives if they move to region 1 or 3 which have been determined as low risk zones.

| **Region 1** | **Region 2** | **Region 3** | **Region 4** | **Region 5** | **Region 6** |
| -----------: | -----------: | -----------: | -----------: | -----------: | -----------: |
| $0           | $2,000       | $0           | $1,000       | $0           | $1,000       |

### **Other Program Features**

The program will prioritize the relocation of citizens based in high-risk geographic zones and 
citizens who cannot afford home and contents insurance and/or earn lower income as they are 
deemed more vulnerable to hazard events.

### **Short-term and Long-term Outlook**

The effectiveness of program will be evaluated in the short-term for years 2023-2028 (5 years)
and long-term for years 2023-2053 (30 years).
<br>
The short-term outlook is chosen to closely monitor key assumptions of the model because our 
pricing is heavily impacted by climate change which is rapidly evolving and new climate related
data continues to emerge exponentially. Furthermore, the model also relies on inputs from 
other climate models which will also continue to improve and evolve over time and so the 
predictions on climate change impacts will also require the model to be updated accordingly.
<br>
The long-term outlook is chosen for evaluating the effectiveness of the program in reducing 
costs and exposure to climate-related displacement as it allows for meaningful migration of 
citizens to less riskier regions and the offset of the initial high cost associated with high 
voluntary movement.

## **Pricing and Costs**


### **Cost Projections**

(TODO)

### **Solvency Capital for Total Cost**

(TODO)

### **Voluntary Costs vs Emergency Displacement Costs**

(TODO)

## **Risk and Risk Mitigation Considerations**

(TODO)

## **Data and Data Limitations**

(TODO)