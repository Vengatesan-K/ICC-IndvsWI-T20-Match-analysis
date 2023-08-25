# ICC-IndvsWI-T20-Match-analysis
Data Collection and Preprocessing for visualization with python


> Data was retrieved from the ESPN Cricinfo webpage using Beautiful Soup. Following data extraction, a thorough cleansing process was undertaken to eliminate redundant elements, and data types were optimized for the purpose of generating a comprehensive report card. The intention is to subsequently share this refined report card on LinkedIn, highlighting the analytical process involved.


__Data Collection from a Webpage :__

- [x] I started by identifying a webpage that had the data I needed. Using the webpage's URL, I fetched its content programmatically, similar to how a web browser would load the page. This gave me access to the underlying HTML code that made up the webpage.

- [x] Once I understood where the data was located in the HTML structure, I used parsing techniques to extract the content.

__Cleaning Up the Data :__

- [x] After retrieving the data, I realized that some of it wasn't necessary for my analysis. I meticulously went through each data point, removing any unnecessary columns or rows that didn't contribute to my goals. I also dealt with missing data, ensuring that my dataset was accurate and complete.

- [x] To make the data suitable for analysis, I performed some additional transformations. For instance, I converted text-based numbers into actual numeric values so that I could perform calculations. I also transformed categorical variables into numerical representations using methods like encoding.

- [x] With the data preprocessed, I focused on the specific parts that were most relevant to what I wanted to achieve. I filtered out certain rows or selected specific columns based on the criteria that aligned with my objectives. This helped me streamline my dataset to the core information I needed.

__Creating Visualizations:__
- [x] With the data well-prepared, I entered the visualization phase. I utilized libraries like Plotly, Matplotlib, and Seaborn to craft a variety of visualizations. These included interactive plots, line charts, bar graphs, scatter plots, and more. Through visualizations, I began to observe patterns and insights.
