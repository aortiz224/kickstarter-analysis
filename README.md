# **Campaign Outcomes Analysis**

## Overview of Project 

Louise's play *Fever* came close to its fundraising goal during a short period of time. Louise has asked us to show her how other campaigns have done compared to hers. 
The following analysis shows the outcomes of comparable campaigns based on their launch dates and their funding goals.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

Based on a population of kickstarter campaigns, we identified all the **theater** campaigns that were successful, had failed, or were canceled. For this sample of kickstarters, we focused on their launch dates to identify trends. The Chart below shows the theater campaign outcomes based on their launch date: 

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/74662680/101284997-f179df80-37b0-11eb-9300-e6a6ee985498.png)

### Analysis of Outcomes Based on Goals

Based on a population of kickstarter campaigns, we identified all the **plays** campaigns that were successful, had failed, or were canceled. For this sample of kickstarters, we spread their respective funding goals based on a set of ranges to identify trends. The Chart below shows the plays campaign outcomes based on their goals:

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/74662680/101286312-c2b33780-37b7-11eb-9a86-d2bb8cec377a.png)

### Challenges and Difficulties Encountered

* I had an issue getting the images above to show based on how it was shown in the module. I used Stack Overflow to find a solution and found a Gallery Creator that helped with the process. In addition, I asked a classmate and he pointed me to a Youtube video that also showed me how to easily do it.
* On the `COUNTIFS()` formula, I added dollar signs ($) to the letters referencing the kickstarter tab and was able to drag the formula across to the 'failed' and 'canceled' columns. The only manual change was to update the 'successful' criteria.

## Results :performing_arts:

- Theater Outcomes based on Launch Date
  - Most kickstarters launch during the summer months (May through August). With this in mind, theater campaigns launched in the month of May and June have a higher likelihood of being successful. 
  - Theater campaigns launched in October are just as likely to fail as if they were launched over the summer months.
- Plays Outcomes based on Goals
  - Plays with a funding goal of over $45,000 are most likely to fail.
  - Plays with a funding goal of less than $1,000 are most likely to be successful.
  - There is, on average, a 51% chance that plays kickstarters with a funding goal of $5,000 to $24,999 will be successful, and a 49% chance that it will fail.
- Limitations of this dataset
  - The dataset does not assess outcomes based on geographical locations. It could be the case that theaters/plays may be more successful in one country over another.
  - The dataset takes a sample of all theater and plays outcomes, in addition to this, it should filter the funding goals based on the comparable goal amount that the *Fever* play had.
- Recommendations of additional tables and/or graphs
  - Line with Markers Chart showing plays outcomes based on amounts pledged.
  - Clustered Column - Line Chart showing theater outcomes by launch date with an additional filter for country.
