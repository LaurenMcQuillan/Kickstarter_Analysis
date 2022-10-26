# An Analysis of Kickstarter Campaigns

## Overview of Project

### The purpose of this analysis is to help a playwright determine how to be most successful when launching a Kickstarter campaign to fund a new play by analyzing several existing Kickstarter campaigns in the theater category and play subcategory in both the United States and Great Britain. The new Kickstarter campaign will be a United States campaign with a goal of $12,000 for a play titled Fever.

## Analysis and Challenges

### This analysis was performed by obtaining data from Kickstarter on a sample of previously conducted campaigns.  By filtering down into the data to only select the pertinent Kickstarter categories and then determining which campaigns were successful by looking at goal donations vs. pledged donations, average donations, and launch date, I was able to draw conclusions on what aspects lead to successful campaigns.

### Analysis of Outcomes Based on Launch Date

#### By focusing on the theater category and the outcomes based on Launch date, I was able to determine the best months of the year to launch a campaign.

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/115508658/198154654-4f93a77f-e9ca-4982-9add-dfcb6d2f1949.png)

### Analysis of Outcomes Based on Goals

#### By focusing on the outcomes based on goal pledged, I was able to determine which goal amounts are most and least successful.

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/115508658/198154674-9e88f5cd-d7bc-41da-ab2f-0517abd38c80.png)

### Challenges and Difficulties Encountered

#### There were some challenges with the initial dataset that had to be overcome. The data was incomplete, so I had to calculate some additional measures such as percentage funded, average donation, and year of launch. Some of the data also needed to be converted to make it more readable. I converted the Unix timestamps of the launch date and end date to standard dates as well as separated the existing category and subcategory field to determine the parent category and subcategory which allowed me to filter down into the specific dataset that is pertinent to the Fever campaign.

## Results

### Outcomes Based on Launch Date Conclusions

#### One conclusion that can be drawn based on the theater outcomes by launch date, is that the highest number of successful theater campaigns were launched in May, June, and July with May being the most successful. It would be best to launch the Fever campaign in May, followed by June and then July. Another conclusion is that the lowest number of successful theater campaigns were launched in December and November, so these launch dates should be avoided.

### Outcomes Based on Goals Conclusion

#### The conclusion that can be drawn about the outcomes based on goal is that the highest percentage of successful play campaigns had goals less than $1,000 followed closely by campaigns with goals between $1,000 and $4,999. Play campaigns with goals between $10,000 and $14,999, which is the range the Fever goal falls in, were only 54% successful. This tells me that the Fever campaign might have some challenges in meeting the goal donations.

### Limitations of the Dataset

#### One limitation of this dataset is that we do not know what tactics each campaign used or who each campaign was targeted to. This information could help us determine what methods the Fever campaign could utilize for a successful outcome. This could also factor into the cause of failed campaigns. Another limitation to the dataset is that we do not know the genre of plays for the Kickstarter sample. It is possible that certain genres perform better than others, regardless of goal or launch date.

### Additional Possible Tables/Graphs

#### Another metric that could be useful is outcome by length of campaign. This could be determined by finding the time difference between end date and launch date. It’s possible some of the failed campaigns didn’t run long enough to meet the goal. It would also be helpful to analyze the measures of central tendency to determine if any of the datasets are skewed or if there are any outliers throwing off the results.
