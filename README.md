# Kickstarting with Excel

## Overview of Project
Louise has come very close to her fundraising goal in a short amount of time. We have analyzed the potential outcome of her play based on launch dates and size of goal using historical kickstart data. We have even taken this a step further and isolated Kickstarter data to focus on a more relatable  Theaters and Plays.

### Purpose
The purpose of this project is to determine the potenial outcome (success, fail, or cancel) of Louise's play, Fever, and propose an opening date.

## Analysis and Challenges
Basic excel features like formulas, pivot tables, filters, and graphs were used for analysis. 
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/103381098/163433254-9e7c0843-a410-44ec-8ed3-a43c6a85e817.png)
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/103381098/163433291-e7ea48e9-dbef-4fd4-bfe2-f26471770a05.png)

### Analysis of Outcomes Based on Launch Date
May, June, and July are by the best months to launch for theater category. Collectively  these months represented roughly a third of successful outcomes. Theaters appeared more likely to fail when launched between late summer and early fall. 

### Analysis of Outcomes Based on Goals
Almost 90% of successful plays had a goal less than 10k. Surprisingly, no plays were canceled. Goals under 20k represented a bigger proportion of successful outcomes compared to failures. Only goals between 35k-45k had a higher ratio of successful plays.

### Challenges and Difficulties Encountered
Fortunately, the Kickstarter dataset was clean and required no scrubbing of the data. Values matched corresponding fields. Strings and numeric fields matched anticipated values. If this were not the case, then excel features would need to be modified to analyze a dirty data set. One of the biggest limitations was data size when subcategories are filtered to plays. There are just over 1000 and just under 700 when we filter country to US.

## Results
I would recommend Louise release her play in May or June and no later than July. A fall or winter release would drastically increase her chances of failure. Ideally, her goal should have been less than 10k. However, she is right around the 20k threshold giving her a better chance of a successful outcome. Hopefully, the fact that she came very close to her goal in a short amount of time will increase the probability of a successful outcome. It would be interesting to analyze the time to raise a Kickstarter goal. One would think the shorter the time the higher chance of success.
