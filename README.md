---
# AI-sentiment-analysis-of-comments

"AI-sentiment-analysis-of-comments" automates sentiment analysis of movie reviews, providing insightful visual representations of public opinion on films. This project harnesses IMDB comments, analyzing them to classify sentiments as positive, negative, or neutral, and displays the results through intuitive graphs.

## Features
- **Automated Review Collection**: Efficiently gathers movie reviews from IMDB.
- **Sentiment Analysis**: Analyzes reviews to determine if sentiments are positive, negative, or neutral.
- **Graphical Results Display**: Visualizes analysis outcomes, offering an at-a-glance understanding of public opinion.

## Demo

<img width="400" alt="スクリーンショット 2024-03-18 22 22 56" src="https://github.com/ShotaNakahata/AI-sentiment-analysis-of-comments/assets/156826073/79fcb719-6782-47d7-8421-9d3bd2e3d7cc">


## Requirements
### Front-end Technologies

* **HTML**: Structures the content of the web application.
* **CSS**: Styles the interface of the web application.
* **Bootstrap**: A framework for quickly and easily building responsive and mobile-first websites.
### Back-end Technologies

* **Python**: The core programming language used for server-side logic.
* **Flask**: A micro web framework written in Python for building web applications.
* **Pandas**: Used for data manipulation and analysis, especially for processing input data before and after sentiment analysis.
* **Matplotlib**: Generates visualizations of the sentiment analysis results to be served to the front end.
* **NLTK** (Natural Language Toolkit): A leading platform for building Python programs to work with human language data, utilized here for performing sentiment analysis on movie reviews.
## Installation

To set up the necessary environment:

```bash
pip install Flask pandas matplotlib nltk
```

## Usage

Clone the project and run the application:

```bash
git clone https://github.com/yourgithub/ai-sentiment-analysis-of-comments.git
cd ai-sentiment-analysis-of-comments
python app.py
```

## Future Directions

In upcoming updates, we plan to introduce the capability for users to freely select the site they wish to scrape by pasting its link. This enhancement will not only extend our project's flexibility beyond IMDB but also allow for a broader range of sources to be analyzed for sentiment.

Furthermore, we aim to enrich the display of scraping results by automatically generating textual descriptions alongside the numerical data. This feature will provide users with a summary of the analysis outcomes, making the insights more intuitive and accessible. By integrating textual summaries with our graphical and numerical results, we strive to deepen user understanding of the sentiment analysis, offering a more comprehensive view of public opinions on movies.
