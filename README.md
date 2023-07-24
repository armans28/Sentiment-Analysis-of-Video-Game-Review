# Sentiment Analysis of Video Game Review

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


## Dataset Source

You can get the data from [Video Game Dataset](https://cseweb.ucsd.edu/~jmcauley/datasets/amazon_v2/).  In this case we are only using [Review Dataset](https://datarepo.eng.ucsd.edu/mcauley_group/data/amazon_v2/categoryFiles/Video_Games.json.gz).
Choose the `Video Games`

![image](https://github.com/armans28/Beauty-Product-Recommendation-System/assets/119162844/7f88378e-2fd6-4e97-8727-93f142f14807)


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
