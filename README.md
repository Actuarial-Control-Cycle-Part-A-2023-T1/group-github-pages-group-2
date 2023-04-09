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

## **Region Analysis**

After estimating the relocation cost per capita from the historical data, it then became important to understand which regions would be considered high risk and low risk to inform the decision making for our voluntary relocation program. 

The historical data was collated into a 10-year moving average time series observing the relocation cost per capita for each year inflated to 2020. Additionally, the frequency and severity cost per capita values were tabulated in table 7b to indicate the quantitative risk for each region across the 1960-2020 historical period.

(add visual)

(add table)

From the table and chart above, we can breakdown the regions into the following categories:
* Regions 1 and 3 are **Low** risk. They have the lowest cost per capita at Ꝕ4.48 and Ꝕ10.00 respectively.
* Regions 2, 4 and 6 are **High** risk. It has the highest cost per capita at Ꝕ39.36, Ꝕ33.00 and Ꝕ25.12 respectively.
* Regions 5 is difficult to categorize into a low-risk or a high-risk category. It has a reasonably high cost per capita at Ꝕ25.12, but this is largely driven by a large major event that occurred in 1989.

Because of these findings, we have decided on the following goals for our voluntary relocation program.
* Our Program will seek to relocate individuals from region 2, 4 and 6 which are deemed high-risk to regions 1 and 3 which are deemed low risk.
* The program will specifically focus on relocating citizens from region 2. This is because region 2 has the highest cost per capita out of all the high-risk regions and has a relatively high population of 4,993,764 citizens. 
* Due to region 1 and 3’s similar cost per capita, we will not favor one region over the other for relocation choice.

## **Key Assumptions**

### **Macroeconomic Assumptions**

* Inflation: Short term inflation of 3.85% in 2023 is assumed which linearly transitions to a 
long-term baseline at 2.00%. Scenario loadings are applied for the long-term rate.
* Risk-free yields: short term risk-free rates are assumed at 0.79% in 2023 which linearly 
transition to a long-term baseline at 2.50%. Scenario loadings are applied for the long-term rate.
* Historical Population Growth Rate: from years 1960-2020, we assumed that population 
grew at a rate of 0.85% yearly. This was selected based on the projected population 
growth rates for future years provided.

### **Relocation Assumptions**

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

### **Yearly Incentives**

Incentive amounts are fixed for each region throughout the program’s timeframe. This is done 
to simplify calculations. To see the assumed yearly incentives. The value of 
these incentives directly influences the costs of the program, as a result, they have a significant 
impact on the projected costs.

### **Distribution Assumptions**

* Relocation severity for each hazard event classification (minor, medium or major) is 
assumed to be constant and equal to the estimate based on historical values, with only 
inflation indexing. This is a significant assumption that would impact the variability of 
our total claim cost.
* Hazard event frequency is assumed to follow a Poisson distribution and grows as per the 
projection model provided. Poisson is a natural distribution to use for count data and is 
common practice in the insurance industry.

## **Methedology for Relocation Cost Calculations**

The historical hazard data contained hazard data from years 1960-2020 which contained the specifics of every natural hazard event that took place. For each hazard event the following damages were recorded, the property damage, the number of injuries and the number of fatalities. Using these variables, we constructed a relocation cost variable that represents the amount the program would have paid out in relocation claims. The calculations are given below:

**Contents Damage**
:This was calculated as a percentage of the property damage. The parameter value that was decided on was 60%.

**Temporary Housing Costs**
:This cost was estimated on a per Ꝕ of property damage basis. The calculation of this cost is given by:
* Calculating the mean property value for each region. This was done using the distribution of property values that was given to us in the demographic data.
* $\text{Number of households impacted per Ꝕ of damage} = \frac{1}{\text{Region Mean Property Value}}$
* $\text{Number of people impacted per Ꝕ of damage} = \text{Number of households impacted per Ꝕ of damage} \times \text{Number of People per Household}$
* $\text{Temporary housing cost per month per Ꝕ of damage} = \text{Number of people impacted per Ꝕ damage} \times \text{Regions Temporary Housing Cost per month per person}$
* $\text{Temporary Housing cost per Ꝕ of damage} = \text{Temporary housing cost per month per Ꝕ of damage} \times \text{Assumed length of building reconstruction}$
* This was then deflated back to 2020 Ꝕ values.

**Medical Costs**: 
This was estimated as a cost per injury in 2020 Ꝕ values. The calculation is given by:
* We started with the *Total health care and social assistance receipts/revenue 2017* statistic given in the demographic data. We see this as a strong representation of the total amount spent on medical fees for 2017.
* $\text{Health Care Costs per capita 2017} = \frac{\text{Total health care and social assistance receipts/revenue 2017}}{\text{2017 Population}}$
* The Health Care Costs per capita 2017 was then inflated to represent the Health Care per Capita in 2020 Ꝕ.
* $\text{Medical Cost for Injury 2020} = \text{assumed length of injury recovery} \times \text{Health Care Costs per Capita 2020}$.

