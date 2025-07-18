# Amazon-Prime-Movies-and-TV-shows

**🔍 Overview**

This project performs Exploratory Data Analysis (EDA) on a dataset containing Amazon Prime content metadata, including movies and TV shows. The dataset includes features such as titles, genres, release years, IMDb and TMDb ratings, runtimes, production countries, age certifications, and more.

**📁 Dataset Summary**

**Source:** Amazon Prime dataset (titles and credits)

**Key Features:**

- Title, Type (Movie/TV Show)

- Genre, Release Year, Runtime

- Age Certification

- IMDb & TMDb ratings and popularity

- Directors, Cast

- Production Countries

**🧹 Data Cleaning**

- Handled missing/null values across age_certification, runtime, seasons, etc.

- Removed duplicate entries based on title and id.

- Converted stringified lists (e.g., genres, countries) into usable formats.

- Cleaned and exploded multi-valued fields for accurate analysis.

**📊 Data Visualization & Key Findings**

**🎯 1. IMDb Score Distribution**

**Insight:** Most movies cluster around an IMDb rating of 6–7.

**🌍 2. Top Producing Countries (Pie Chart)**

**Insight:** The United States contributes nearly 75% of all content, followed by India and the UK.

**🎬 3. Age Certification Distribution (Bar Plot)**

**Insight:** The majority of content is rated R, with fewer family-friendly options.

**⭐ 4. Average IMDb Ratings by Age Certification**

**Insight:** TV-PG, TV-MA, and TV-14 have higher average ratings.

**⏱️ 5. Runtime Distribution by Genre (Box Plot)**

**Insight:** Documentaries and Dramas show the widest variation in runtime.

**🎬 6. Top Directors by Content Count (Bar Chart)**

**Insight:** Directors like Joseph Kane and Sam Newfield have directed the most titles.

**🔗 7. Pairplot of Rating Variables**

**Insight:** Strong positive correlation observed between IMDb score and TMDb score.

**✅ Conclusion**

- **Dominant Content Type:** R-rated and US-produced content dominates the platform.

- **Rating Trends:** Higher-rated content is often PG-13 to TV-MA, while R and NC-17 rated shows tend to have lower scores.

- **Genre Variation:** Runtime varies significantly by genre, indicating viewer engagement strategies should differ.

- **Director Patterns**: Some directors contribute more to quantity than quality.

**💡 Recommendations**

- **Diversify Production:** Encourage more titles from underrepresented countries to broaden global appeal.

- **Expand Family Content:** Invest in PG and TV-Y7 content to reach a broader demographic.

- **Prioritize High-Performing Genres:** Focus on drama and documentary genres with high viewer retention.
