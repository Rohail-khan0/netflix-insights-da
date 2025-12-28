# 🎬 Netflix Movie Database Insights (EDA)  
## 📖 Project Description
In the rapidly evolving world of streaming and cinema, understanding audience preferences is key. This project utilizes Python to clean and analyze a dataset of over 9,000 movies. By performing data transformation and feature engineering, the analysis uncovers:
- Which genres dominate the market.
- How movie ratings translate into "Popularity Categories."
- The peak years for movie releases in recent history.
- The relationship between specific genres and high popularity scores.

## 🚀 Key Features
- **Data Cleaning & Transformation:** Handled date formats, stripped unnecessary metadata, and managed missing values.
- **Dynamic Categorization:** Implemented a quantile-based rating system to classify movies into four tiers: *Popular, Average, Below Average, and Not Popular*.
- **Genre Explosion:** Deconstructed multi-genre labels to perform granular analysis on individual genre performance.
- **Statistical Visualizations:** Utilized Seaborn and Matplotlib to create intuitive counts, bar plots, and trend charts.

## 🛠️ Tech Stack
- **Python** (Core Analysis)
- **Pandas** (Data Manipulation)
- **NumPy** (Numerical Processing)
- **Matplotlib & Seaborn** (Data Visualization)

## 📁 Dataset Details
The analysis is based on the `mymoviedb.csv` file, which includes:
- `Release_Date`: Timeline of movie history.
- `Title`: Movie names.
- `Popularity`: Numerical metric of audience reach.
- `Vote_Average`: Average rating score.
- `Genre`: Categories associated with each movie.

## 📊 Visualizations & Insights
The notebook includes several high-impact visualizations:
1.  **Distribution of Movie Genres:** Identifies 'Drama' and 'Comedy' as the most frequent genres.
2.  **Category Count:** A visual breakdown of how many movies fall into high vs. low rating categories.
3.  **Highest Priority Genres:** A bar chart showing which genres achieve the highest average popularity (identifying 'Animation' and 'Adventure' as strong performers).
4.  **Release Year Trends:** A count of releases per year, highlighting the boom in content production.

## 📋 How to Use
1. **Clone the repo:**
   ```bash
   git clone [https://github.com/yourusername/netflix-movie-data-analysis.git](https://github.com/yourusername/netflix-movie-data-analysis.git)

## Conclusion
The analysis demonstrates that while certain genres like Drama are produced in high volumes, others like Animation and Adventure often command higher average popularity scores. The peak of movie releases in the dataset shows a significant trend toward increased content volume in the modern era.
