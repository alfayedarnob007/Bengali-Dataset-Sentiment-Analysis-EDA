# Bengali-Dataset-Sentiment-Analysis-EDA
As my traing and testing dataset, I have used the Bengali Dataset from a research paper where they have curated publicly available data from the internet: 
Indian Language tweet posts, cricket and restaurant based comments, several newspapers, TV news, books, blogs, and social media, youtube channel comments and social media posts.

I trained different Machine learning classical algorithm models to detect sentiments
(positive, negative and neutral) for each of the Bengali sentences.
The models were NB Bernoulli ,Linear SVC model, Logistic Regression Model and Random Forest Model and compared the results among them inorder to find the model with 
the best confusion matrix.

Here I mainly focused on Exploratory Data Analyis (EDA) and data visualization to get more insights in our dataset.
Generated meta features - 1. Difference In Number Of words of Selected_text and Text
                          2. Jaccard Similarity Scores between text and Selected_text

Preprocessed and cleaned the data - 
● Removed stopped words  
● Remove text in square brackets.
● Remove links.
● Remove punctuation.
● Remove words containing numbers.
● Replacing same letters in sequence- more than twice into just double letter

Used different methods to visualize our data before and after prepossing. 
Visualizations used such as word clouds , kernel distribution graph, bar diagram , funnel charts, tree of unique words/common words, sentiment wise differences etc.

I have another similar project in my repository where i did sentiment analysis on English Twitter dataset. The main purpose for me to do this project was out of the curiosity to figure out how it felt to work with Bengali Dataset and what dificulties or variations I had to face.



