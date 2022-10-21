# Trending-Youtube-Video-Statistics

# Problem Statement
Simplify the Trending list with the basis of given data and tell which industry comes in trending list.

* [Main Code](https://github.com/piyush033/Trending-Youtube-Video-Statistics/blob/main/Trending-Youtube-Video-Statistics-checkpoint.ipynb) 

# Table of Content
* [Problem Statement](https://github.com/piyush033/Trending-Youtube-Video-Statistics#problem-statement)
* [Dataset Used](https://github.com/piyush033/Trending-Youtube-Video-Statistics#dataset-used) 
* [Framework Used](https://github.com/piyush033/Trending-Youtube-Video-Statistics#frameworks-used)
* [Youtube Video Statistics Data Dictionary](https://github.com/piyush033/Trending-Youtube-Video-Statistics#trending-youtube-video-statistics-data-dictionary)
* [Model Visualization](https://github.com/piyush033/Trending-Youtube-Video-Statistics#model-visualizations)
* [Conclusion](https://github.com/piyush033/Trending-Youtube-Video-Statistics/blob/main/README.md#conclusion)

# Dataset Used 
The original data come from [Kaggle Trending YouTube Video Statistics](https://www.kaggle.com/datasets/datasnaek/youtube-new).

You can find this also in my repository: [My Repository](https://github.com/piyush033/Trending-Youtube-Video-Statistics/tree/main/Data) 

# Frameworks Used

* [Numpy](https://numpy.org/doc/)
* [Pandas](https://pandas.pydata.org/pandas-docs/stable/)
* [Scikit-Learn](https://scikit-learn.org/stable/)
* [Matplotlib](https://matplotlib.org/stable/index.html)
* [Seaborn](https://seaborn.pydata.org/)

# Trending YouTube Video Statistics Data Dictionary

### Context
YouTube (the world-famous video sharing website) maintains a list of the top trending videos on the platform. According to Variety magazine, “To determine the year’s top-trending videos, YouTube uses a combination of factors including measuring users interactions (number of views, shares, comments and likes). Note that they’re not the most-viewed videos overall for the calendar year”. Top performers on the YouTube trending list are music videos (such as the famously virile “Gangam Style”), celebrity and/or reality TV performances, and the random dude-with-a-camera viral videos that YouTube is well-known for.

This dataset is a daily record of the top trending YouTube videos.

Note that this dataset is a structurally improved version of this dataset.

### Content
This dataset includes several months (and counting) of data on daily trending YouTube videos. Data is included for the US, GB, DE, CA, and FR regions (USA, Great Britain, Germany, Canada, and France, respectively), with up to 200 listed trending videos per day.

EDIT: Now includes data from RU, MX, KR, JP and IN regions (Russia, Mexico, South Korea, Japan and India respectively) over the same time period.

Each region’s data is in a separate file. Data includes the video title, channel title, publish time, tags, views, likes and dislikes, description, and comment count.

The data also includes a category_id field, which varies between regions. To retrieve the categories for a specific video, find it in the associated JSON. One such file is included for each of the five regions in the dataset.

For more information on specific columns in the dataset refer to the column metadata.

### Acknowledgements
This dataset was collected using the YouTube API.

### Inspiration
Possible uses for this dataset could include:

* Sentiment analysis in a variety of forms
* Categorising YouTube videos based on their comments and statistics.
* Training ML algorithms like RNNs to generate their own YouTube comments.
* Analysing what factors affect how popular a YouTube video will be.
* Statistical analysis over time.

For further inspiration, see the kernels on this dataset!

# Conclusion

* The music category is in the 1st place on Youtube Platform.
* The entertainment category comes after the music category.

# Model Visualizations

Data:

![Screenshot 2022-07-23 124055](https://user-images.githubusercontent.com/100412728/180944703-d4504e57-47ac-4276-9337-3054b7b09be2.png)

![Screenshot 2022-07-23 124207](https://user-images.githubusercontent.com/100412728/180944713-fea44b98-f895-4ec6-8eed-061b737f3c0e.png)

![Screenshot 2022-07-23 124308](https://user-images.githubusercontent.com/100412728/180944723-bc4ed3a1-55aa-4253-9e28-d238f95f9cfe.png)

![Screenshot 2022-07-23 124401](https://user-images.githubusercontent.com/100412728/180944733-d28d578f-2eed-449f-b0c8-2a818a31f46f.png)

![Screenshot 2022-07-23 124436](https://user-images.githubusercontent.com/100412728/180944749-01eee641-f0e0-4afd-9a92-cfc260d2f8bb.png)

![Screenshot 2022-07-23 124524](https://user-images.githubusercontent.com/100412728/180944773-30f23397-3490-4381-bfd0-5111818200fb.png)

Heatmaps updates: <br/>

<img width="464" alt="image" src="https://user-images.githubusercontent.com/47862474/197239840-cedf4231-d013-45c2-957d-a0836a3658df.png">

New dataframe updates: <br/>

<img width="993" alt="image" src="https://user-images.githubusercontent.com/47862474/197239928-51b374f0-0de7-4c31-b175-a031342de51a.png">

