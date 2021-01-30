# Reflection Document - Milestone3

> Authors: Dustin Burnham, Javairia Raza, Rafael Pilliard Hellwig, Tanmay Sharma

The group has been able to deploy an interactive app built using dash in R. Currently, we have a map and a barplot to compare across countries, a scatter plot to look at associations and a trendline to look at the rates over time. Additionally, this week we have improved our helper function and made it more generalizable where it can take an arbitrary number of lists, grouping variables and rates. We also added documentation and examples to our functions so they can run interactively without having to run the app. 

Our experience using R was an overall positive one. It was an easier transition to develop a skeleton which we prioritized first since we had a predefined layout set up from the python app. It allowed for a smoother git experience with fewer merge conflicts since the layout was already in place. We also added modularization and other associated imports to keep development tidy. 

## Feedback:
We agreed with the TA feedback and all of it was incorporated in Milestone 2 and 3. The additional feedback from Joel around tabs and positioning local sliders next to their appropriate graphs was also completed.

## Fixed issues from Milestone 2:
- Missing data issue (map and scatter plot) 
- Map tooltip
- Default data show when there is no selection
- Add tabs to decrease clutter 
- Add trend lines to the factor plot 
- Move year slider below time series plot 
- Single year vertical line for selected year 
- Give the time series plot a start and end points 
- Move grouper and regressor below scatter plot 

## Known bugs at this stage of development:
- Addressing missing countries (South Sudan and Cote d’Ivoire)
- Rate is greater than one for the primary education rate scatter plot

## Future Improvements and Additions:
- Improve interactivity between existing plots using R
- Add unit tests for our plots
- Formatting layout (reduce the size of plots)
- Homogeneity of color usage across plots 
- Add country selection to the bar plot 
- Improve plot legends/axis for readability
- Add the radio button to show top or bottom countries for bar plot 
- Add a tab with a table of aggregated data 
- Continue improving the CSS design aesthetics 
- Change default zoom of map to remove white padding
- Convert map to leaflet plot
