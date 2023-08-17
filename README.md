# Segmentation-Airline-Customer
This dataset contains customer data for an airline and several features that can describe the value of that customer

## 🌱 Problems
✔️ Airlines want to increase revenue through marketing strategies. Therefore the Company requires the behavioral preferences of each customer

## 🌱 Objective
✔️ Create a clustering model, to segment customers based on:
1. Recency or distance between the first flight and the last flight
2. Average customer flights every month
3. Customer expenses

## 🌱 Modelling
### **1. Elbow Method**

<br> ![alt text](https://github.com/JodhiKrisantus/Segmentation-Airline-Customer/blob/master/Asset%20img/Elbow%20Method.png "Optimal Clusters")<br>
Using the Elbow Method to find the optimal number of clusters by looking at the most drastic changes in inertia. Through the visualization above, it can be concluded that the optimal number of clusters is 3.


### **2. Cluster Results Visualization**

<br> ![alt text](https://github.com/JodhiKrisantus/Segmentation-Airline-Customer/blob/master/Asset%20img/Kmeans%20Clustering.png "Cluster Results")<br>

### **3. Clusters Interpretation**
<br> ![alt text](https://github.com/JodhiKrisantus/Segmentation-Airline-Customer/blob/master/Asset%20img/Clusters%20Interpretation.png "Cluster Interpretation")<br>

- Cluster 0 = High-Value Passengers (Important). Cluster 0 memiliki nilai recency, frequency, dan monetary yang tinggi. Hal ini menunjukkan bahwa penumpang dalam cluster ini adalah penumpang aktif dengan kontribusi pendapatan yang signifikan bagi maskapai.
- Cluster 1 = Mid-Value Passengers (Potensial). Cluster ini menunjukkan penumpang dengan tingkat aktivitas dan kontribusi pendapatan rendah.
- Cluster 2 = Low-Value Passengers (Low - Potensial). Cluster ini menunjukkan penumpang yang jarang terbang dengan kontribusi pendapatan yang lebih sedang.


## 🌱 Business Recommendations
### Clusters 0
Offers an exclusive loyalty program to passengers in this cluster by providing additional benefits, such as priority boarding.
Provide discount offers or special promotions to passengers in this cluster, by sending them promo codes via email or mobile application. This is to encourage them to take more flights or book tickets earlier.

### Cluster 1
Invite passengers in this cluster to join a loyalty program that provides incentives, such as reward points or special discounts for each subsequent flight. This is expected to encourage them to fly more frequently and get extra benefits.
Offer travel packages that combine airfare with additional accommodation or services, such as hotels at special rates. This is to encourage them to fly more frequently and get extra benefits.

### Cluster 2
Offering attractive promotions, such as special discounts or special offers, giving promos in the form of attractive cash back or vouchers, so they can make transactions again. This is because the cost of retaining a customer can be 5-25 times cheaper than finding a new customer.
Provides more flexibility in payment, for example at a lower rate or with a refund.


