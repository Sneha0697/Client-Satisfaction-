# Client-Satisfaction-
Keep track of the numerous aspects that influence client satisfaction across the United States.

The tableau workbook is comprised of interactive dashboards that can be used to analyze various aspects across multiple states for any specific gender, complaint, or product.The following three analyses can be used to examine and support the factors that influence the dependent variables.
### Resolve Days Analysis
<img src="Images/Resolve Days.png?raw=true"
     width="600" 
     height="400"/> 


   This dashboard provides the user to compare the average number of days it takes to address a customer complaint across different states, complaint kinds, and product categories. We can also observe that customer satisfaction is inversely related to resolve days, implying that fewer resolve days result in better client contentment.

### Customer Satisfaction Analysis
<img src="Images/Client Satisfaction.png?raw=true"
     width="600" 
     height="400"/> 
     
   We obtain the number of satisfied and unsatisfied consumers for each complaint type, category, and source. We may enhance our analysis by obtaining a particular customer satisfaction count for the desired gender in the desired state for the intended product. We gain a better knowledge of which goods are underperforming and causing customer unhappiness, as well as how probable it is that a gender category may affect customer satisfaction for a certain type or category of complaint.
   
### Predictive Model Analysis
<img src="Images/Predictive Analysis.png?raw=true"
     width="600" 
     height="400"/> 
     
  The logistic regression for the normalized and unnormalized features supports all the dependent variables used to analyze customer satisfaction and resolve days behavior in the above dashboards.Confusion Matrix was computed separately for train and test data to assess its prediction accuracy and capacity to fit any set of data that measures the same variables.
  According to the ROC curve, if we want to include only true positives in our model, we set the threshold to 5.88 %, and if we want to boost our true positive rate, we should capture all true positives by allowing the model to include false positives too and set our threshold to around 8%.
By and large, our goal is to improve the firm's ability to optimize client satisfaction under various conditions and forecast a certain behavior pattern based on various parameters.
