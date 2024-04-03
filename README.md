##Movie Studio Market Analysis Project

## Table of Contents
- [Business Understanding](#business-problem)
- [Data Understanding](#data-insights)
- [Data Preparation and EDA](#data-preparation-and-eda)
- [Visualization](#models)
- [Results](#results)
- [Next Steps](#recommended-next-steps)
- [Conclusion](#conclusion)
- [Requirements](#requirements)

**Authors**: Johnathan Yater and Lotus Baumgarner
  
#Business Understanding

In an era where original video content is increasingly dominating the entertainment industry, our company has recognized the strategic opportunity to establish a new movie studio. The primary objective is to understand what types of films are currently thriving at the box office and to leverage these insights to guide the studio's production strategy. Our aim is to identify genres, budget ranges, and release timing that correlate with high box office performance, translating these findings into actionable recommendations for the studio's launch and future projects.

#Data Understanding

Three key datasets were utilized in this analysis:

Movie Budgets: Contains data on production budgets, domestic gross, and worldwide gross revenue.

TMDB Movies: Provides insights into movie genres, popularity, and audience ratings.

Rotten Tomatoes Movie Info: Offers detailed movie genres, synopsis, and critical ratings.

These datasets enabled a comprehensive examination of financial performance, audience reception, and genre popularity across a wide range of films.

#Data Preparation

Data cleaning and preparation steps included standardizing financial figures and converting them into numerical data, merging datasets based on movie titles to align genre information with financial data, organizing genres into broader categories for a more generalized analysis, and handling missing values and ensuring consistent data formats across all datasets.

#Data Analysis

The analysis focused on identifying patterns and correlations between movie genres, production budgets, release timing, and box office success. Key areas of exploration included the financial success of movies based on worldwide and domestic gross revenue, the correlation between production budgets and box office gross, genre trends and their impact on box office performance, and the effect of movie release timing on financial success.

#Visualization

Several visualizations were created to illustrate findings, including bar charts showing the distribution of release months for top-grossing movies, heatmaps and scatter plots depicting the relationship between budget, audience ratings, and box office revenue, and comparisons of median ROI across different budget levels and genres.

#Results

Key findings include that Horror, Music, and Mystery genres exhibit higher ROIs, especially for films with moderate budgets, movies released during holiday seasons and summer months tend to perform better at the box office, higher production budgets correlate with larger gross revenues, though not necessarily with higher ROI, and positive audience ratings are associated with better financial performance, highlighting the importance of content quality.

#Next Steps

Future analysis could delve deeper into audience demographics, market segmentation, and the impact of streaming platforms on movie success. Additionally, employing advanced analytics and predictive modeling could further refine investment strategies and content selection.

#Conclusion

The analysis provides valuable insights into the current dynamics of the movie industry, highlighting strategic opportunities for our new movie studio. By focusing on cost-effective genres, optimizing release timing, and prioritizing content quality, the studio can position itself for success in the competitive entertainment landscape. Continuous market research and adaptability to emerging trends will be crucial for long-term growth and profitability.


## Requirements
- Python programming language
- Libraries such as pandas, NumPy, and matplotlib
- Jupyter Notebook for code execution and documentation
- Access to the dataset containing movie information from Box Office Mojo, The MovieDB, The Numbers
- Basic understanding of machine learning concepts and techniques
