 # PROJECT-1
 
By [STEVE TROY](https://github.com/01Troy)

### OVERVIEW
This project we will use exploratory data analysis to deteremine what factors should Microsoft consider in starting their own studio. We shall analyze if it's a profitable industry. On top of that, we will see which genres are profitable and what is the correlation of the amount invest in production of a movie and it's realized profit is.


### Business Problem




![WhatsApp Image 2022-05-23 at 10 25 23 PM](https://user-images.githubusercontent.com/104380168/169892557-2163c19b-a7e5-444b-b00a-536824eece67.jpeg)









Image of [Marcolowes](https://www.instagram.com/accounts/login/?next=/p/Cdvaz90IwVg/)


Microsoft sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t know anything about creating movies. I am charged with exploring what types of films are currently doing the best at the box office. I will also translate those findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create and what they should keep in mind as they enter into a new and highly competitive sector.

We will analyze if this venture is likely to result in profits by looking at how movies have perfomed over the years.Once that is done, we will look to see how movies have been released over the years and the month that has the highest number of released movies. The relationship between the ROI and production budget will be looke at keenly. We will then see which genres are the most popular. 

We will then make some recommendations for Microsoft after doing our analysis. This will include which genres to focus on, whether or not runtime will affect their success in the industry and how much to invest in movie production

#### Data
Data will be used from the following sources:

IMDB
The tn_movie_budgets dataset shows us monetary numbers worth considering when planning to produce a film. This includes the initial production budget and gross earning at both a domestic and worldwide scale for the film in question. We are also given the release date of the film for additional context. In my EDA, I will use the production budget and worldwide gross to come up with realized profit column then later an ROI column to help me come up with reliable insights.

The title_basics dataset has genres, runtime minutes and year started columns. I'll use this to create proper insights on which genres are the most popular. We will further look into the runtime data and analyze if it affects the rating of a movie. This will be done after join the title_basic and title_ratings datasets.


### Methods & Results

I use descriptive analysis to show that:

The movie making industry is a profitable industry.

The most popular genres in this industry are drama and doumentaries both with a percentage of over 35.

The movie makers are usually busy in December than any other month.

The correlations between production budget, profit and ROI, and runtime and ratings vary.








![heatmap_to_show_correlation_between_productio_budget_and_other_factors_Python](https://user-images.githubusercontent.com/104380168/169898929-65589f72-1848-4cd1-834a-e6b37f617441.png)






### Conclusion

The movie production industry is a profitable industry. Everything held constant, Microsoft is likely to generate good profits if it goes ahead with its investment plan.

The most popular genres are drama and documentary. Microsoft should focus on these two.

Make movies that have high budgets in order to maximized on profits. However these have low ROIs.

Movie runtime doesn’t dictate the movie’s rating. Nevertheless, most movies have an average runtime of 90 minutes.

The last quarter of the year is the busiest in terms of releasing movies.






![countplot_showing_the_total_number_of_movies_produced_each_month_Python](https://user-images.githubusercontent.com/104380168/169899761-9e8cd9cb-759a-490a-97ef-b2be76d34be2.png)







### REPOSITORY STRUCTURE


```bash
├── data
├── images
├── __eda__.py
├── phase_1_project_presentation.pdf
├── README.md
 ```
