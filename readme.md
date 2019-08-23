# WeRateDog
WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. In this project I gathered data from a variety of sources and in a variety of formats, assess its quality and tidiness, clean(wrangling and analyze) it by using Python and its libraries, then reporting on the data wrangling efforts and data analyses and visualizations.

## Date created
- README file: Aug-23-2019

- Project: June-20-2019

## Software Requirements

- Jupyter Notebook
- pandas
- NumPy
- requests
- tweepy
- json


## Dataset

- Enhanced Twitter Archive  
Download the file manually by clicking the following link: [twitter_archive_enhanced.csv](https://d17h27t6h515a5.cloudfront.net/topher/2017/August/59a4e958_twitter-archive-enhanced/twitter-archive-enhanced.csv)


- Image Predictions File  
 Download it programmatically by using the Requests library and the link: [URL](https://d17h27t6h515a5.cloudfront.net/topher/2017/August/599fd2ad_image-predictions/image-predictions.tsv).

- Additional Data via the Twitter API  
I queried the Twitter API for each tweet's JSON data using the tweet IDs in the WeRateDogs Twitter archive with the help of Python's Tweepy library, and then stored each tweet's entire set of JSON data in the _tweetjson.txt_ file file.


## Data Assessing and Cleaning
- Detected and documented the quality issues and tidiness issues by assessing the gathered data visually and programmatically.

- Cleaned each of the documented issues above and got the high quality and tidy master pandas DataFrames.Cleaned each of the documented issues above and got the high quality and tidy master pandas DataFrames.

##  Interesting Findings
- **Charlie'** is a very popular name for dogs!
- Higher rate  ≠ More popular
- **Puppo** are the **BEST**!
- Who is the top retweet count and favorite count dog?  
 _Find out in the **act_report.ipynb** or **wrangle_act.ipynb**_




## Credits
The data files and programming instructions are provided by Udactiy's [Data Analyst Nanodegree Program](https://eu.udacity.com/course/data-analyst-nanodegree--nd002). :bowtie:
