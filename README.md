# ICC-IndvsWI-T20-Match-analysis
Data Collection and Preprocessing for visualization with python


> Data was retrieved from the ESPN Cricinfo webpage using Beautiful Soup. Following data extraction, a thorough cleansing process was undertaken to eliminate redundant elements, and data types were optimized for the purpose of generating a comprehensive report card.


__Data Collection from a Webpage :__

- [x] I started by identifying a webpage that had the data I needed. Using the webpage's URL, I fetched its content programmatically, similar to how a web browser would load the page. This gave me access to the underlying HTML code that made up the webpage.

- [x] Once I understood where the data was located in the HTML structure, I used parsing techniques to extract the content.

__Cleaning Up the Data :__

- [x] After retrieving the data, I realized that some of it wasn't necessary for my analysis. I meticulously went through each data point, removing any unnecessary columns or rows that didn't contribute to my goals. I also dealt with missing data, ensuring that my dataset was accurate and complete.

- [x] To make the data suitable for analysis, I performed some additional transformations. For instance, I converted text-based numbers into actual numeric values so that I could perform calculations. I also transformed categorical variables into numerical representations using methods like encoding.

- [x] With the data preprocessed, I focused on the specific parts that were most relevant to what I wanted to achieve. I filtered out certain rows or selected specific columns based on the criteria that aligned with my objectives. This helped me streamline my dataset to the core information I needed.

__Creating Visualizations :__
- [x] With the data well-prepared, I entered the visualization phase. I utilized libraries like Plotly, Matplotlib, and Seaborn to craft a variety of visualizations. These included interactive plots, line charts, bar graphs, scatter plots, and more. Through visualizations, I began to observe patterns and insights.

__Match Report__

> WORM CHART

![263172125-1c0db3a0-1dca-4355-b791-55b978262bd2](https://github.com/Vengatesan-K/ICC-IndvsWI-T20-Match-analysis/assets/128688827/8283589c-7aa6-45b5-825c-e5d0e476a542)


> MANHATTAN CHART

![Screenshot 2023-08-25 104013](https://github.com/Vengatesan-K/PDF-Password/assets/128688827/97f8813c-dde3-4b0d-9d91-0a711bbcea93)

> Batting Comparison

![newplot (14)](https://github.com/Vengatesan-K/PDF-Password/assets/128688827/fa19ce8c-bcc0-4b8c-bcd0-b18c296e7aeb)

> Bowling Comparison

![Screenshot 2023-08-25 104110](https://github.com/Vengatesan-K/PDF-Password/assets/128688827/938f7da5-717c-46f8-92c4-0d193bed1aab)

> Fours and Sixes

![newplot (15)](https://github.com/Vengatesan-K/PDF-Password/assets/128688827/322b015d-dec3-4d90-b5de-e3191bf0a449)

> Runs Distribution

![Screenshot 2023-08-25 104137](https://github.com/Vengatesan-K/PDF-Password/assets/128688827/c0e782d8-6171-4fb7-b568-deec1b90a458)

> Strikerate Comparison

![Screenshot 2023-08-25 104151](https://github.com/Vengatesan-K/PDF-Password/assets/128688827/88893610-c6e0-45ba-a8bf-95c69d61c4cf)
