# voting-data-general-election-MD-2016
## Background Information
I was interested in looking at data from the 2016 general election and focused on counties in Maryland in particular. I was curious if there were any "categories" of counties that shared similar voting characteristics, and how these different "types" of counties may differ across party lines. Raw data was downloaded from the [Maryland State Board of Elections](https://elections.maryland.gov/elections/2016/index.html).

Please note that the raw data abbreviated a few variables as "POLLS, "EV," "ABS," and "PROV." There was no description on the site explaining what each of these represented, so I made the assumption that "POLLS" refers to the amount of polling sites, "EV" refers to early voting numbers, "ABS" refers to absentee ballots cast, and "PROV" refers to provisional ballots cast. The other variables, such as "TURNOUT" or "ELIGIBLE_VOTERS," were self-explanatory by nature. 

### Business Question
How do voting characteristics/tendencies change across counties in Maryland, and are there ways to categorize counties by characteristic? If so, how?

## Data Analysis

### Data Sources
[General Election_Raw Data.xlsx](https://github.com/viv-sun/voting-data-general-election-MD-2016/blob/main/General%20Election_Raw%20Data.xlsx) shows the raw data as downloaded from the Maryland State Board of Elections.

[General Election_Consolidated and Filtered Data.xlsx](https://github.com/viv-sun/voting-data-general-election-MD-2016/blob/main/General%20Election_Consolidated%20and%20Filtered%20Data.xlsx) shows the filtered and consolidated data, which was then converted into chart format as well. Charts are available in this workbook, as well as via stand-alone files in .jpg format (please see the __Charts__ section below).

[Instructions for Clustering.docx](https://github.com/viv-sun/voting-data-general-election-MD-2016/blob/main/Instructions%20for%20Clustering.docx) contains instructions on how I gathered the raw data, filtered it, and analyzed it.

### Clusters

__Statewide Clusters__
![alt text](https://github.com/viv-sun/voting-data-general-election-MD-2016/blob/main/cluster_statewide.jpg)

The five county clusters for all voters in MD are Calvert County, Baltimore City, Allegany County, Baltimore County, and Montgomery County.

Calvert County features a below average number of polls, amount of early voting, absentee ballots, and provisional ballots filled out. It also has a below average eligibility, but a slightly above average voter turnout. 

Baltimore City features an above average amount of polls, amount of absentee ballots used, and amount of eligible voters. It has a high amount  of provisional ballots. It has a slightly below average amount of early voting, but has very low voter turnout. 

Allegany County has slightly below average amounts for every variable.

Baltimore County features a very high amount of polls, slightly above average amount of early voting, and slightly below average voter turnout. It has a high usage of absentee ballots and provisional ballots; it also has a higher than average voter eligibility.

Montgomery County has many polls, above average early voting rates, and slightly below average voter turnout. It has a very high usage of absentee ballots and provisional ballots, and higher than average voter eligibility.

__Democrat Clusters__
![alt text](https://github.com/viv-sun/voting-data-general-election-MD-2016/blob/main/cluster_democrat.jpg)

The five county clusters for Democrats in MD are Harford County, Baltimore County, Queen Anne's County, Prince George's County, and Anne Arundel County. 

Harford County has slightly below average poll locations, early voting rates, absentee ballot usage, provisional ballot usage, and amount of eligible voters. However, it has slightly above average voter turnout. 

Baltimore County has a very high, above average amount of poll locations, amount of eligible voters, and early voting rates. It has an above average absentee and provisional ballot usage, and average voter turnout.

Queen Anne's County has a below average amount of poll locations, early voting rates, absentee ballot usage rate, provisional ballot usage rate, and amount of elibible voters. It has a slightly above average voter turnout. 

Prince George's County has a very high, above average amount of poll locations, early voting rates, absentee ballot usage rate, provisional ballot usage rate, and amount of eligible voters. It has slightly below average voter turnout. 

Anne Arundel County has a slightly above average amount of polls, early voting rate, absentee ballot usage rate, provisional ballot usage rate, and amount of eligible voters. It has an average voter turnout. 


__Republican Clusters__
![alt text](https://github.com/viv-sun/voting-data-general-election-MD-2016/blob/main/cluster_republican.jpg)

The five county clusters for Republicans in MD are Frederick County, Montgomery County, Kent County, Saint Mary's County, and Cecil County.

Frederick County has above average amount of poll locations, eligible voters, and voter turnout. It has a slightly above average early voting rate and usage of absentee and provisional ballots.

Montgomery County has a very high, above average amount of polls and early voting rate. It has even higher absentee provisional ballot usage rate and amount of eligible voters. It has a below average voter turnout. 

Kent County has below average values (almost one standard deviation) for all variables. 

Saint Mary's County has slightly below average values for all variables. 

Cecil County has slightly below average values for all variables. 


__Unaffiliated Clusters__
![alt text](https://github.com/viv-sun/voting-data-general-election-MD-2016/blob/main/cluster_unaffiliated.jpg)

The five county clusters for unaffiliated voters in MD are Prince George's County, Montgomery County, Charles County, Frederick County, and Caroline County.

Prince George's County has above average amount of polls, early voting rates, absentee and provisional ballot usage, and voter eligibility. It has below average voter turnout. 

Montgomery County has a very high above average amount of polls, early voting rates, usage of absentee and provisional ballots, and voter eligibility. It has slightly above average voter turnout.

Charles County has below average values for all variables.

Frederick County has slightly above average values for all variables save for voter turnout, which is above average. 

Caroline County has below average values for all variables.

### Overall Cluster Conclusions

Overall, the overlaps in clusters tell us that Montgomery County is a cluster point for statewide voters, Republicans, and unaffiliated voters. 

Baltimore County is a cluster for overall statewide voters and Democrats. 

Prince George's County is a cluster for Democrats and unaffiliated voters (maybe left-leaning?). 

Frederick County and Montgomery County are clusters for Republicans and unaffiliated voters (maybe right-leaning?).


### Charts
Please keep in mind that the Statewide data in each chart is organized from smallest to largest. 

![alt text](https://github.com/viv-sun/voting-data-general-election-MD-2016/blob/main/chart_eligible%20voters.jpg) 
Maryland is a predominantly blue state, so it is no surprise that there are many more registered Democrat eligible voters than Republican or unaffiliated voters. 

![alt text](https://github.com/viv-sun/voting-data-general-election-MD-2016/blob/main/chart_absentee%20ballots.jpg)

![alt text](https://github.com/viv-sun/voting-data-general-election-MD-2016/blob/main/chart_early%20voting.jpg) 

![alt text](https://github.com/viv-sun/voting-data-general-election-MD-2016/blob/main/chart_provisional%20ballots.jpg)

![alt text](https://github.com/viv-sun/voting-data-general-election-MD-2016/blob/main/chart_voter%20turnout.jpg)

Overall, Democrats seem to have (in sheer numbers) the majority in early voting, as well as with casting absentee ballots and provisional ballots. Interestingly, Republicans have a higher percentage voter turnout than Democrats do. 

## Summary

Moving forward, because Democrats are the majority and Republicans/unaffiliated voters are the minority, I would like to recreate the charts with percentages (as in the case of the __Voter Turnout__ chart) to more accurately and easily compare data. I am also interested in looking at/including additional variables in the analysis. These variables (perhaps obtained from Opportunity Atlas) would include high school graduation rate, average income level, ethnic/racial makeup of the population in a county, etc. to see if there is any relationship between community factors and election results. Certain demographics tend to vote a certain way and it would be interesting to see if the Maryland voters also follow these precedents/how that voting preference might affect the clusters, especially for counties that are clusters for more than one category (ex: Democrats and unaffiliated voters sharing a county as a cluster point). 

With the extra variables mentioned above, we could gain a more holistic and in-depth view of each county. This could inform methods to increase voter access, such as increasing the amount of polling locations in certain counties or identifying ways to increase voter turnout at the polls on election day. For example, in counties where a non-English language is also prevalent, perhaps voting materials could be distributed in a second language to encourage eligible voters to vote. It could also help election candidates determine how to tailor their campaigns for the local population (if applicable). 
