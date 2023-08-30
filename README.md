# My Project Portfolio

## [Project 1: NLP Topic Modeling](https://choijin.github.io/NLP_Topic_Modeling/) 

NLP project using text data web-scraped from news website. Used Latent Dirichlet Allocation (LDA) to perform topic modeling, refined the LDA topics and find nuanced groupings using K-means clustering and BERT model. 
* Webscrape and collect news articles and store in S3.
* Perform topic modeling using LDA model and improve upon baseline using K-means Clustering and BERT.
* Evaluate its performance using various metrics such as topic coherence and silhouette score.
* Visualize the word importance per topic and summarize each articles using BART.

![](/images/nlp_pipeline.png)

## [Project 2: Music Recommender System](https://choijin.github.io/Music_Recommender_System/) 

Big data project using PySpark to extract and transform large-scale music listening data stored in HDFS and build a collaborative-filter based recommender system
* Develop a collaborative filtering recommender system using Alternating Least Squares (ALS) model
* Evaluate the model against a popularity baseline model
* Use Mean Average Precision at K (MAP@K) metric for performance assessment
* The ALS model outperformed the popularity baseline model and resulted in a 16.7x improvement in MAP@100.

## [Project 3: Twitter Data Pipeline](https://choijin.github.io/Twitter_Data_Pipeline_ETL/) 

Data engineering project using Airflow to perform ETL process on Twitter data and executing tasks inside Docker containers
* Executed data extraction utilizing Twitter API calls (Tweepy)
* Transformed JSON data into CSV using Python scripts and libraries (Pandas, JSON)
* Loaded the processed data into AWS S3 buckets for storage using Python SDK (boto3)
* Orchestrated the ETL process by implementing Airflow and operated the tasks inside Docker to ensure a controlled and isolated environment, resulting in improved development and testing processes as well as facilitating faster deployment.

![](/images/twitter_pipeline.png)

## [Project 4: Health Insurance Premium Price Analysis](https://choijin.github.io/Health_Insurance_Analysis/) 

Analysis of health insurance premium data using causal inference and machine learning methods
* Conducted power analysis and hypothesis testing to identify relationships between features
* Compared LASSO regression, Ridge regression, and Elastic net regression to identify the regularized regression model that will perform best prediction
* Performed PCA, K-Mean's clustering and XGBoost classifier to create the decision tree to determine one’s diabetes status

![](/images/age_distribution.png)

## [Project 5: Bank Customer Segmentation Dashboard](https://choijin.github.io/Bank_Customer_Dashboard/) 

Analysis of dummy bank customer data from United Kingdom
* Customizable balance band and age band, interactive filters upon clicking figures
* Segmented the customer distributions according to their age, bank balance, location, and gender
* Created an interactive dashboard to derive business insights

![](/images/bank_dashboard.png)

## [Project 6: Data Analysis on Research Text Data](https://choijin.github.io/Data_Analysis_Research/)  

Exploratory data analysis on research grant data retrieved from National Science Foundation 
* Transformed XML formatted non-relational data into a tabular relational data format
* Pre-processed the data by removing any stopwords and missing data
* Performed text analysis using libraries (such as PlaintextCorpusReader and BigramCollocationFinder) to segment the text into single word, two-worded and three-worded phrases and counting its frequencies
* Used various machine learning algorithms (KMeans Clustering, XGBoost, Random Forest, NetworkX) to draw insights

## [Project 7: Additional Tableau Project](https://public.tableau.com/app/profile/jin.choi8484/viz/NYCParkCrime_16744573706270/NYCRates) 

Analysis of crime incidents occurring at New York City (NYC) parks to promote for safer parks. You can customize the county and view the parks along with their crime report incidents.

* Conducted data pre-processing after importing a PDF data file
* Combined the PDF data with spatial files using inner join (on park names)
* Designed an attention-grabbing visualisation which can be used to motivate for more police patrols in NYC public parks.
