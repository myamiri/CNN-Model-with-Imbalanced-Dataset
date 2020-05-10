# CNN-Model-with-Imbalanced-Dataset



# Problem

For banks, risk management and default detection have always been a crucial part in issuing credit cards. Defaults on credit card bill payment can result in a great financial loss. In order to reduce or even prevent loss of this kind, banks need to determine appropriately given credit for each specific client based on their information. Back in the great recession, many credit card issuers faced a credit card debt crisis. Card-issuing banks over-issued credit cards to unqualified applicants in order to gain market shares. At the same time, cardholders, irrespective of their repayment ability, overused credit cards for consumption purposes and accumulated heavy debts. This crisis caused a blow to consumer financial confidence and presented a big challenge for both banks and cardholders.



# Solution

This dataset is imbalanced and features in both classes have huge overlap. For dealing with the imbalanced dataset with using the advantage of having many samples, I used convolutional Neural Network using max pooling without and with undersampling.





# Data

The dataset contains the credit information from more than 30000 clients with multiple attributes including marital status, education, age, and payment history, etc.
The classes were imbalanced.To make my dataset balanced,I used downsampling method.

You can see the imbalance of the dataset with this plot :

![ana1](https://user-images.githubusercontent.com/33470542/81461380-47ce6380-9179-11ea-994e-3c7ecca1fc7a.png)




# Modeling

1) Model Building (Imbalanced Dataset)

   Convolutional Neural Network (CNNs)
   
   ![ana15](https://user-images.githubusercontent.com/33470542/81508979-71040680-92d5-11ea-8af9-6d7cae255eec.png)

     
   
   Adding MaxPooling
   
   ![ana 16](https://user-images.githubusercontent.com/33470542/81508993-88db8a80-92d5-11ea-8096-37e2b321c714.png)


2) Model Building (Downsampling the majority class)


   ![ana17](https://user-images.githubusercontent.com/33470542/81513595-8558fb00-92f7-11ea-9d90-d7653e8df262.png)


# Result

The f1 score of Convolutional Neural Network after balancing the dataset using downsampling method is less than when we are using Convolutional Neural Network with Maxpooling.

The result of CNN after Maxpooling :

![ana18](https://user-images.githubusercontent.com/33470542/81513020-42952400-92f3-11ea-96f6-8231cb5dea8c.png)


The result of CNN after downsampling : 

![ana19](https://user-images.githubusercontent.com/33470542/81513609-9570da80-92f7-11ea-97c1-7ebb4cfcbb51.png)



