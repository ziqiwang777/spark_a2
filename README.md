# Read Me 

This project works on the online review data set released by Amazon and go through various analytic phases, including getting summary statistics, removing unwanted data and performing similarity analysis. 

### The whole prokect includes four stages:
* ***Stage1*** : Overall statistics
* ***Stage2*** : Filtering Unwanted Data
* ***Stage3*** : Similarity analysis with Sentence Embedding
* ***Stage4*** : Similarity analysis with Spark supported Feature 


### About code
	
1. You need to create a cluster in amazon cloud with tensorflow, hadoop, spark. After that install some necessary modules and set some configuration in server use following command orders.
  + sudo python -m nltk.downloader -d /home/hadoop/nltk_data "punkt"
  + sudo pip-3.6 install --quiet tensorflow-hub
  + sudo pip-3.6 install --quiet numpy

2. Open the Notebooks connected with cluster to run the 5349a2.ipynb.
  + you need to change the store_route in ml_tils to your S3 folder path such as (store_route = "s3://5349a2/")
<br>This store_route is decided the path of the data stored. There are some data will be stored for reduce useless repeating calculation.
 



<br>
Thx for your reading!<br>

