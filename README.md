# GameReviewSentimentAnalysis
This project analyzes user-written game reviews to determine whether the user recommends the game or not. The main objectives include preprocessing a review dataset, visualizing distributions, and evaluating various classification models for performance comparison.

##  Dataset
- **Source:** `train.csv`
- **Columns:**
  - `review_id`: Unique identifier for each review.
  - `title`: Title of the game.
  - `year`: Release year.
  - `user_review`: Text of the review.
  - `user_suggestion`: Binary label (1 = recommended, 0 = not recommended)

## Exploratory Data Analysis
- Histogram showing the distribution of user suggestions.
- Pie chart to visualize the proportion of positive vs. negative recommendations.
- Bar chart showing the number of samples after filtering and train-test splitting.

## Machine Learning Models Evaluated
The following models were tested to classify whether a review suggests the game:
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Random Forest
- Decision Tree
- Linear Regression
- Multinomial Naive Bayes
- Bernoulli Naive Bayes

## Evaluation Metrics
Models were compared using:
- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**

Bar charts were created to visualize and compare these metrics for all models.

## Key Insights
- Naive Bayes models showed high precision but moderate recall.
- KNN had balanced performance.
- Visualizations helped to highlight trade-offs between models.
