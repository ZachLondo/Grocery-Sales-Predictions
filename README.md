# Grocery Sales Predictions

Establishing a model to predict sales for a grocery chain
Author: Zach Londergan

Business problem:
My goal was to establish a model that would help to predict future overall sales for various locations of a grocery chain.

Data:
The data is a market basket of products from different locations, segmented by factors such as the size of the grocery store, price of the item, and overall sales for that location, etc.

Methods:
- No duplicated data and only two columns with missing data
- Replaced missing data in 'Item Weight' with the average as there was not much variance among the weight overall.
- There was missing data for 'Outlet Size.' I believe creating a new category will offer the best solution as it will allow me to retain the data without skewing a potentially useful column with faulty inputs.

Results

Item Sales by outlet type:

![image](https://user-images.githubusercontent.com/100807032/166812479-89a26ddc-7692-4c74-aede-3b8f7a358da7.png)

From this visual, we can see the distribution of sales among the various kinds of stores this grocery chain has.

Distribution of item prices:

![image](https://user-images.githubusercontent.com/100807032/166812786-6af0ada4-3c13-4c0a-8395-57596db7cfd4.png)

From this visual, we can see that there was a good distribution of the prices of products picked for the market basket.

Recommendations:

The regression tree model was the best fit for predicting sales based on the given data. The R2 for this was optimized at 0.604207 and 0.596056 for training and testing data, respectively.

Limitations & Next Steps:
The main limitations would be in the replaced data. Ideally, I would be able to talk with an expert in the field or someone that collected this data in order to better identify what to do with the missing data. 

For further information
For any additional questions, please contact email
