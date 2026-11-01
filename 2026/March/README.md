# Challenges Table

| Week | Challenge | Creator | Data Source |
|--|--|--|--|
| 10 | [Dynamic visibility of visuals](https://www.workout-wednesday.com/2026-week-10-power-bi-dynamic-visibility/) | [Diana Ackermann](https://www.workout-wednesday.com/author/dackermann/) |[WoW/data - Github](https://github.com/Workout-Wednesday/data/blob/main/2026/2026-01_Eurostat_arrivals.xlsx) |
| 12 | [Custom matrix subtotals and cards with categories](https://www.workout-wednesday.com/pbi-2026-w12/) | [Meagan Longoria](https://www.workout-wednesday.com/author/meagandcac-com/) | [Financial Sample](https://learn.microsoft.com/en-us/power-bi/create-reports/sample-financial-download) |
| 13 | [Tile Map with 3D Effect](https://www.workout-wednesday.com/pbi-2026-w13/) |  [Meagan Longoria](https://www.workout-wednesday.com/author/meagandcac-com/) |[US Census](https://www2.census.gov/library/publications/2011/compendia/statab/131ed/tables/12s0366.pdf) |

# What I learned
## 2026 Week 10 | Power BI: Dynamic visibility of visuals by Diana Ackermann

The goal of this challenge was to create dynamic UI elements that appear or disappear based on user selections, allowing users to compare two countries. 
This was my first challenge, and also the first time working with slicers, DAX conditional logic using IF statements, conditional background formatting, and 
overlapping visuals. I learned how to combine these features to control visual elements dynamically based on user input and create more interactive reports.


## 2026 Week 12 | Power BI: Custom matrix subtotals and cards with categories by Meagan Longoria 

In this challenge, I continued developing my understanding of Power BI visuals, focusing on formatting matrices and cards. I learned how to customize number 
formatting, control how values are displayed, and adjust visual elements such as borders, rounded corners. I also became more familiar with the formatting options 
available for different visual components, understanding how small adjustments can improve the overall layout, readability, and consistency of a report.

## 2026 Week 13 | Power BI: Tile Map with 3D Effect by Meagan Longoria 

This challenge was my first experience working with Deneb and the Vega visualization language. Although JSON syntax was already familiar to me, understanding how the tile geometry was constructed was more challenging. I used the creator's PBIX file as a reference to better understand the implementation and guide my own version.

I also created a separate coordinate table to define the position of each state, which helped simplify part of the implementation. One of the most interesting aspects of this challenge was understanding why tile maps can be used instead of geographically accurate maps: by representing each state with a tile, the visualization reduces geographical distractions and keeps the viewer's attention on the data itself.

I'm still getting familiar with Deneb and Vega, and I don't fully understand every part of the code yet. However, this challenge introduced me to a different way of thinking about data visualization. I had already recognized the importance of choosing the right chart for the data, but this experience helped me understand how simplifying or reshaping certain aspects of information can guide the viewer's attention toward what really matters in a visualization.