**Workers Compensation for Injury Costs**: 
This was estimated as a cost per injury in 2020 Ꝕ values. The calculation is given by:
* Starting with the *Prior Year per Capita Income* statistic given in the demographic data. It was assumed that this was referring to the 2022 per Capita Income.
* This value was then deflated to 2020 Ꝕs. 
* $\text{Workers Compensation Cost for Injury 2020} = \text{Assumed length of injury recovery} \times \text{2020 per Capita Income}$.

With these calculations, the minor, medium and major event frequencies and severities for 2020 can then be calculated using the relocation cost per capita.

## **Relocation Model**

A significant motivation of this program is the reduction in climate-related displacement costs throughout Storylsia. The way that Storslysia’s task force has asked this to be implemented is through a voluntary relocation program where an incentive is offered for those who voluntarily decide to move to low-risk regions we decide.

This was achieved by implementing a population model which allows for the relocation of the population every year. This population model assumes the following:

* Citizens are allowed to relocate at the start of the year.
* This relocation is independent of other factors of the model. 
* The relocation rates are constant and do not change throughout the projected timeframe. 
* The population still grows as described by the SSP projected population growth rates.

The relocation model is run using a deterministic transition rate matrix as described by table 7b. The row of the matrix corresponds to where the individual is relocating from while the column corresponds to the region that individual wants to relocate to. These rates are applied on a yearly basis.

(insert matrix)

As described in Part B of the Appendix, the aim of the program is to relocate citizens from regions 2, 4 and 6 towards regions 1 and 3. For regions 4 and 6, we have assumed a 2% relocation rate while region 2 has a doubled assumed relocation rate of 4%. 

The rates were chosen through mainly experimentation. The rates are meant to reflect an optimal relocation rate that achieves a balance between lowering displacement costs, while still being a reasonable amount of relocation for the government to achieve.  Additionally, the doubled relocation rate for region 2 is justified due to the increased emphasis on region 2 in the program design from section 2. Region 2 is getting double the incentive of region 4 and 6 and hence a double relocation rate would be in alignment with that program specification. 

## **Pricing and Costs**

### **Cost Projections**

The short-term and long-term costs were simulated using the SSP frequency projections combined with the 2020 severity estimates. 500 simulations were run, in order to obtain the benefit of the LLN (Law of Large Numbers) where we could conduct CLT (Central Limit Theorem) hypothesis tests and accurately estimate the upper quantiles of our total cost distribution for solvency capital reasons. The simulation results are described in the table and visuals below.

(Add Table)

(Add Visuals)

By comparing the cost projections, we can see that the program decreases the mean displacement cost. This is expected as the program will influence people to relocate from Storslysia’s high risk regions to lower risk regions. We have confidence that this will occur with a greater than 99.99% confidence level from our CLT calculations. This satisfies the high degree of confidence required by our program goals.

We can also see that the relative displacement cost of the program, in comparison to without the program decreases with a longer time horizon. This is intuitive as the longer the time horizon, the more relocated the population will be away from high-risk regions to low-risk regions. The implication is that the voluntary relocation program will not significantly decrease costs in the short term but lead to strong cost decreases for longer time horizons. This should be considered in the programs monitoring processes.

### **Solvency Capital for Total Cost**

To cover the displacement costs arising from climate-catastrophe related disasters and provide incentive packages to relocating citizens, Storslysia will need to hold a certain amount of capital in the short term to remain solvent which is known as the solvency capital. The mean total cost would not be sufficient as there is a significant chance that the total cost will be greater than the mean. To determine an appropriate solvency capital, the approximate distribution of the total cost needs to be simulated. The distribution of the simulated total cost over a 5-year time horizon for each scenario can be observed below:

(add visuals)

For our solvency capital, we will be using the figures calculated from the Value at Risk and Conditional Value at Risk at a 99.5% level looking at a 5-year time horizon. These are tabulated for each scenario below:

(Add Table)

Since CVaR represents the mean of the losses above the VaR, it is a more conservative estimate for the solvency capital. Additionally, CVaR is more commonly used in practice for insurance solvency requirements and consequently it will be used.

Based on the different emissions scenarios, we get various estimates as to what this solvency capital could be. Since this report does not explore the likelihood of any of these scenarios, we will assume a solvency capital figure that is the equal weighted average of these four scenarios. Hence our final 5-year solvency capital that we recommend for the program is Ꝕ10,486 m.

### **Voluntary Costs vs Emergency Displacement Costs**

With the given program design discussed above, the contrast between the voluntary and displacement costs can be observed from the expected yearly and cumulative line charts below. For simplicity, we have only considered SSP2 as similar behavior is shown across all the scenarios:

(add visuals)

During the initial years of the program, we can observe that there is a higher proportion of voluntary costs in comparison to displacement costs. This is intuitive for two main reasons.

