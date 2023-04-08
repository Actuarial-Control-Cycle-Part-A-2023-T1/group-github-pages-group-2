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

(TODO)

### **Cost Projections**

(TODO)

### **Solvency Capital for Total Cost**

(TODO)

### **Voluntary Costs vs Emergency Displacement Costs**

(TODO)

## **Risk and Risk Mitigation Considerations**

### **Key Risks with Significant Impacts**

| **Key Risks**   | **Likelihood** | **Severity** | **Description** |
| --------------: | -----------:   | -----------: | :-------------- | 
| Climate Change  | 3              | 4            | Costs of climate events could evolve to become larger beyond inflation, and the frequency of climate disasters may also increase beyond predictions. By assuming disaster related inflation at 30% and replacement of contents at 60% of property value, we integrate a sufficient margin to such potential impacts.       |
| Interest/ inflation  | 4            | 1            | Higher rates of inflation will reduce the ability to meet future cost of scheme and lower interest will reduce the accumulation of present-day funds. Such risks have been accounted for through scenario weighted reserves which account for adverse rates and economic capital to meet unexpected losses (see Section 3).       |
| Relocation Risk  | 3            | 5           | Regions at the focus of relocation can have the potential to be less safe and therefore decrease the effectiveness of relocation. The provision of incentives acts to lower the personal cost of hazards to households as well as to provide ongoing monitoring to adjust relocation assumptions from future data on region specific experience.       |
| Incentive Risk  | 4            | 3            | From the lack of relocation data, Storslysia’s inhabitants may be more reluctant to voluntarily relocate than expected. Thus, population proportions in safer regions may be overvalued and vice versa, resulting in higher-than-expected costs for the program. This is difficult to assess due to social factors such as lifestyle preferences, familial connections within one’s current location, and sentimental values. Arising primarily from a lack of data, future monitoring on the efficacy/value of incentives can improve program design and modelling aspects susceptible to such risk.       |

### **Risk Mitigation Strategies**

Addressing the stated key risks, our program possesses appropriate risk mitigation strategies which aim to employ elements of risk control and financing.  
<br>
| **Key Risks**     | **Mitigation Strategies** |
| :---------------- | :----------- |
| Climate Change    | Conservative margins used in assumptions setting, including value of contents and weather inflation, implicitly builds in an allowance for severity related cost increases. Ongoing repricing and monitoring of the suitability of hazard assumptions will further allow the program to adapt to evolving climate-related costs. |
| Interest/Inflation    | Strategies such as duration matching, and capital modelling can ensure future cash-flows are not adversely affected through interest rate risk. Investment in higher growth assets can also help accumulate capital and make up for future shortfalls from such risks. Investing in inflation indexed assets, although costly, can additionally mitigate the impacts of heightened levels of inflation. |
| Relocation Risk    | Continual monitoring of regional hazard data is necessary in identifying ineffective hazard reduction efforts and investment in climate-resistant infrastructure can further improve the safety and cost-effectiveness of relocated regions. As the program progresses and new data becomes available, populations residing in hazardous regions can be relocated to newly identified safer regions, enforcing a dynamic risk control approach. |
| Incentive Risk    | To address mispricing or inadequate incentives, comprehensive modeling and pooled incentives be employed. Personalized incentives based on individual factors can reduce costs and improve the willingness to relocate. Collective incentive funds can also increase purchasing power through economies of scale, making the use of allocated incentives more effective. |

### **Sensitivity Analysis**

To understand the impact of uncertainty and favourable/unfavourable conditions, we imbue moderate increases and decreases to our assumptions and observe the effects on final projection figures. We have chosen to only test the baseline scenario SSP2 as these impacts are shown to be similar across different scenarios. The results of our testing on total costs are detailed below: 
<br>

**Inflation/interest rates:** Inflation and yields are tested separately, where short and long-term rates are changed by 1%. Note that inflation and yields are directly and inversely related to program costs respectively, due to the cost and investment nature such rates. Such changes have a minor/moderate impact on short and long-term costs respectively and does not undermine the program goals. As such, the severity posed by macroeconomic risk is reasonable.  

**Relocation rates:** Rates of individuals leaving a region are simultaneously increased or decreased by 1% to analyse relocation risk. Changing these rates have a major impact, driven by large voluntary cost changes of up to 51.83%, due to relocations incurring incentive costs. Voluntary costs make up 28 - 62% of total cost in these scenarios, leading to this observation. We note this deviation is lower in the long-term, primarily as migration falls towards the scheme end. As such, relocation risk has a high severity particularly in the short-term and will require monitoring. 

**Incentives:** Altering incentives for migrations to regions 2, 4 and 6 has a major impact in both the short and long-time horizons, with the magnitude of change ranging from 20% to 25%.  Note that this acts to only increase/decrease voluntary costs by 50% which is a large proportion of the total, with displacement costs being unaffected. Therefore, the viability of incentives needs strong levels of further monitoring and calibration to manage incentive risk.  

**Contents/weather inflation:** changes in conditions produce moderate changes to displacement costs of around 14% and 20% respectively. As this does not impact voluntary displacement costs driven by incentives, the overall effect is minor from both a short and long-term perspective. This suggests the risk higher severities arising overtime is overall low. 

### **Certainty of Program Objectives**

A key objective when designing this relocation insurance program was to implement a voluntary relocation program that would reduce the relocation costs arising from climate-related displacement. As discussed in Section 3, the projected displacement costs do decrease significantly for both the short-term and long-term horizons considered. Using the simulation data, it can be shown through CLT calculations that given our distributional assumptions this will occur with a greater than 99.99% confidence level across all the scenarios. This satisfies the high certainty requirement of this objective. The CLT calculations discussed are showcased in detail in the Appendix Part E.  

The secondary key objective was to ensure that the total yearly costs of the program (displacement and voluntary costs) would be less than 10% of yearly GDP. Through our simulations, we implemented automatic checks which would count the number of times this condition was satisfied. By averaging the proportion of times this check was satisfied across all the simulations, we were able to show a greater than 99.99% confidence level that this constraint would be satisfied in any given year across all the scenarios. This also satisfies the high certainty requirement of this objective. 

## **Data and Data Limitations**

(TODO)