# Neural_Network_Charity_Analysis

## Overview of the Project

In this Analysis we looked at Alphabet Soup, a Charitable organisation that helps needy with small loans and helped trhem determine the people that will be able to pay back the loans

## Analysis

In the Analysis, we were able to upload the data of the companies that were applying for the grants and we removed the name and Ein columns as this would bias our data

We then processed the data and turned it in neuro network friendly data by replacing the counts with more than 500 and replaced them with other in the Application and Classification columns

We encoded the data, split, standadized and trained the data to be able to determine if a client will be able to pay back the sums borroqwed or will vanish in thin air.

We then compiled and trained and evaluated the data with 

Model: "sequential_1"
_________________________________________________________________
Layer (type)                 Output Shape              Param #   
=================================================================
dense_3 (Dense)              (None, 80)                3600      
_________________________________________________________________
dense_4 (Dense)              (None, 30)                2430      
_________________________________________________________________
dense_5 (Dense)              (None, 1)                 31        
=================================================================
Total params: 6,061
Trainable params: 6,061
Non-trainable params: 0

and used 100 epochs to train the module

we then evaluated the model 

268/268 - 0s - loss: 0.6922 - accuracy: 0.7022
Loss: 0.6921913027763367, Accuracy: 0.7021574378013611

and determined that with an accuracy of 70%, this module would not be the best to fully evaluate this data, since to get the best results we would need at have an accuracy of over 95%

## Conclusion

This Module would help Alphabet Soup to predict the results that are required but is not good enough, we would need to increase the nodes and neurons to be able to achieve better results although this could easily lead to over fitting and not give as a correct picture of what is required

hence Alphabet soup can use this data but also throw in some caution as they advance the loans to the people that need them

