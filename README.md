# netflix_movie_tv_show_EDA_DS005
## Analysis of the netflix movies &amp; tv shows dataset (EDA)

---

## Introduction   
#### Context  
Netflix is one of the biggest streaming movies & tv shows platform. They have variety of genres and provide us a lot of movies or tv shows from around the world. Finding some insights in the datasets of movies & tv shows attributes produced by Netflix would be beneficial for stakeholders related to streaming or entertainment industry.  
#### Need  
Finding insights through visualizations in the dataset.  
#### Outcome  
Visualization makes us easiear & faster to take new information & patterns from the dataset.  
#### Vision  
Information & patterns hopefully will make decisions from stakeholders in the related industry more data-driven.

---

The dataset = [Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)  
The final analysis = [Jupyter notebook file](https://github.com/IchfanKurniawan/netflix_movie_tv_show_EDA_DS005/blob/main/netflix_data_eda.ipynb)  

#### Key Findings  
- Almost 70% of netflix contents is movies & the rest are tv shows  
<p align="center">
  <img src="./assets/dist_type.png" />
</p>  

- Here are the top 10 countries
<p align="center">
  <img src="./assets/dist_country.png" />
</p>  

- Here are the top 10 countries divided by "type" (movies & tv shows).  
Countries which has big portion of movies than tv shows= USA, Canada, India.  
Countries which has big portion of tv shows than movies= India, Japan, South Korea.  
<p align="center">
  <img src="./assets/dist_countryvstype2.png" />
</p>  

- The release year reachs its peak in 2018 and then gradually down.
<p align="center">
  <img src="./assets/dist_year.png" />
  <img src="./assets/dist_year_kde.png" />
</p>  

- The release year of movies reachs its peak in 2018 and then gradually down. However, the release year of tv shows reachs its peak in 2020.
<p align="center">
  <img src="./assets/dist_yearvstype.png" />
  <img src="./assets/dist_yearvstype_kde.png" />
</p>  

- There is no pattern in the release month
<p align="center">
  <img src="./assets/dist_month.png" />
</p>  

- Mostly the contents (movies or tv shows) are released in the first day a month or in the middle of a month.
<p align="center">
  <img src="./assets/dist_day.png" />
  <img src="./assets/dist_dayvstype.png" />
</p>  

- Mostly movies have duration in range 90-150 min.
<p align="center">
  <img src="./assets/dist_movieduration.png" />
</p>  

- Mostly tv shows have duration of 1 season.
<p align="center">
  <img src="./assets/dist_tvduration.png" />
</p>  

- The director in the dataset is quite diverse as shown by the lower value of percentage.
<p align="center">
  <img src="./assets/dist_director.png" />
</p>  

- The cast in the dataset is quite diverse as shown by the lower value of percentage.
<p align="center">
  <img src="./assets/dist_cast.png" />
</p>  

- Mostly the contents have TV-MA rating.
<p align="center">
  <img src="./assets/dist_rating.png" />
</p>  

- The cast in the dataset is quite diverse as shown by the lower value of percentage.
<p align="center">
  <img src="./assets/dist_cast.png" />
</p>  

- Top 3 listed_in column values= international movies, drama, comedy
<p align="center">
  <img src="./assets/dist_listedin.png" />
</p>  
