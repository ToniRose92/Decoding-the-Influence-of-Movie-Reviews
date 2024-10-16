# Decoding the Influence of Movie Reviews on Revenue

## Project Overview
This project explores how the sentiment of movie reviews impacts the success of future films for directors and actors. Using **Natural Language Processing (NLP)**, **sentiment analysis**, and various statistical techniques, we analyze the relationship between review sentiments and box office performance. This research provides insights into how reviews can drive success in the entertainment industry, helping organizations understand the role of public perception in future projects.

## Research Question
**How do mentions of actors and directors in movie reviews, along with the sentiment expressed, influence their future projects' revenue and success metrics?**

## Tools & Technologies Used
- **Programming Languages**: Python
- **Libraries**: Pandas, Scikit-learn, NLTK (NLP), Matplotlib, Seaborn
- **Statistical Models**: Mann-Whitney U Test, Spearman’s Rank Correlation, Generalized Linear Models (GLM), Mixed-Effects Models, Cohen's d Effect Size
- **Data Sources**: Publicly available movie-related datasets from Kaggle
- **Visualization**: Scatter plots, bar charts, heatmaps, and time-series graphs

## Methodology
1. **Data Collection & Preparation**:
   - Data was sourced from multiple publicly available datasets on Kaggle, focusing on movie reviews, revenue, and other success metrics.
   - Data cleaning and merging were performed using Python, with extensive preprocessing steps to address missing or inconsistent data.
   
2. **Sentiment Analysis**:
   - Reviews were tokenized, and sentiment scores were assigned using NLP libraries. These scores were aggregated for both actors and directors across multiple projects.

3. **Statistical Testing**:
   - The relationship between sentiment scores and revenue was evaluated using statistical tests, including Mann-Whitney U Tests and Spearman’s Rank Correlation.
   - **Generalized Linear Models (GLMs)** were applied to assess how much of the variance in revenue can be explained by sentiment and review volume.
   - **Mixed-Effects Models** were used to account for random effects between actors and directors.

## Key Insights
- **Positive Sentiment Boosts Revenue**: Positive reviews were found to have a statistically significant impact on revenue for both actors and directors, with large effect sizes.
- **Neutral Sentiment Matters**: Neutral sentiment had a borderline but notable impact, particularly for actors.
- **Review Count is Critical**: The number of reviews was consistently a significant predictor of future success.

## Challenges & Learnings
- The project involved complex data cleaning and merging processes, which were more challenging than anticipated. Iterative approaches were used to ensure data quality.
- Low R-squared values in GLM models suggest that other factors beyond review sentiment may also play a role in determining revenue, which could be a focus for future research.

## Visualizations
Key visualizations include scatter plots showing the correlation between sentiment and revenue, as well as bar charts demonstrating effect sizes for actors and directors. These can be viewed in the **notebooks** or **visualizations** section of the repository.

## How to Run
1. Clone the repository.
2. Install dependencies: `pip install -r requirements.txt`
3. Open the Jupyter notebook to run the analysis.

## Conclusion
The analysis shows a strong relationship between positive sentiment in movie reviews and box office success, highlighting the importance of public perception in the entertainment industry. While reviews explain some of the variance in revenue, future research should investigate additional factors that contribute to a film's financial success.

---

### Timeline
The project follows the CRISP-DM methodology and is planned over 6 weeks, with milestones ranging from business understanding to deployment.

### Ethical Considerations
All sources used will be properly cited and referenced, adhering to ethical guidelines for academic and professional work.

## Appendices

### Links to all Kaggle Datasets used
- [Movie Reviews Dataset](https://www.kaggle.com/datasets/joyshil0599/movie-reviews-dataset-10k-scraped-data)
- [The Complete Movie Dataset](https://www.kaggle.com/datasets/mayasoffer/the-complete-movie-dataset)
- [Clapper Massive Rotten Tomatoes Movies and Reviews](https://www.kaggle.com/datasets/andrezaza/clapper-massive-rotten-tomatoes-movies-and-reviews?datasetId=3125944&sortBy=dateRun&tab=profile)
- [25k Movie Dataset](https://www.kaggle.com/datasets/utsh0dey/25k-movie-dataset)
- [Millions of Movies](https://www.kaggle.com/datasets/akshaypawar7/millions-of-movies)
- [Worldwide Box Office Rankings 1977](https://www.kaggle.com/datasets/jonbown/worldwide-box-office-rankings-1977)
- [Weekend Box Office Summaries](https://www.kaggle.com/datasets/jonbown/weekend-box-office-summaries)

## References
- Basuroy, S., & Ravid, S. A. (2006). *The Power of Stars: Do Star Actors Drive the Success of Movies?* Journal of Marketing, 70(4), 1-20.
- Elberse, A. (2013). *Blockbusters: Hit-making, Risk-taking, and the Big Business of Entertainment*. Henry Holt and Co.
- Epstein, E. J. (2012). *The Hollywood Economist 2.0: The Hidden Financial Reality Behind the Movies*. Melville House.
