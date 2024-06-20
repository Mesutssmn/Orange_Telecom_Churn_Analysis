# Orange Telecom's Churn Analysis

<div style="border-radius: 10px; overflow: hidden; text-align: center;">
    <img src="https://miro.medium.com/v2/resize:fit:1400/1*47xx1oXuebvYwZeB0OutuA.png" alt="Churn" width="900"></div>




**ABOUT DATA**

The Orange Telecom's Churn Dataset, which consists of cleaned customer activity data (features), along with a churn label specifying whether a customer canceled the subscription, will be used to develop predictive models. Two datasets are made available here: The churn-80 and churn-20 datasets can be downloaded.

The two sets are from the same batch, but have been split by an 80/20 ratio. As more data is often desirable for developing ML models, let's use the larger set (that is, churn-80) for training and cross-validation purposes, and the smaller set (that is, churn-20) for final testing and model performance evaluation.

**FEATURES**

1. **State**: 

   - **Type**: Categorical (string)
   - **Description**: Indicates the state in which the customer resides. This attribute can be useful for regional analysis of churn rates.
   
   
2. **Account length**:

   - **Type**: Integer
   - **Description**: The duration of the customer’s relationship with the telecom service provider, measured in months. It can be an indicator of customer loyalty and satisfaction.


3. **Area code**:

   - **Type**: Integer
   - **Description**: The area code associated with the customer’s phone number. This is often used to segment customers geographically.


4. **International plan**:

   - **Type**: Categorical (string)
   - **Description**: Indicates whether the customer has an international plan (e.g., "yes" or "no"). This feature could impact usage patterns and costs.


5. **Voice mail plan**:

   - **Type**: Categorical (string)
   - **Description**: Indicates whether the customer has a voicemail plan (e.g., "yes" or "no"). This feature may be related to customer engagement and service preferences.


6. **Number vmail messages**:

   - **Type**: Integer
   - **Description**: The number of voicemail messages left by the customer. This feature may reflect customer engagement and usage of voicemail services.


7. **Total day minutes**:

   - **Type**: Float
   - **Description**: The total number of minutes used during daytime calls. This is a key metric for understanding a customer’s calling behavior during peak times.


8. **Total day calls**:

   - **Type**: Integer
   - **Description**: The total number of daytime calls made by the customer. This feature helps in analyzing call frequency during the day.


9. **Total day charge**:

   - **Type**: Float
   - **Description**: The total charge for daytime calls. This is the cost incurred by the customer for daytime usage.


10. **Total eve minutes**:

    - **Type**: Float
    - **Description**: The total number of minutes used during evening calls. This feature is crucial for understanding usage patterns during non-peak hours.


11. **Total eve calls**:

    - **Type**: Integer
    - **Description**: The total number of evening calls made by the customer. It reflects the frequency of calls made in the evening.


12. **Total eve charge**:

    - **Type**: Float
    - **Description**: The total charge for evening calls. This shows the cost incurred by the customer for evening usage.


13. **Total night minutes**:

    - **Type**: Float
    - **Description**: The total number of minutes used during night calls. Night usage is often cheaper, so this feature is useful for cost analysis.


14. **Total night calls**:

    - **Type**: Integer
    - **Description**: The total number of night calls made by the customer. This can help analyze call patterns during night hours.


15. **Total night charge**:

    - **Type**: Float
    - **Description**: The total charge for night calls. This indicates the expense incurred by the customer for night-time usage.


16. **Total intl minutes**:

    - **Type**: Float
    - **Description**: The total number of minutes used for international calls. This is essential for analyzing international calling behavior.


17. **Total intl calls**:

    - **Type**: Integer
    - **Description**: The total number of international calls made by the customer. This feature helps in understanding the extent of international calling.


18. **Total intl charge**:

    - **Type**: Float
    - **Description**: The total charge for international calls. This shows the cost associated with international calling.


19. **Customer service calls**:

    - **Type**: Integer
    - **Description**: The number of calls made by the customer to customer service. A high number of service calls may indicate issues with the service or dissatisfaction.


20. **Churn**:

    - **Type**: Categorical (string)
    - **Description**: Indicates whether the customer has churned ("yes" or "no"). This is the target variable for the churn prediction model.

These features collectively provide a comprehensive view of customer behavior, usage patterns, and interactions with the telecom service provider, which are crucial for building predictive models to identify potential churners.
