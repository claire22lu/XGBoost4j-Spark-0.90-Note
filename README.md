# XGBoost4j-Spark-0.90-Note

Study note for XGBoost4j-Spark v0.90. (From a DS with no prior experience with Scala or Spark.)

Reference: https://xgboost.readthedocs.io/en/latest/jvm/xgboost4j_spark_tutorial.html

1. Setup XGBoost4j 0.90: 

> - 0.90 works with spark 2.4+(despite the installation tutorial said 2.3+, the actual tutorial asked for 2.4+). I tried to work on a Windows machine using dll provided, but kept getting error in RabitTracker. Eventually I decided to work on Azure.

2. Setup Juypter Notebook: 

> - I used Juypter Notebook instead of Zeppline which is suggested by a co-worker. I think the main reason for choosing Juypter is because the version of Zeppline we have in our Azure cluster does not support importing external library.

