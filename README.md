# Sentiment Analysis of Video Game Review
To view the user's portfolio blog on the Sentiment Analysis of Video Game Review, please visit [My Blog](https://danielrs.systeme.io/sentiment-analysis-of-video-game-review) to see the explanation of the notebook.

Due to the use of `plotly.express` and `plotly.graph_objects`, the visualizations in this code cannot be displayed on GitHub. To view the visualizations, please download the code and run it on your local machine.

## Dataset Information

Here's a table with the column names and descriptions for the `user_data` DataFrame:

| Column Name | Description |
| --- | --- |
| overall | The overall rating given by the reviewer, on a scale of 1 to 5 |
| verified | Whether the reviewer is a verified purchaser of the product |
| reviewTime | The date and time the review was posted |
| reviewerID | A unique identifier for the reviewer |
| asin | A unique identifier for the product |
| reviewerName | The name of the reviewer |
| reviewText | The full text of the review |
| summary | A brief summary of the review |
| unixReviewTime | The date and time the review was posted, in Unix time format |
| vote | The number of helpful votes the review received |
| style | Additional information about the product |
| image | A URL to an image of the product |

This table lists all of the columns in the `user_data` DataFrame, along with a brief description of each column.

After that, a new column is created, namely "sentiment," where ratings above 3 are labeled as `positive`, ratings below 3 as `negative`, and ratings equal to 3 as `neutral`. Then, only two columns are selected, namely "reviewText" and "sentiment."
GitHub Copilot: Sure, here's a table with the column names and descriptions for the `user_data` DataFrame, specifically for the `reviewText` and `sentiment` columns:

| Column Name | Description |
| --- | --- |
| reviewText | The full text of the review, written by the reviewer |
| sentiment | The sentiment label assigned to the review based on the overall rating, either "POSITIVE", "NEGATIVE", or "NEUTRAL" |

## Usage

Here's a table with the file names and descriptions for the files used in the video game sentiment analysis project:

| File Name | Description |
| --- | --- |
| lr.pkl | A serialized file containing a trained logistic regression model for sentiment analysis |
| nb.pkl | A serialized file containing a trained Naive Bayes model for sentiment analysis |
| svm.pkl | A serialized file containing a trained support vector machine model for sentiment analysis |
| Video Game Sentiment Analysis.ipynb | A Jupyter Notebook containing the code used to preprocess the data, train the models, and evaluate the performance |
| vectorizer.pickle | A serialized file containing a trained CountVectorizer object for text vectorization |

This table lists the file names and descriptions for the files used in the video game sentiment analysis project. The `lr.pkl`, `nb.pkl`, and `svm.pkl` files contain serialized versions of trained machine learning models for sentiment analysis. The `Video Game Sentiment Analysis.ipynb` file is a Jupyter Notebook containing the code used to preprocess the data, train the models, and evaluate the performance. The `vectorizer.pickle` file contains a serialized version of a trained CountVectorizer object for text vectorization.
## Dataset Source

You can get the data from [Video Game Dataset](https://cseweb.ucsd.edu/~jmcauley/datasets/amazon_v2/).  In this case we are only using [Review Dataset](https://datarepo.eng.ucsd.edu/mcauley_group/data/amazon_v2/categoryFiles/Video_Games.json.gz).
Choose the `Video Games`

![image](https://github.com/armans28/Sentiment-Analysis-of-Video-Game-Review/assets/119162844/ca2ceeb9-43d9-419d-82e1-cb54096dc2a6)



## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
