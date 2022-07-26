# Trending-Youtube-Video-Statistics

# Problem Statement
Simplified the Trending list with the basis of given data and tell which industry comes in trending list.

* Main Code: https://github.com/piyush033/Trending-Youtube-Video-Statistics/blob/main/Trending-Youtube-Video-Statistics-checkpoint.ipynb 

# Table of Content
* [Problem Statement](https://github.com/piyush033/Time-Series-Data-Project/blob/main/README.md#problem-statement)
* [Dataset Used](https://github.com/piyush033/Time-Series-Data-Project/blob/main/README.md#dataset-used)  
* [Frameworks Used](https://github.com/piyush033/Time-Series-Data-Project#frameworks-used)
* [Bulldozer Data Dictionary](https://github.com/piyush033/Time-Series-Data-Project#bulldozer-data-dictionary)
* [Model Visualizations](https://github.com/piyush033/Time-Series-Data-Project#model-visualizations)

# Dataset Used 
The original data come from [Kaggle Trending YouTube Video Statistics](https://www.kaggle.com/datasets/datasnaek/youtube-new).

You can find this also in my repository: https://github.com/piyush033/Trending-Youtube-Video-Statistics/tree/main/Data 

# Frameworks Used

* Numpy
* Pandas
* Scikit-Learn
* Matplotlib
* Seaborn

# Trending YouTube Video Statistics Data Dictionary

## Context
YouTube (the world-famous video sharing website) maintains a list of the top trending videos on the platform. According to Variety magazine, “To determine the year’s top-trending videos, YouTube uses a combination of factors including measuring users interactions (number of views, shares, comments and likes). Note that they’re not the most-viewed videos overall for the calendar year”. Top performers on the YouTube trending list are music videos (such as the famously virile “Gangam Style”), celebrity and/or reality TV performances, and the random dude-with-a-camera viral videos that YouTube is well-known for.

This dataset is a daily record of the top trending YouTube videos.

Note that this dataset is a structurally improved version of this dataset.

## Content
This dataset includes several months (and counting) of data on daily trending YouTube videos. Data is included for the US, GB, DE, CA, and FR regions (USA, Great Britain, Germany, Canada, and France, respectively), with up to 200 listed trending videos per day.

EDIT: Now includes data from RU, MX, KR, JP and IN regions (Russia, Mexico, South Korea, Japan and India respectively) over the same time period.

Each region’s data is in a separate file. Data includes the video title, channel title, publish time, tags, views, likes and dislikes, description, and comment count.

The data also includes a category_id field, which varies between regions. To retrieve the categories for a specific video, find it in the associated JSON. One such file is included for each of the five regions in the dataset.

For more information on specific columns in the dataset refer to the column metadata.

## Acknowledgements
This dataset was collected using the YouTube API.

## Inspiration
Possible uses for this dataset could include:

* Sentiment analysis in a variety of forms
* Categorising YouTube videos based on their comments and statistics.
* Training ML algorithms like RNNs to generate their own YouTube comments.
* Analysing what factors affect how popular a YouTube video will be.
* Statistical analysis over time.

For further inspiration, see the kernels on this dataset!

# Model Visualizations

Data:

![Screenshot 2022-07-23 124055](https://user-images.githubusercontent.com/100412728/180944703-d4504e57-47ac-4276-9337-3054b7b09be2.png)

![Screenshot 2022-07-23 124207](https://user-images.githubusercontent.com/100412728/180944713-fea44b98-f895-4ec6-8eed-061b737f3c0e.png)

![Screenshot 2022-07-23 124308](https://user-images.githubusercontent.com/100412728/180944723-bc4ed3a1-55aa-4253-9e28-d238f95f9cfe.png)

![Screenshot 2022-07-23 124401](https://user-images.githubusercontent.com/100412728/180944733-d28d578f-2eed-449f-b0c8-2a818a31f46f.png)

![Screenshot 2022-07-23 124436](https://user-images.githubusercontent.com/100412728/180944749-01eee641-f0e0-4afd-9a92-cfc260d2f8bb.png)

![Screenshot 2022-07-23 124524](https://user-images.githubusercontent.com/100412728/180944773-30f23397-3490-4381-bfd0-5111818200fb.png)
