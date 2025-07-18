## Sanctuary Policy Exploration
**Project description:** This project investigates how local economic, demographic, and political factors relate to county-level immigration policy using data from the ILRC, U.S. Census, Bureau of Economic Analysis, and electoral outcomes. We developed predictive models to identify which factors most strongly associate with local cooperation or resistance to federal immigration enforcement. The findings offer insight into the structural patterns that may influence immigration-related policy decisions at the county level.


### 1. Introduction
#### Exploring economic and social factors around immigration acceptance and resistance

The Immigration Legal Resource Center (ILRC) was founded as Golden Gate Immigration Clinic in 1979 to face the growing need for expert assistance and training in immigration law and policy following the increasingly complex legal and social challenges immigranats were facing. The ILRC seeks to improve immigration law and policy, expand the capacity of legal service providers, and advance immigrant rights by training attorneys, paralegals, and community-based advocates who work with immigrants around the country and inform elected officials and the public to shape effective and just immigration policy and law. 

In November 2019, the ILRC published a [National Map of Local Entanglement with Ice](https://www.ilrc.org/resources/national-map-local-entanglement-ice) which assigned each county a score from 0, representing counties most engtangled, identified for spending "substancial local time and resources on civil immigration enforcement, [including those] under a 287(g) agreement", to 7, representing counties least entangled, identified for having "the most comprehensive protections to prevent local resources from going to civil immigration enforcement." There are also counties with No jail, and those with No data. 

The scores for Multnomah County, OR of a 6/7 was generated by the sum of 'Yes' to the following:
- Declines 287(g) Program: Yes
- Declines ICE detention contract: Yes
- Limits ICE holds: Yes
- Limits ICE notifications: Yes
- Limits on ICE interrogations in jail: No
- Prohibition on asking immigration status: Yes
- General Prohibition on Assistance to ICE: Yes

Each county is also annotated with comments. For example, the comments for Multnomah County are:
2015 ICE Comments: Ground Zero for detainer issues, County for Portland, OR, adjacent to Clackamas County which was subject of Miranda-Olivares. Awaiting response from County concerning future meeting on PEP. 09/28/2015 Update: Oregon USAO hosting meeting with Clackamas, Marion, Multnomah and Washington county sheriffs, district attorneys, county counsels, et.al to discuss PEP. DEAD B(6) B(7)C and AFODs B(6) B(7)C will be participating.

2017 ICE Comments: Basis of policy refined to more accurately reflect understanding of Oregon State Sheriff's Association (OSSA) position and respective Sheriff's policy as it has evolved: Does not provide foreign-born arrest information. Will allow ICE access to interview alien. Will honor 48-hour hold provision of I-247A only with criminal warrant issued by USDC. Miranda-Olivares v. Clackamas County cited as prohibiting compliance with DHS administrative detainers. Will not allow transfer of custody within secure area of facility. ORS 181A.820 cited as prohibiting transfer of custody and ongoing exchange of information including release information.

By joining the county and state policy data from the ILRC with publically available census and elected official political affiliation data, we aimed to more deeply understand how elected officials at different levels of government are associated with the variety of immigration policies.


### 2. Methods
**Assumptions**
Immigration policy is, in theory, determined by weighing the perceived costs of having someone immigrate to an area (housing shortages, marginal crime increases, etc.) over the perceived benefits of having them participate in the economy (by paying tuition, contributing to the labor market, improving demand for local consumer markets, etc.) 

**Our Approach**
We're using models to surface which factors are the strongest predictors of policy. 

Population data by the Census collected at the county level includes: county name, Foreign-born Population Estimate, Foreign-born Population Margin, Non-citizen Pop Estimate, Non-citizen Pop Margin, Lived in Different House Estimate, Lived in Different House Margin, Total Population Estimate, Total Population Margin, state, county, and the year the data was collected from 2013 to 2023. 

Economic data by [Bureau of Economic Analysis](https://www.bea.gov/data/gdp/gdp-county-metro-and-other-areas) includes the county, time period, how much a given industry contributes to the respective GDP. 

Political affiliation data includes the political affilation of the state's governor, the affiliation breakdown of the legislative branch for both the upper and lower houses where applicable, and the county results for the presidential elections since 2008 with the number of total votes cast, and the number of votes for the Democratic and Republican nominees respectively.  

**Limitations**
The identified factors indicate correlation, not causation. It would be remiss at this stage to say the polcies cause the factors, or that the factors drive the policies as a result of this study. 

### 3. Results
Coming soon! 
Reach out for updates. 


### 4. Opportunities for future research
Expanding the scope of the model to include additional metadata includes data available from the [FBI Crime Data Explorer](https://cde.ucr.cjis.gov/LATEST/webapp/#/pages/home). 

Collaborator: [Connor Warren (they/them)](https://github.com/MarcusApollo7).
For more details see [Repository](https://github.com/wu-msds-capstones/pdx-project-workbook-connor-kim-capstone).
