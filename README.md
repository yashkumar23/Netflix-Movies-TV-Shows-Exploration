# 🎬 Netflix Movies & TV Shows Exploration

## 📌 Project Overview & Task Objective

This `Netflix_Movies_TV_Shows_Exploration_Main.ipynb` explores the Netflix Movies and TV Shows dataset to uncover insights such as content distribution over time, type proportions (Movie vs TV Show), genre popularity, rating categories, content-producing countries, and content durations. The primary objective is to understand Netflix's content strategy using exploratory data analysis (EDA).

## 📂 Dataset Information

The project utilizes the `netflix_titles.csv` dataset, which contains information about movies and TV shows available on Netflix. Key features include `show_id`, `type`, `title`, `director`, `cast`, `country`, `date_added`, `release_year`, `rating`, `duration`, `listed_in` (genres), and `description`.

**Key Aspects:**
- Content distribution over time.
- Proportion of Movies vs. TV Shows.
- Popularity of different genres.
- Analysis of content ratings.
- Identification of top content-producing countries.
- Examination of content durations.

## ✨ Features

- Data loading and initial inspection.
- Handling missing values.
- Exploratory Data Analysis (EDA) to visualize content trends.
- Analysis of content types (movies vs. TV shows).
- Investigation of genre popularity and distribution.
- Examination of content ratings and their prevalence.
- Identification of key countries contributing to Netflix content.
- Analysis of content duration for both movies and TV shows.

## 🛠️ Installation

To run this notebook locally, you will need Python installed along with the following libraries. You can install them using pip:
```bash
pip install pandas numpy seaborn matplotlib
```

## 🚀 Approach

My approach to exploring the Netflix dataset involved the following steps:

- **Library Import**: Imported essential Python libraries for data manipulation (pandas, numpy), and visualization (matplotlib, seaborn).
  
- **Data Loading**: Loaded the `netflix_titles.csv` dataset into a pandas DataFrame.

- **Data Cleaning and Preparation**:
  - Handled missing values in relevant columns (e.g., `director`, `cast`, `country`).
  - Converted `date_added` to datetime objects for time-based analysis.
  - Extracted and processed genre information from the `listed_in` column.
    
- **Exploratory Data Analysis (EDA)**:
  - Analyzed the distribution of content types (Movie vs. TV Show).
  - Visualized content added over time to observe trends.
  - Explored the popularity of different genres using count plots.
  - Examined the distribution of content ratings.
  - Identified the top countries producing content for Netflix.
  - Analyzed the duration of movies and TV shows.

## 🧰 Technologies Used
- P Y T H O N
- P A N D A S
- N U M P Y
- M A T P L O T L I B
- S E A B O R N

## 📉 Visualizations
### Distribution of Movies vs TV Shows
![image](https://github.com/user-attachments/assets/140d7e59-b01c-465b-a8bd-e87ebe2f2f8d)

**Insights:** Netflix hosts 69.1% Movies and 30.9% TV Shows, indicating a strong focus on film content.

### Top 10 Content Ratings
![image](https://github.com/user-attachments/assets/cfe987d2-e612-46fe-8cae-72bc925216e1)

**Insight:**  TV-MA and TV-14 are the most frequent, showing a large amount of teen and adult-oriented content.

### Top 10 Most Common Genres on Netflix
![image](https://github.com/user-attachments/assets/92448af5-a8cf-4ef3-8b35-540cb1177d5c)

**Insight:** Netflix's top genres are International Movies, Dramas, Comedies, and Documentaries, showing they cater to varied interests.

### Content Releases Over the Years
![image](https://github.com/user-attachments/assets/189504d7-fc96-4b61-b671-59330b6e989f)

**Insight:** Most content was released post-2000, with peaks around 2016–2020. Netflix’s recent growth is significant.

### Top 10 Countries Producing Netflix Content
![image](https://github.com/user-attachments/assets/3b08a354-9764-4756-8413-72bd1184b6ea)

**Insight:** USA is the leading content producer, with India and the U.K. also major contributors, proving Netflix's worldwide reach.

## 📊 Results and Insights

- Netflix mostly has movies, many of them for adults (TV-MA).

- Most content is from the United States, but shows and movies from India, the UK, and other countries       are growing.

- The most popular genres are:

   - International Movies

   - Dramas

   - Comedies

   - International Dramas

   - Documentaries

- A lot of content was added after 2016, showing Netflix's fast growth.

- Netflix is offering more global and diverse content over time.

## 🧪 Usage

```bash
# 1. Clone the repository 
git clone https://github.com/Shilpachhatani/Netflix-Movies-TV-Shows-Exploration.git

# 2. Navigate to the project directory
cd Netflix-Movies-TV-Shows-Exploration

# 3. Open the notebook
jupyter notebook Netflix_Movies_TV_Shows_Exploration.ipynb

```

## 🤝 Contributing

Contributions are welcome! If you have any suggestions or improvements, please open an issue or submit a pull request.

## 📬 Contact

For questions or collaboration:
- GitHub: `Shilpachhatani`
- Email: shilpachhatani669@gmail.com

