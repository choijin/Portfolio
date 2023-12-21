# My Project Portfolio

## [Project 1: NLP Text Stock Prediction](https://choijin.github.io/NLP_Text_Stock_Prediction/)

Stock Price Prediction project leveraging LSTM and BERT models to analyze context from daily news headlines for forecasting stock movements.
* Aggregated and processed over 100,000 news articles, aligning them with historical stock data from the S&P 500.
* Developed a baseline LSTM model using stock data, and an advanced hybrid model combining LSTM with BERT embeddings of news headlines.
* Implemented a custom tokenization strategy to handle BERT's token limit, creating daily news embeddings that represents the context for each day.
* Evaluated model performance with AUC scores, and improved upon a baseline model (0.43 to 0.59).

![](/images/nlp_text_stock_prediction.png)

## [Project 2: Loan Underwriting](https://choijin.github.io/Loan_Underwriting/)

Developed a logistic regression model to predict the one-year Probability of Default (PD) for prospective borrowers to enhance the bank's loan underwriting process.
* Trained a logistic regression model on historical bank transaction data to forecast default probabilities, emphasizing model explainability.
* Engineered financial features like liquidity, debt coverage, and profitability, and handled missing data through finance-based and median imputation.
* Performed feature selection using univariate and multivariate analysis, and addressed multicollinearity using Variation Inflation Factor (VIF).
* Implemented walk-forward analysis and calibration for model evaluation, achieving an AUC of 0.7761, significantly improving upon a baseline model (AUC of 0.701).

![](/images/loan_underwriting.png)

## [Project 3: NLP Topic Modeling](https://choijin.github.io/NLP_Topic_Modeling/) 

NLP project using Latent Dirichlet Allocation (LDA) to perform topic modeling on text data scraped from a news website, further refining the LDA topics to find nuanced groupings by incorporating K-means clustering and BERT model. 
* Webscraped and collected news articles and stored it in Amazon S3.
* Performed topic modeling utilizing LDA model and improved upon baseline applying K-means Clustering and BERT.
* Evaluated its performance using various metrics such as topic coherence and silhouette score.
* Visualized the word importance per topic and summarized each articles using BART.

![](/images/nlp_pipeline.png)

## [Project 4: Music Recommender System](https://choijin.github.io/Music_Recommender_System/) 

Big data project using PySpark to extract and transform large-scale music listening data stored in HDFS and build a collaborative-filter based recommender system
* Developed a collaborative filtering recommender system using Alternating Least Squares (ALS) model
* Evaluated the model against a popularity baseline model
* Used Mean Average Precision at K (MAP@K) metric for performance assessment
* The ALS model outperformed the popularity baseline model and resulted in a 16.7x improvement in MAP@100.

## [Project 5: Twitter Data Pipeline](https://choijin.github.io/Twitter_Data_Pipeline_ETL/) 

Data engineering project using Airflow to perform ETL process on Twitter data and executing tasks inside Docker containers
* Executed data extraction utilizing Twitter API calls (Tweepy)
* Transformed JSON data into CSV using Python scripts and libraries (Pandas, JSON)
* Loaded the processed data into AWS S3 buckets for storage using Python SDK (boto3)
* Orchestrated the ETL process by implementing Airflow and operated the tasks inside Docker to ensure a controlled and isolated environment, resulting in improved development and testing processes as well as facilitating faster deployment.

![](/images/twitter_pipeline.png)

## [Project 6: Health Insurance Premium Price Analysis](https://choijin.github.io/Health_Insurance_Analysis/) 

Analysis of health insurance premium data using causal inference and machine learning methods
* Conducted power analysis and hypothesis testing to identify relationships between features
* Compared LASSO regression, Ridge regression, and Elastic net regression to identify the regularized regression model that will perform best prediction
* Performed PCA, K-Mean's clustering and XGBoost classifier to create the decision tree to determine one’s diabetes status

![](/images/age_distribution.png)

## [Project 7: Bank Customer Segmentation Dashboard](https://choijin.github.io/Bank_Customer_Dashboard/) 

Analysis of dummy bank customer data from United Kingdom
* Customizable balance band and age band, interactive filters upon clicking figures
* Segmented the customer distributions according to their age, bank balance, location, and gender
* Created an interactive dashboard to derive business insights

![](/images/bank_dashboard.png)

## [Project 8: Data Analysis on Research Text Data](https://choijin.github.io/Data_Analysis_Research/)  

Exploratory data analysis on research grant data retrieved from National Science Foundation 
* Transformed XML formatted non-relational data into a tabular relational data format
* Pre-processed the data by removing any stopwords and missing data
* Performed text analysis using libraries (such as PlaintextCorpusReader and BigramCollocationFinder) to segment the text into single word, two-worded and three-worded phrases and counting its frequencies
* Used various machine learning algorithms (KMeans Clustering, XGBoost, Random Forest, NetworkX) to draw insights

## [Project 9: Additional Tableau Project](https://public.tableau.com/app/profile/jin.choi8484/viz/NYCParkCrime_16744573706270/NYCRates) 

Analysis of crime incidents occurring at New York City (NYC) parks to promote for safer parks. You can customize the county and view the parks along with their crime report incidents.

* Conducted data pre-processing after importing a PDF data file
* Combined the PDF data with spatial files using inner join (on park names)
* Designed an attention-grabbing visualisation which can be used to motivate for more police patrols in NYC public parks.
