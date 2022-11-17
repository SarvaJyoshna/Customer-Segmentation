# Customer-Segmentation
**Motivation:**
My brother wanted to sell his old phone, but we had no idea whom to sell it. He wanted to sell his phone for the best possible price. That is when I started this project. It is important to know about the people whom you are selling the product to, so that you can gain profit. That is when I started this project. customer segmentation is necessary for knowing what characteristics that exist on each customer.

**Tools/technologies/methodologies:**
Firstly, we gather the data. The dataset used here is a transactional data. After we sample the data, we will make the data easier to conduct an analysis. We have to perform RFM (Recency Frequency Monetary) segmentation. RFM table is made by creating some columns. Then, we have to pre-process the data as the dataset is not ready yet. 
The data should meet assumptions where the variables are not skewed and have the same mean and variance. Data needs to be transformed., so it has a more symmetrical form. Then we manage skewness by using box-cox transformation. To make sure, we calculate each variable using the skew function. Then, we interpret skewness value. Based on that calculation, we use variables that use box-cox transformations. Except for the MonetaryValue variable because the variable includes negative values. 
To handle this variable, we can use cubic root transformation to the data. By using the transformation, we will have data that less skewed. Then RFM table is transformed. Then, we have to normalize it. To normalize, we can use StandardScaler object from scikit-learn library to do it. Finally, we can do clustering using that data.
After pre-processing the data, we perform modelling. For data segmentation, we can use K-Means algorithm. We can use the K-Means function from scikit-learn to do this. To obtain maximum clustering performance, we have to determine which hyperparameter fits to the data, which can be done using elbow method. Now, we can fit the model. By fitting the model, we can have clusters where each data belongs. By that, we can analyze the data. 
We can summarize the RFM table based on clusters and calculate the mean of each variable. We can have clusters where each data belongs. Besides that, we can analyze the segments using snake plot. By using this plot, we can have a good visualization from the data on how the cluster differs from each other. By using this plot, we know how each segment differs.
The order of major steps that we perform in the project are as follows:
1.	Gather the data
2.	Create Recency Frequency Monetary (RFM) table
3.	Manage skewness and scale each variable
4.	Explore the data
5.	Cluster the data
6.	Interpret the result

**Skills gained (technical and otherwise):**
I was able to draw useful insights that helps us in our day-to-day life and help us in leading a better life by making right decisions at the right time. I’ve learnt creating RFM table, managing skewness and scale of each variable, clustering the data, and applying K-Means algorithm.

**Impact/obstacles:**
This project taught me that we can analyse and draw insights from almost any situation in our day-to-day life. With that, we can make better decisions and lead a better life with more savings. 
