
# Recommendation System for Anime

## Executive Summary 

I created a recommendation system that allows people to find anime to watch. 
Everyone has just about watched every interesting show on netflix, it may be useful to try something new and different.

You can also link to 
* [Email Me](anila.m.qureshi@gmail.com)
* [My LinkedIn](https://www.linkedin.com/in/aneela-qureshi-262aa670/)
* [Follow me on Twitter](https://twitter.com/aneeliabedelia)


### Background Information

Anime, is a hand drawn and computer animation originating from Japan which is widely drawn a cult following around the world. The animation industry consists of more than 430 companies. Some of the most popular anime that has come to Western television is Pokemon and Yugi-Oh ."Spirited Away" a film created by Hayao Miyazaki and animated by Studio Ghibli is the highest grossing film within the anime genre. The reason it became so popular in the west is because a good friend of Miyazaki convinced him to sell distribution rights to Walt Disney. Like Spirited Away, there are thousands of really good anime films and shows produced by the same animation house. Due to the pandemic a nice way to bring such works of art into Disney plus or any streaming site in the West I have created a recommendation system that can help anyone or any company to view/add the highest rated anime. The Japan External Trade Organization has valued overseas sales to  18𝑏𝑖𝑙𝑙𝑖𝑜𝑛( 5.2 billion for the US alone) in 2004. This has likely grown. With covid19 looming over Japan which has caused one of the first long term recessions for the country. A way at which potential growth could take place is focusing on streaming and producing more of the top recommended.

Below I am creating a recommendation system for anime. This will help with the above problem and can help to create more in demand anime that is similar. It can also help anyone who is not familiar with the niche genre to quickly find top rated items. (Helping to grow the market).

I have downloaded anime and user ratings from https://www.kaggle.com/CooperUnion/anime-recommendations-database . I will conduct exploratory data analysis to familiarise the reader and myself with the data presented. From there I have created a baseline model using Singular Value Decomposition(SVD). I will then do memory based models which will look at user based v item based. I will use KNNBase, KNNBaseline and KNNWithMeans. Then I will take the top performing model and evaluate its root mean squared error (rmse) and its mean absolute error (mae). 


### More Information

Based off of the modelling done, it would be best to conduct more statistical analysis on top rated and viewed anime that comes from the same animation studios, writers, directors and media houses. From here we can tweek the recommendation system to include their newest releases. 

Another suggestion is to look at a time component analysis. TV shows are the most viewed type of anime, during which time of year. From here the recommendation system can help to fill in the gaps within the fiscal year for anime studios. They can either spread out the dates or work on a new pipeline for creating more specials. 

### Glimpse of some Data Viz

![Distribution of anime types](figures/distributionoftypes.png)

> Image taken from `copy_of_mvp.ipynp` [documentation](https://github.com/anilaq/capstone/blob/master/Copy_of_mvp.ipynb)

![Distribution of user ratings](figures/distributionsofratings.png)
> Image taken from `copy_of_mvp.ipynp` [documentation](https://github.com/anilaq/capstone/blob/master/Copy_of_mvp.ipynb)

![Number of Reviews per User](figures/numofreviewsperuser.png)
> Image taken from `copy_of_mvp.ipynp` [documentation](https://github.com/anilaq/capstone/blob/master/Copy_of_mvp.ipynb)


### Directory

Although I started this project on my local machine, I did not have enough CPU power to continue. At the top of my `copy_of_mvp.ipynb` and `final_mvp.ipynb` you can see that there is a link to run it and replicate it in google colab. (Friendly and repetitive reminder that google colab does not save notebooks, you have to manually do this yourself). 

The `final_mvp.ipynb` is where the most up to date and organized modelling occurs. 
The `figures` file holds all images that have been used for visuals in the readme.md file. 
The `anime-recommendations-database` holds all the data that I have downloaded from kaggle to run my models on. 
The `ppt.pdf` is a quick powerpoint that goes over the business problem, models, and findings as stated above but in a more visual manner. 


### Sources: 
* [https://en.wikipedia.org/wiki/Anime#Industry()
* [https://en.wikipedia.org/wiki/Spirited_Away()
* [https://sifted.eu/articles/streaming-startups-coronavirus/()




