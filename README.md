# Netflix-Movies-and-TV-Shows-Clustering-Capstone-Project

![github](https://github.com/anasmalik081/Netflix-Movies-and-TV-Shows-Clustering-Capstone-Project/assets/84465546/c01734a4-9ef7-47bc-a75d-afdd4ca0a05e)

### Project tile - Netflix Movies and TV Shows Clustering
### Description:
This is a Unsupervised ML (Clustering) capstone project on **Netflix Movies and TV Shows Clustering** given by [Alma Better](https://www.almabetter.com/).

![github](https://github.com/anasmalik081/Netflix-Movies-and-TV-Shows-Clustering-Capstone-Project/assets/84465546/c01734a4-9ef7-47bc-a75d-afdd4ca0a05e)

### Problem statement:

This dataset consist of tv shows and movies available on Netflix as of 2019. The dataset is collected from Flixable which is a third-party Netflix search engine. In 2018, they released an interesting report which shows that number of TV Shows on Netflix has nearly tripled since 2010. The streaming service's number of movies has decreased by more than 2,000 titles since 2010, while its number of TV Shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset.

Integrating this dataset with other external dataset such as IMDB ratings, rotten tomatoes can also provide many interesting findings.

![net](https://github.com/anasmalik081/Netflix-Movies-and-TV-Shows-Clustering-Capstone-Project/assets/84465546/a1c40eed-2b7e-4be9-9022-d3c72998ef52)

![github](https://github.com/anasmalik081/Netflix-Movies-and-TV-Shows-Clustering-Capstone-Project/assets/84465546/c01734a4-9ef7-47bc-a75d-afdd4ca0a05e)

### Note: Dataset is provided by the company, [Alma Better](https://www.almabetter.com/).

### Dataset description:

The dataset is collected from Flixable which is a third-party search engine of Netflix. The dataset consist of the information of the Movies and TV Shows available on Netflix as of 2019

Attribute Information:
* show_id - Unique ID for every Movie / Tv Show
* type - A Movie or TV Show
* title - Title of movie/show
* director - Director of the show
* cast - Actors involved
* country - Country of production
* date_added - Date it was added on Netflix
* release_year - Actual release year of the show
* rating - TV ratings of the show
* duration - Total duration in minutes or number of seasons
* listed_in - Genre
* description - The summary description

![github](https://github.com/anasmalik081/Netflix-Movies-and-TV-Shows-Clustering-Capstone-Project/assets/84465546/c01734a4-9ef7-47bc-a75d-afdd4ca0a05e)

### Project Flowchart:

1. Initial preparations(Loading the dependencies and the data)

2. Data Inspection

3. Data Wrangling
   * Handling null values
   * Handling duplicate values
   * Removing Irrelevant Features

4. Exploratory Data Analysis (EDA)

5. Data Preprocessing
     * Feature Encoding
     * Text Preprocessing
         * Removing Punctuations
         * Removing Stopwords
         * Lemmatization
      * Scaling
        
6. Feature Engineering
     * Creating new features
     * Vectorization

7. Model implementation
     * KMeans Clustering
         * Elbow Method
         * Silhouette Score
     * Hierarchical Clustering
         * Dendogram Visualization
         * Agglomerative Clustering
     * DBSCAN
  
![github](https://github.com/anasmalik081/Netflix-Movies-and-TV-Shows-Clustering-Capstone-Project/assets/84465546/c01734a4-9ef7-47bc-a75d-afdd4ca0a05e)

### Conclusion:

1. EDA insights:
     * Netflix started becomming popular in 2008 and in 2015, it gets a boost in its growth.
     * There are two types of content available on Netflix ,i.e., Movies and TV Shows.
     * Earlier there were only Movies (before 2002), but in recent years both of the * content is increasing drastically specially TV Shows because the young generation is prefering TV Shows over Movies.
     * USA has contributed the largest number of contents(both Movies & TV Shows) on Netflix.
     * Japan & South Korea are two top countries who have contributed more number of * TV Shows as compare to Movies.
     * Most of the content available on Netflix is for Mature audience.
     * Top 3 genre of the content are International, Dramas & Comedies.
     * Most of the content is added in the month of December on Netflix.

2. Results from ML models:
     * KMeans Clustering :
         * Elbow Method ---> K values is 2.
         * Silhouette Score ---> When the K value is 2, silhouette score is highest ,i.e., 0.42.
     * Hierarchical Clustering :
         * Dendogram ---> No. of Clusters = 2.
     * DBSCAN :
         * I applied DBSCAN with min_samples = 2.
           
3. Challenges faced:
     * Feature Encoding
     * Text Preprocessing
     * Vectorization
     * Finding Optimal Value of K

![github](https://github.com/anasmalik081/Netflix-Movies-and-TV-Shows-Clustering-Capstone-Project/assets/84465546/c01734a4-9ef7-47bc-a75d-afdd4ca0a05e)

**For further information you can check the google colab file added in the repository.**

**If you find any mistakes or have any suggestions for me, please reach out to me, all the criticism is heartly welcomed.**

**You can also reach out to me for project collaborations.**

**My Email Id - anasmalik081@gmail.com**

**My LinkedIn profile - [Anas Malik](https://www.linkedin.com/in/anas-malik-01/)**

### Thankyou for tagging along to the end.
