# Aircraft Safety Analysis Overview

### Author: Noah Meakins

#### Introduction
This project aims to enhance our entry into the aviation sector by focusing on aircraft safety and reliability. By analyzing historical data on aviation accidents, I aim to identify the safest aircraft models for commercial and private use. This initiative underscores our commitment to safety and positions us as a trustworthy industry participant.

#### Business Objective
As part of our diversification strategy, we're venturing into the aviation industry, focusing on acquiring aircraft for commercial and private use. I seek to identify the safest aircraft models through comprehensive data analysis, drawing insights from historical accident data to inform our purchasing decisions.

#### Data Overview
I analyzed aviation accident data from 1962 to 2023, sourced from the National Transportation Safety Board. This dataset includes details on civil aviation accidents in the U.S. and international waters, providing a solid basis for evaluating aircraft safety across different models and manufacturers. 

You can take a deeper look at the original dataset here: (https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses/data). 

#### Analytical Approach
My analysis involved thorough data cleaning to remove irrelevant or incomplete records, followed by detailed examination of the data to identify patterns and insights related to aircraft safety. Key variables such as aircraft make, model, engine type, and injury severity were analyzed to assess the historical safety performance of various aircraft models.

#### Key Findings
My analysis yielded three recommendations that will provide support for the decisions to be made when choosing aircraft. My recommendations are based on quantitative analysis of historical accident data, ensuring they are grounded in empirical evidence.

#### Recommendations
1. For commercial use, consider aircraft from Embraer, Boeing, and Airbus, which show the lowest fatal injury rates. This can be supported with the following visualization: ![Bar Chart of Total Fatal Injuries by Aircraft Make](<images/Total Fatal Injuries by Aircraft Make.png>)

2. For private aircraft, Embraer, Raytheon Corporate Jets, and Gulfstream are recommended based on their safety records. This can also be supported by the visualization above. 

3. Prioritize aircraft with three or more engines and those built after 2015 to benefit from the latest safety features and technologies. This can be supported by the two following visualizations below: ![Incidents by Engine Type and Number of Engines](<images/Incidents by Engine Type and Number of Engines.png>) ![Trend of Fatal Injuries](<images/Yearly Trend of Fatal Injuries.png>)

For an interactive dashboard including the mentioned visualizations, please click the following link to be directed to my Tableau Dashboard for this analysis: 

#### Limitations and Future Directions
My analysis, while comprehensive, has limitations, including potential gaps in historical data and the exclusion of some factors that can affect safety outcomes. Future improvements could include real-time data analysis and a broader set of safety metrics to provide more nuanced recommendations.

#### Conclusion
This project provides a data-driven foundation for selecting safe and reliable aircraft for our business ventures in aviation. By continuing to refine our analytical methods and incorporating the latest data, we can ensure our recommendations remain relevant and effective in promoting safety and operational excellence in our aviation activities.


## Repository Structure

Describe the structure of your repository and its contents, for example:

```
├── README.md                           <- The top-level README for reviewers of this project
├── dsc-phase1-project-template.ipynb   <- Narrative documentation of analysis in Jupyter notebook
├── DS_Project_Presentation.pdf         <- PDF version of project presentation
├── data                                <- Both sourced externally and generated from code
└── images                              <- Both sourced externally and generated from code
```