# Project Title: Microsoft Movie Studio Data Analysis
Microsoft is creating a new movie studio but lacks knowledge on what types of movies to produce. The goal of this project is to analyze box office trends using data from movie databases and ticket sales records to guide their decisions on movie genres, budget allocation, and marketing strategies. The project involves the following data science steps:

1. Data Understanding: Four datasets were used from IMDb to analyze trends and factors that contribute to a movie's success or failure, including box office gross revenue, IMDb rating, production budget, and genre.

2. Data Preparation: The datasets were prepared for analysis by dropping null values and incomplete datasets, and any column with a null percentage of over 5% was also dropped.

3. Data Modeling: The code was run on 744 movies to show a process for analyzing and modeling the data related to movie studios and their worldwide gross revenue. The approach involved grouping the data by studio and summing the worldwide, then converting it to a DataFrame and sorting it by total worldwide in descending order. A horizontal bar chart was created to display the results. The code was then iterated to filter out data before 2000 and create a pivot table to analyze worldwide gross by studio, which is then displayed as a bar chart. Lastly, the code showed the process of grouping data by rating and summing the worldwide to create a table.

4. Results: Following an evaluation of the studio's performance, it was recommended that a successful studio be consulted in order to establish a new one for Microsoft. The studio's performance was assessed based on several key metrics, including the quality of their production as evidenced by movie ratings, as well as the revenue and profits generated from their films. Implementing this approach would enable the company to produce high-quality movie content while also achieving significant revenue generation.

Total World Wide Gross by Studio
 ![image](https://github.com/elsheikhz1/Project-1/assets/107605292/7968cf10-7634-4ca8-b395-f806b2f7cb8b
 
 Average rating by Studio
![image](https://github.com/elsheikhz1/Project-1/assets/107605292/0e5f5106-4c7f-4e63-83ea-73d08a78698b)

Total World Wide Gross by Studio
![image](https://github.com/elsheikhz1/Project-1/assets/107605292/7ceadb2c-ee5c-4f34-8047-5901b549ffe0)

5. Conclusions: Based on the analysis conducted, it was recommended that Buena Vista is the most suitable studio for Microsoft to consult. With the highest revenue and profit achieved, coupled with the second-highest average rating per movie of 6.9, Buena Vista is well positioned to provide valuable insights and expertise in producing high-quality movies that generate strong returns. The use of larger datasets and exploring trending genres could be a valuable addition to the analysis, helping to identify the types of movies that would align with Microsoft's goals and objectives.

Navigation of respitoruy
Jupyter Nootbook: Microsoft New Studio Project.ipynb
https://github.com/elsheikhz1/Project-1/blob/main/Microsoft%20New%20Studio%20Project.ipynb
Presentation slides: Microsoft’s Movie Studio Presentation.pdf
https://github.com/elsheikhz1/Project-1/blob/main/Microsoft%E2%80%99s%20Movie%20Studio%20Presentation.pdf

Data base used:
bom.movie_gross.csv.gz: https://github.com/elsheikhz1/Project-1/blob/main/bom.movie_gross.csv.gz
imdb.title.basics.csv.gz: https://github.com/elsheikhz1/Project-1/blob/main/imdb.title.basics.csv.gz
imdb.title.ratings.csv.gz: https://github.com/elsheikhz1/Project-1/blob/main/imdb.title.ratings.csv.gz
tn.movie_budgets.csv.gz: https://github.com/elsheikhz1/Project-1/blob/main/tn.movie_budgets.csv.gz
