Motivation and Goal: 

As the entertainment industry grows, predicting a movie’s success is vital for content platforms and production companies.
Success is typically measured by revenue, budget, and audience reception. Accurate prediction is challenging due to factors like budget, genre, release
time, and audience engagement. By analyzing historical data, teams can identify patterns that guide investments, marketing, and content strategies.
This project aims to develop classification models, including Logistic Regression, Random Forest, Decision Trees, Gradient Boosting, Neural
Networks, LDA, QDA, and Naive Bayes, to predict movie success. It also focuses on feature selection and model interpretation using methods like
SHAP, Recursive Feature Elimination, cross-validation, and partial dependence plots. Key features analyzed include budget, release year, runtime, and
popularity. The ultimate goal is to create a high-accuracy model that helps stakeholders make data-driven decisions and understand the factors behind
movie success.

Process: 

We began by scraping the web for an interesting dataset and defining our research goals. After selecting the Horror dataset, we cleaned
it by removing outliers and NA values. Feature engineering included creating boolean columns, converting categorical variables to factors, and
defining our target variable, success, based on whether profit (revenue - budget) was greater than zero. We analyzed correlations, conducted
exploratory data analysis using visualizations, and split the data into training (60%) and testing (40%) sets. A normalized dataset was also prepared for
specific classification methods. Models were fitted, predictions made, and evaluations performed, including PDP plots. Feature selection and predictor
comparisons were conducted using various techniques. Collaboration was managed through a shared GitHub repository. Each person worked on
sections, committing and pushing changes, while the other pulled updates to continue work. Weekly meetings were held to review progress, provide
feedback, and make edits.

Data: 

The dataset, scraped from TidyTuesday, contains information on ~32,540 horror movies dating back to the 1950s, sourced from
"The Movie Database" via the tmdb API. It includes 20 variables detailing movie performance, reception, and themes. These features will train a
classification model to predict movie success, focusing on identifying key predictors for accurate classification.

Data Dictionary: 

1. The release date variable is a date field that records the date when the movie was first released.
2. The popularity variable is a numerical value representing the movie’s popularity score based on audience interactions.
3. The budget variable is an integer field capturing the movie’s production budget in USD.
4. The revenue variable is an integer field indicating the total revenue earned by the movie in USD.
5. The runtime variable is an integer field that specifies the duration of the movie in minutes.
