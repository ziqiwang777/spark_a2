# COMP5349-Assignment2

1. You need install some necessary modules and set some configuration in server.
  + sudo python -m nltk.downloader -d /home/hadoop/nltk_data "punkt"
  + sudo pip-3.6 install --quiet tensorflow-hub
  + sudo pip-3.6 install --quiet numpy

2. Open the Notebooks connected with cluster to run the 5349a2.ipynb.
  + you need to change the store_route in ml_tils to your S3 folder path such as (store_route = "s3://5349a2/")
<br>This store_route is decided the path of the data stored. There are some data will be stored for reduce useless repeating calculation.
 



<br>
Thx for your reading!<br>
