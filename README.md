# MS4110-Introduction to Data Analytics-Assignment
e_commerce,ipynb contains the code that was run

E-COMMERCE DELIVERY
Context
Consider an online delivery store, that delivers customized apparels to customers. Given various details such as the order details, factory details, expected_delivery_date, predict whether the product would be delivered on time  or not.
Content
 Think of the supply chain as made up of 4 parts :- 
1. Plan – provide consumer with an expected delivery date.
2. Supply – Drop the product to a work station, where it could be customised
3. Customise – Create the customised product
4. Deliver – Pick the order from work station and deliver it to the customer.
All of supply, customise and deliver have a deadline, but plan does not. It is possible that the order meets all the 3 deadlines, but still fails due to a bad plan.

Most of the fields are self-explanatory except for the following:-
    • facility:-  location where the customization occurs and shipment originates
    • shipping_method and transit_days: the shipping method the customer requested. Next Day, 2-Day, and 3-Day take 1, 2, and 3 business days respectively; Ground is dependent on the customer location, and takes the amount of business days in transit_days to reach the customer
For testing, you should provide a function, which takes in the path of a test csv file(it would be in the same format as the train file) and prints out the accuracy/relevant metrics.
For imputing missing data, one method is to assume a joint or a conditional distribution for the missing variables given the other varaibles in the model. Fit this distribution to the known values and use it to predict the missing values. Do not use any other method for imputing missing values. 
