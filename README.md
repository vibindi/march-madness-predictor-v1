# Predicting the 2024 March Madness Bracket using an Adaboost Machine Learning Model

## Background 🚀
As March Madness approaches each year, college basketball fans eagerly wait for the bracket to be released so that they can theorize and create bracket predictions of their own. Of course, there are many ways to create a bracket. You can base it off of gut feeling, expert opinions, team colors, or randomization. However, I wanted to explore whether or not I could use past and previous statistics to determine the outcome of this year’s tournament.

## Tech Stack 📚
For the following project, I used: **Python, scikit-learn, Pandas, and Tableau**.

## Process 🔀
1. Collect past tournament and season data (up until 1985).
2. Explore the data and engineer the features required. This includes creating dummy variables.
3. Create a model to use and test said model.
4. Collect this years bracket and season data.
5. Iteratively run the model for each round (game-by-game).
6. Evaluate and display results.

## Data Collection 💾
To collect my data, I used web scraping to retrieve information from [sports-reference.com](https://www.sports-reference.com/cbb/). Of course, to do so ethically and to relieve any potential load on the website’s end, I web scraped in batches and with time breaks in between.

## Data Exploration 🔎
While exploring the data, the biggest thing that I wanted to explore was how certain factors affected the likelihood of upsets. Of course, it’s easy for the algorithm to detect high performers through past performance, but upsets tend to be a little more random. I used the following Tableau visualization to do so. In the end, however, I did not end up actually creating any features to represent upset probability. The Tableau visualization can be found here.