Firstly, due to our constant relocation rates, there is higher amounts of relocation toward the start of the program leading to more incentive payments being paid. Additionally, in the short term, the population is in the process of relocating to lower risk regions. This implies that the cost savings from the relocation program haven’t fully developed yet.

As the program develops, the voluntary costs significantly decrease as the population is significantly relocated and there are fewer people in high-risk regions. Despite this relocation, the displacement costs continue to steadily increase as the frequency of climate disasters continue to rise, according to the SSP2 disaster frequency projection. As a result, the proportion of voluntary costs to displacement costs decreases as the program develops.

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

| **Key Risks**     | **Mitigation Strategies** |
| :---------------- | :----------- |
| Climate Change    | Conservative margins used in assumptions setting, including value of contents and weather inflation, implicitly builds in an allowance for severity related cost increases. Ongoing repricing and monitoring of the suitability of hazard assumptions will further allow the program to adapt to evolving climate-related costs. |
| Interest/Inflation    | Strategies such as duration matching, and capital modelling can ensure future cash-flows are not adversely affected through interest rate risk. Investment in higher growth assets can also help accumulate capital and make up for future shortfalls from such risks. Investing in inflation indexed assets, although costly, can additionally mitigate the impacts of heightened levels of inflation. |
| Relocation Risk    | Continual monitoring of regional hazard data is necessary in identifying ineffective hazard reduction efforts and investment in climate-resistant infrastructure can further improve the safety and cost-effectiveness of relocated regions. As the program progresses and new data becomes available, populations residing in hazardous regions can be relocated to newly identified safer regions, enforcing a dynamic risk control approach. |
| Incentive Risk    | To address mispricing or inadequate incentives, comprehensive modeling and pooled incentives be employed. Personalized incentives based on individual factors can reduce costs and improve the willingness to relocate. Collective incentive funds can also increase purchasing power through economies of scale, making the use of allocated incentives more effective. |

### **Sensitivity Analysis**

To understand the impact of uncertainty and favourable/unfavourable conditions, we imbue moderate increases and decreases to our assumptions and observe the effects on final projection figures. We have chosen to only test the baseline scenario SSP2 as these impacts are shown to be similar across different scenarios. The results of our testing on total costs are detailed below: 
<br>

<div align="center">
<img src="Screenshot 2023-04-08 171527.png"  width="550" height="300"/>
</div>

<u><b>Inflation/interest rates:</b></u> Inflation and yields are tested separately, where short and long-term rates are changed by 1%. Note that inflation and yields are directly and inversely related to program costs respectively, due to the cost and investment nature such rates. Such changes have a minor/moderate impact on short and long-term costs respectively and does not undermine the program goals. As such, the severity posed by macroeconomic risk is reasonable.  

<u><b>Relocation rates:</b></u> Rates of individuals leaving a region are simultaneously increased or decreased by 1% to analyse relocation risk. Changing these rates have a major impact, driven by large voluntary cost changes of up to 51.83%, due to relocations incurring incentive costs. Voluntary costs make up 28 - 62% of total cost in these scenarios, leading to this observation. We note this deviation is lower in the long-term, primarily as migration falls towards the scheme end. As such, relocation risk has a high severity particularly in the short-term and will require monitoring. 

<u><b>Incentives:</b></u> Altering incentives for migrations to regions 2, 4 and 6 has a major impact in both the short and long-time horizons, with the magnitude of change ranging from 20% to 25%.  Note that this acts to only increase/decrease voluntary costs by 50% which is a large proportion of the total, with displacement costs being unaffected. Therefore, the viability of incentives needs strong levels of further monitoring and calibration to manage incentive risk.  

<u><b>Contents/weather inflation:</b></u> changes in conditions produce moderate changes to displacement costs of around 14% and 20% respectively. As this does not impact voluntary displacement costs driven by incentives, the overall effect is minor from both a short and long-term perspective. This suggests the risk higher severities arising overtime is overall low. 

### **Certainty of Program Objectives**

A key objective when designing this relocation insurance program was to implement a voluntary relocation program that would reduce the relocation costs arising from climate-related displacement. As discussed in Section 3, the projected displacement costs do decrease significantly for both the short-term and long-term horizons considered. Using the simulation data, it can be shown through CLT calculations that given our distributional assumptions this will occur with a greater than 99.99% confidence level across all the scenarios. This satisfies the high certainty requirement of this objective. The CLT calculations discussed are showcased in detail in the Appendix Part E.  

The secondary key objective was to ensure that the total yearly costs of the program (displacement and voluntary costs) would be less than 10% of yearly GDP. Through our simulations, we implemented automatic checks which would count the number of times this condition was satisfied. By averaging the proportion of times this check was satisfied across all the simulations, we were able to show a greater than 99.99% confidence level that this constraint would be satisfied in any given year across all the scenarios. This also satisfies the high certainty requirement of this objective. 

## **Data and Data Limitations**

(TODO)