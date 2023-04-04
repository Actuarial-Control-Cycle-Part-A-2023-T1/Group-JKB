[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-8d59dc4de5201274e310e4c54b9627a8934c3b88527886e3b421487c677d23eb.svg)](https://classroom.github.com/a/elzutNYu)
[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-f4981d0f882b2a3f0472912d15f9806d57e124e0fc890972558857b51b24a6f9.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=10667393)
# Actuarial Theory and Practice A @ UNSW

_"Tell me and I forget. Teach me and I remember. Involve me and I learn" - Benjamin Franklin_

---

### Congrats on completing the [2023 SOA Research Challenge](https://www.soa.org/research/opportunities/2023-student-research-case-study-challenge/)!

>Now it's time to build your own website to showcase your work.  
>To create a website on GitHub Pages to showcase your work is very easy.

This is written in markdown language. 
>
* Click [link](https://classroom.github.com/a/elzutNYu) to accept your group assignment.


#### Follow the [guide doc](Doc1.pdf) to submit your work. 
---
>Be creative! Feel free to link to embed your [data](hazard-event-data.csv), [code](sample-data-clean.ipynb), [image](unsw.png) here

More information on GitHub Pages can be found [here](https://pages.github.com/)
![](Actuarial.gif)


(Start of page)

[![2023 SOA Case Study](https://www.soa.org/research/opportunities/2023-student-research-case-study-challenge/)](https://classroom.github.com/a/elzutNYu)
[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-f4981d0f882b2a3f0472912d15f9806d57e124e0fc890972558857b51b24a6f9.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=10667393)

# [2023 Student Research Case Study Challenge](/): Relocation Social Insurance 
## UNSW x SOA sponsored by Valani Global
![alt text](logos.png "UNSW, SOA & Valani Global logos")
>
## Group JKB Consulting Report

(add something about the purpose of this page, links to code and report)


---

### Page Navigation
>
>[Executive Summary](https://github.com/Actuarial-Control-Cycle-Part-A-2023-T1/Group-JKB/blob/main/README.md#executive-summary)
>
>[Objectives](https://github.com/Actuarial-Control-Cycle-Part-A-2023-T1/Group-JKB/blob/main/README.md#objectives)
>
>[Program Design](https://github.com/Actuarial-Control-Cycle-Part-A-2023-T1/Group-JKB/blob/main/README.md#program-design)
>
>[Pricing and Costs](https://github.com/Actuarial-Control-Cycle-Part-A-2023-T1/Group-JKB/blob/main/README.md#pricing-and-costs)
>
>[Assumptions](https://github.com/Actuarial-Control-Cycle-Part-A-2023-T1/Group-JKB/blob/main/README.md#assumptions)
>
>[Risk and Risk Mitigation Strategies](https://github.com/Actuarial-Control-Cycle-Part-A-2023-T1/Group-JKB/blob/main/README.md#risk-and-risk-mitigation-strategies)
>
>[Data and Data Limitations](https://github.com/Actuarial-Control-Cycle-Part-A-2023-T1/Group-JKB/blob/main/README.md#data-and-data-limitations)
>
>[Conclusion/Recommendations](https://github.com/Actuarial-Control-Cycle-Part-A-2023-T1/Group-JKB/blob/main/README.md#conclusionrecommendations)
>
>[References](https://github.com/Actuarial-Control-Cycle-Part-A-2023-T1/Group-JKB/blob/main/README.md#references)

---

## Executive Summary

This report was composed to design and evaluate a social insurance program to assist Storslysia in mitigating displacement risk as a result of climate-related hazard events. The program design specifies claim coverage of 30% of household goods and 12 months of temporary housing, as well as incentives such as buybacks and grants to provide opportunities for voluntary relocation to lower risk regions. Projections of economic costs over short- and long-term time frames with and without the proposed insurance program found that the scheme was able to reduce displacement costs with a high degree of certainty in the long-term under all climate scenarios. The economic capital needed would be at least φ 300 billion each year to remain solvent, but the scheme remains within 10% of GDP with 97.5% confidence. Moreover, the key risks were assessed through both qualitative and quantitative risk analyses, with suggested mitigation strategies. The report concludes with a recommendation of how to proceed with the implementation of the program regarding the analyses performed. 

## Objectives

The goal of this social insurance program is to manage the financial risks associated with catastrophe-related displacement in Storslysia. To this end, the program aims to encourage proactive relocation which lowers damage risk and comes at a lower cost than involuntary displacement. This scheme will cover the entire population of Storslysia. As well as reducing long-term costs from climate-related disasters regardless of future emissions scenarios, this scheme will provide financial support to Storslysia citizens affected by such disasters. This program will be equitable in its design such that very affluent households are not advantaged by the scheme any more than lower or middle-class households. Keeping the costs arising from relocation from exceeding 10% of GDP each year with a high degree of certainty is the aim of this program. 

The following key metrics will be used to monitor the social insurance program:
>
| Metric                                               | Frequency                                             |
| ---------------------------------------------------- | ---------------------------------------------------- |
| Compare costs with and without the scheme            | Annually for the first 10 years, then every 3 years |
| Number of people who voluntarily relocated each year | Annually                                             |
| Cost as a percentage of GDP                          | Annually                                             |
| Value at risk                                        | Annually                                             |


## Program Design
In our program, all citizens of Storslysia will be covered for displacement costs after a climate catastrophe. However, we will distinguish between support for households who are voluntarily relocating and households who are involuntary relocating due to a natural disaster. We also distinguish between renters and owner-occupiers. 

### Requirements to make a claim
All households, regardless of region, are entitled to financial support for temporary housing, rebuilding their property and household-goods replacement costs. For households in regions 2, 4, 5 and 6, additional support is provided contingent upon that household relocating to regions 1 or 3, the lower risk regions. (See Appendix Table 2.1 for justification of which regions are high and low risk).
To be eligible for voluntary relocation support, a household in a highly affected region (regions 2, 4, 5 and 6) may apply for financial assistance to relocate their household to a safer region (regions 1 or 3). Both renters and owner-occupiers in highly affected regions are eligible for this support. 
To be eligible for involuntary relocation support, a household must be affected by a severe weather event, causing irrecoverable damage to the home such that it is no longer fit for living. 

### Program coverage
Support for all households with uninhabitable homes affected by the natural disaster, regardless of the region, include the following:

* Up to 30% of housing costs will be paid out to replace household goods.
* Up to 30% of the median value of houses in that region.
* Temporary housing in the affected region is provided for 12 months.
>
In addition, the following benefits are included as a part of the program to assist with relocation:

|                                  | Voluntary relocation                                                            | Involuntary relocation                                                                              | 
| -------------------------------- | ------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| Owner-occupiers (Region 2,4,5,6) | Pay for construction of new home (up to median value) + lump-sum of φ 10,000 | Buy back uninhabitable homes (up to median value) provided the household moves to a low-risk region |
| Renters (Region 2,4,5,6)         | Pay for home rental costs for 6 months (up to median rent)                      | Pay for home rental costs for 2 months in the new region (up to the median rent)               |

(Karen: didn't include the wordy reasoning sections, they can see the report for that)

## Pricing and Costs
(Karen: still thinking about the best way to present this section in a concise but engaging manner)
### Short-term projections

#### Economic costs

|                      | Mean Estimates | Upper Bound (97.5%) |
| -------------------- | -------------: | ------------------: |
| Property Damage      | φ 255,15,548   | φ 9,637,762,244     |
| Displacement Costs   | φ 581,450,888  | φ 25,738,567,833    |
| Total Economic Costs | φ 836,566,436  | φ 35,376,330,076    |

#### Program costs

|                            | Mean Estimates   | Upper Bound (97.5%) |
| -------------------------- | ---------------: | ------------------: |
| Property Damage            | φ 255,15,548     | φ 9,637,762,244     |
| Displacement Costs         | φ 581,450,888    | φ 25,738,567,833    |
| Relocation Incentive Costs | φ 12,310,238,772 | φ 12,310,238,772    |
| *Voluntary Costs*          | φ 12,254,805,736 | φ 12,254,805,736    |
| *Involuntary Costs*        | φ 55,433,035     | φ 55,433,035        |
| Total Economic Costs       | φ 836,566,436    | φ 35,376,330,076    |

### Long-term projections

#### Program costs

|                            | Mean Estimates   | Upper Bound (97.5%) |
| -------------------------- | ---------------: | ------------------: |
| Property Damage            | φ 206,962,717    | φ 8,570,367,393     |
| Displacement Costs         | φ 473,142,809    | φ 22,892,334,372    |
| Relocation Incentive Costs | φ 51,065,396     | φ 51,065,396        |
| *Voluntary Costs*          | φ 174,906        | φ 174,906           |
| *Involuntary Costs*        | φ 50,890,490     | φ 50,890,490        |
| Total Economic Costs       | φ 731,170,922    | φ 31,513,768,160    |

### Capital and solvency requirements


## Assumptions
Assumptions within the modelling process, economic climate and validity of the utilised datasets were required to ensure the program generated accurate and reliable results. A summary of all the assumptions used can be seen in the table below.
>
(table from report - either screenshot or create a table)

(Karen: didn't include the wordy explanations)

## Risk and Risk Mitigation Strategies
(risk matrix from report)

### Key risks and mitigation strategies
When a project is underway, unexpected factors have the potential to affect the success of a project, and thus proactive identification, assessment and action improves the chance of success in meeting project objectives (Hillson, David 2014). The risk matrix (right) illuminates the key areas of risk present within the scheme:
>
(table from report - create a table but summarise text even further?)

### Sensitivity analysis
The sensitivity analysis is performed using the Shared Socioeconomic Pathways (SSPs) carbon emissions scenario forecasts (see Appendix Table 3.2). The projected log values of the long-term economic costs without the program are shown in the graph below. Under the best scenario (SSP1) where the world shifts to become greener and more sustainable, then the costs of climate-related disasters can be reduced below current (2020) levels. However, in the other 3 scenarios of higher carbon emissions, the economic cost will only continue to increase in the future. In the most severe scenario (SSP5), the average economic cost could increase up to 17-fold by 2150.

### Certainty of cost estimates
Under the proposed program, there is a 97.5% confidence that costs will not exceed 10% of Storslysia’s GDP in any given year as seen in the graph below. The solid lines represent the scheme cost and dashed lines represent 10% of GDP, each under the four SSP scenarios. The real GDP is modelled assuming no population growth and only increases in GDP per capita. While the scheme does not exceed 10% of GDP between now and 2100, there is the possibility it may exceed this level after 2100, particularly in the SSP5 scenario. This means that the program and underlying model assumptions must be assessed in the future to ensure it remains sustainable beyond around 80 years.
>
(graph from report)

Given constant claims (no adjusting for climate scenarios), the scheme is expected to have a negative economic benefit for 26 years. After this, the scheme delivers benefits increasing to $110 million in reduced damage and displacement costs per year. Under higher claims scenarios, the economic benefits of the scheme increase: 
>
* Under the SSP2 scenario and the mean claims predicted, the scheme delivers positive economic benefits within 20 years reaching $180 million per year by 2065  
* Under the severe claims (97.5th percentile) and SSP3 scenario, the scheme delivers economic benefits within 10 years, which can reach almost $10 billion per year (see Appendix Table 6.1 and 6.2)
>
The success of the scheme depends on the take-up of the voluntary relocation program, the main driver of reduced risks and reduced damage and associated costs. Secondary research suggested that between 15-20% of people would consider relocating to be away from high-risk areas without any additional financial incentive; hence, our 20% estimate of voluntary relocation is rather conservative, and take-up may be even higher (Yazzie R. 2021). 


## Data and Data Limitations

### Data Sources
In addition to the Storlysia-specific data – housing and demographic information, historical weather-related hazards data and macroeconomic data – external data from the ABS was also utilized to inform the modelling process.

### Limitations of provided data
There are inherent data limitations which inhibit the predictive capacity of the program and hence reliability. Operational risks as a result of human error when inputting, duplicate or missing values and one-off extreme values in historical data (e.g. inflation values in 2003) have impacts in the training of the model. To overcome these limitations, interpolation via linear or geometric means using surrounding data was utilised where appropriate. The rationale for this was due to calibrate the model without the influence of severe outliers.

### Limitations when utilising data
The inability of historical data to perfectly capture population movements and account for unique situations within the future also presents a limitation in the modelling process, thereby limiting the accuracy of our program analysis. This is especially prevalent within the climate modelling area which has seen impacts in frequency and severity exacerbated by climate change. Compilation of data and the period of impacts has also presented a limitation as hazard event data only accounts for property damage (and does not distinguish between household goods, and material and labour costs) which is recognized and measured in days (duration). More precise calculations of property damage as well as duration of the hazard event would thus increase the predictive capacity of the models, as well as more data points to train the frequency and severity models. 


## Conclusion/Recommendations
In conclusion, the proposed social insurance scheme can help Storslysia mitigate their climate-related displacement risk while remaining under 10% GDP with a high level of confidence. After extensive analysis on the impact of the social insurance program over short and long-term timeframes and under different climate scenarios, the improved financial and social benefits associated with the scheme provide substantial evidence that the project should be employed given our assumptions. Although there are risk mitigation analysis and monitoring protocols incorporated within the program design of the scheme, it is quintessential to verify the plausibility of assumptions to ensure the validity and success of the scheme in achieving its objective to manage the financial risks associated with catastrophe-related displacement in Storslysia. The viability and strategy of financing the scheme must also be considered. 

## References
>
* Australian Bureau of Statistics, 4102.0 -  Australian Social Trends, Dec 2011, Commonwealth of Australia, last accessed 21st March 2023, < https://www.abs.gov.au/AUSSTATS/abs@.nsf/Lookup/4102.0Main+Features10Dec+2011>
* C, S. (2017) Social Insurance: Meaning and Features | Poverty|Economics, last accessed 18th March 2023,  <https://www.economicsdiscussion.net/social-insurance/social-insurance-meaning-and-features-poverty-economics/29305>
* College of Vocational Studies, Meaning of Social Insurance Features of Social Insurance, Last accessed 21st March 2023, < https://www.cvs.edu.in/upload/Social%20insurance%20-%20feature%20and%20need.pdf>
* Department of Regional NSW, Northern Rivers Reconstruction Corporation (2022) Northern Rivers’ voluntary home buy backs to start, last accessed 19th March 2023 <https://www.nsw.gov.au/media-releases/northern-rivers-voluntary-home-buy-backs-to-start>
* Deryugina, T. (2022), Economic effects of natural disasters, IZA World of Labor, last accessed 22nd March 2023, <IZA World of Labor - Economic effects of natural disasters >
* Greer, A., Trainor, J. and McNeil, S. (2019) “Voluntary Household Relocation Decision Making in the Wake of Disaster: Re-interpreting the Empirical Record,” International Journal of Mass Emergencies and Disasters, 37(2), pp. 197–226, last accessed 18th March 2023, <https://doi.org/10.1177/028072701903700206>
* King D., Bird D., Haynes K., Boon, H., Cottrell A., Millar J., Okada T., Box P., Keogh D., Thomas M. 2014, Voluntary Relocation as an adaption strategy to extreme weather events, International Journal of Disaster Reduction, last accessed 20th March 2023, < https://www.csu.edu.au/__data/assets/pdf_file/0009/1801764/Voluntary-relocation-King-et-al.pdf>
* OECD (2019), Monitoring and Evaluating social protection systems, last accessed 21st March 2023, <https://www.oecd.org/dev/inclusive-societies-development/Lessons_learned_M-E.pdf>
* Our World in Data., Data Explorer: IPCC Scenarios, last accessed 23rd March 2023, <Data Explorer: IPCC Scenarios - Our World in Data > 
* Risk.net, Solvency Capital requirement (SCR), last accessed 23rd March 2023, <Solvency capital requirement (SCR) definition - Risk.net>
* Seong K., Losey C. (2020), To Remain or Relocate? Mobility Decisions of Homeowners Exposed to Recurrent Hurricanes, last accessed 20th March 2023, <https://hazards.colorado.edu/quick-response-report/to-remain-or-relocate-mobility-decisions-of-homeowners-exposed-to-recurrent-hurricanes>
* Yazzie R. (2021), How Long Does It Take to Build a House: Is It Worth The Wait, Better Homes and Gardens Real Estate, last accessed 19th March 2023, < https://www.homecity.com/blog/how-long-does-it-take-to-build-a-house/#:~:text=The%20average%20new%20home%20building,home%2C%20and%20the%20final%20walkthrough>

