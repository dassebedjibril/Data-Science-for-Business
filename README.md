# Data-Science-for-Business: predict the sales in the future using Facebook Prophet. 

`Important: If you are unable to open the notebook kindly dowload it to your local PC. I couldn'd upload the second .csv file. find it here please https://www.kaggle.com/c/rossmann-store-sales/data`
For companies to become competitive and skyrocket their growth and sales, they need to leverage A.I. and machine learning to develop predictive models 
so they can be able to forecast sales in the future.

Predictive models attempt at forecasting future sales based on historical data while taking into account seasonality effects, demand, holidays,
promotions and competition. In this repo, you work as a data scientist in the sales department, and the sales team provided you with data from around 
eleven hundred approximately stores. The objective is to predict future daily sales based on some features such as stores, promotions, store size, school,
state holidays, distance away from competition, and 
what type of products do these stores carry? In this case study, we are going to learn many skills. Here are the main learning outcomes:

  -Understand how to leverage the power of data science to predict future product sales.
  
  -Understand the theory and intuition behind time series forecasting models.
  
  -Understand the theory behind Facebook prophet time series forecasting tools.
  
  -Understand the concept of additive regression.
  
  -List the advantages of Facebook prophet.
  
  -Apply Facebook prophet to predict future sales using real world data datasets.
  
  -Predict future weekly, monthly and yearly trends.

So companies right now, in order for them to become competitive and try to fuel and skyrocket their growth, they need to leverage AI and ML. So basically,
everyone right now in every single industry in health care, in business, in banking, in finance, anywhere, you will find that they leverage in ML.
And if you if you're following the news, basically, that's kind of the hype right now. Machine learning, deep learning, artificial intelligence. Companies,
In order to leverage that data, they need to develop some forecasting models. Think of it as now I have a lot of historical data and this data, we call it
a gold mine. Basically, if companies can leverage that data and fully understand all the kind of intrinsic information, within the data, they can multiply
their revenue by, a factor of two or three or and that would be like improvements in the revenue, in massive reductions in their expenses so they can
really optimize all their processes if these if they correctly, were able to leverage that data and actually develop an advanced and sophisticated AI and 
ML models. The sales people don't really know, like, you know, machine learning they don't know this aspect they just have the data collected and now you
basically have been hired to help the team to analyze that data and try to develop future of Time series forecasting models to try to predict the sales in
the future.

But the point here is that when the data is provided to you as a data scientist, it's actually provided to you in two formats. So you have two csv files. The first csv file consists of all the different transactions with around one million transactions approximately and that's basically the summary of all the features. There is another csv file that consists of store specific information. And that other file consists of around thousand entries, because if you remember, we have `1000 stores` that we are trying to analyze.

After this the data has been cleaned and we got rid of the missing valves. For more details, here is the notebook. Now we have this with no missing values.

We had two data frames the first one, which is our store info, that's the smaller data frame that has around 1000 samples in there, or thousand info about the stores. And we have a very unique ID in here, which is the store column. This is again, a unique ID specific to each store. The other data frame, which is our sales data frame that consists of around a million points. And there is, again, another ID, which is another column called Store. And again, that includes unique information related to the stores. We have to specify which column that we're going to be merging these two data frames based upon.
