The project involved the analysis of dining reviews from various restaurants by processing a CSV file containing different columns such as Restaurant, Reviewer, Review, Rating, Metadata, Time, and Pictures. The goal was to conduct a comprehensive analysis by transforming the existing columns into new ones and subsequently building a multiclass neural network model to predict restaurant ratings based on various features.

The process included various steps:

Data Processing and Feature Extraction:

Extracted features such as Review_Word_Count, neg, neu, pos, compound, Year, Month, Day, DayOfWeek, ReviewCount, FollowerCount, Average_Rating, Rating_Std_Dev, Cleaned_Review from the existing data columns.
The 'Review' column was analyzed for sentiment through sentiment analysis (polarity score, word count, etc.).
Other columns were processed to extract relevant information and new features.
Visualization:

Plotted different visualizations to analyze the data distribution and relationships between variables. These visualizations might include histograms, scatter plots, line plots, and box plots to explore relationships between features.
Modeling:

Built a multiclass neural network model using features such as Review sentiment scores (neg, pos, compound), Average_Rating, and Rating_Std_Dev to predict restaurant ratings.
Addressed class imbalance to ensure the model's ability to predict across different classes.
Evaluation:

Used a confusion matrix to evaluate the performance of the model.
Despite class imbalance within the dataset, the model achieved a significant level of accuracy, indicating that it could predict restaurant ratings effectively based on the provided features.
This project involved a detailed analysis of dining reviews, extensive feature engineering, visualizations to understand data distributions, and the application of a multiclass neural network for predicting restaurant ratings. The noteworthy aspect of the project was achieving a reasonable level of accuracy even in the presence of class imbalance within the dataset.
