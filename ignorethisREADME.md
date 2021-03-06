# Overview of Stock Analysis
The purpose of this Stock Analysis overal was to display Louise's successes failures and cancelations during her campaigns. Louise's budgets and goals based off a variety of categories and subcategories were also displayed in this stock analysis. The color coded items in this analysis for each campaign allow the reader to easily visualize outliers in the data. The different line charts show the trends of the percentages over a difference in goals. The pivot table used to count the outcomes quickly summarize the large amounts of data based on the different categories. Filters can be used in this pivot table to change which country the data is filtered by.
# Analysis and Challenges
## Outcomes Based on Goals
![Screen Shot 2022-01-09 at 6 29 28 PM](https://user-images.githubusercontent.com/77857472/148705587-98ca588a-b5aa-44f2-a008-7c35d91e16e4.png)
Above the screenshot shows the outcomes of the plays subcategory based on the actual goat for each. In this visualization I faced a challenge with using the COUNTIFS() function. I then refered to the official documentation.<img width="493" alt="Screen Shot 2022-01-09 at 6 28 11 PM" src="https://user-images.githubusercontent.com/77857472/148705557-7fcb765d-e30e-49d6-9322-51260b27b0b6.png">


This site was used for me to remind myself how to calculate the percentages of two columns -> [Percentage of two columns](https://www.quora.com/How-can-you-calculate-the-percentage-of-two-numbers-in-Excel).

## Theater Outcomes Based on Launch Date
![Screen Shot 2022-01-09 at 6 40 42 PM](https://user-images.githubusercontent.com/77857472/148705931-7793e6e2-9322-4448-81e1-a27cf1f7b5d8.png)
My challenges faced in this screenshot were that I could properly display months in the rows. [This link](https://support.microsoft.com/en-us/office/group-or-ungroup-data-in-a-pivottable-c9d1ddd0-6580-47d1-82bc-c84a5a340725?ui=en-us&rs=en-us&ad=us) allowed me to group the data based off of the years and then scale down to the months.

# Results
1. What are two conclusions you can draw about the Theater Outcomes by Launch Date?
   - The average of all of the theater outcomes highest succes month was in May with 111 successes. Also for all of the years there was never an data in October for canceled shows. 
2. What can you conclude about the Outcomes based on Goals?
     - You can also see from the Line Chart of the Outcomes Based on Goals that most of the successful outcomes had a greater success rate of 60% or more until the goal range increased to $45,000 to $50,000.Also from this chart you see that no matter what the goal amount was none of the plays were ever canceled.
3. What are some limitations of this dataset?
    - One of the limitations of the data is the inconsistency in the October data for all the years in theater. Also for the plays outcomes there were no canceled plays in the dataset that met that criteria. The canceled columns could be eliminated since there is no need for the data. 
4. What are some other possible tabes and/or graphs that we could create?
    - The most popular category and/or subcategory based off of the successes in the outcome column. A graph of visualization the amount of successes and failures of the campaigns based on whether or not they were staff favorites. 
