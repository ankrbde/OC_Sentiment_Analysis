# OC_Sentiment_Analysis
Repository to hold google colab notebook to do sentiment analysis as an internal project to scrape reviews from google play store for NHS app.

### This notebook works using the libraries as below:

[Google play scraper](https://pypi.org/project/google-play-scraper/) - To scrape reviews from Google playstore

[Transformers](https://huggingface.co/docs/transformers/en/index) - [pip install transformers](https://pypi.org/project/transformers/)

[Plotly](https://plotly.com/python/) - Open source Graphing library for Python

### Below are some of the packages used:

[Pandas](https://pandas.pydata.org/) for dataframes

[Numpy](https://numpy.org/) - for working with arrays


## How to use
* Download the "sentiment_analysis_nhs.ipynb" file on your device.
* Open [Google colab](https://colab.research.google.com/) in any browser and you have a introductory page.
* Go to File -> Upload Notebook -> Sign in to your google account
* Once you have an Open Notebook overlay opened, select the downloaded file from you device
* Your file will be loaded on the Google colab
* Go to Runtime -> Run all

## Output

On completion of above steps,  will take roughly 10 mins to download an output csv file which will have a report for sentiment analysis done for the latest 1000 reviews from the NHS App(Google play store)

Report will have 2 customised columns 'sentiment' and 'result score' which are the outcome of the sentiment analysis done. You can also have a look at the column 'score' which tell how much ratings user gave for the review.


## Useful links

[Introduction to using transformers and hugging face](https://www.datacamp.com/tutorial/an-introduction-to-using-transformers-and-hugging-face)

[How transformers work](https://www.datacamp.com/tutorial/how-transformers-work?dc_referrer=https%3A%2F%2Fwww.google.com%2F)

Alternative to Plotly - [Matplotlib](https://matplotlib.org/)
