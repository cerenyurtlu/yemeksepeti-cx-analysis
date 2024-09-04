# Customer Experience (CX) Metrics Analysis for Yemeksepeti

# Project Overview
This repository contains a detailed analysis of customer experience (CX) metrics from a food delivery platform. The dataset, comprising 50,000 randomly selected restaurant orders from January to August 2024, provides insights into key CX metrics such as customer satisfaction, order distribution, and payment methods. The primary focus of this analysis is on the self-service channel, aiming to identify pain points and improve user satisfaction.

# Dataset
The dataset includes the following columns:
* order_id: Unique identifier for each order.
* order_time: Timestamp of the order.
* order_city: City where the order was placed.
* order_area: Specific area or district within the city.
* order_kitchen: Type of cuisine for the order.
* order_restaurant_id: Unique identifier for the restaurant.
* order_size_TRY: Total value of the order in Turkish Lira.
* preferred_payment_method: Payment method used for the order.
* isSeamless: Indicates if the order process was seamless.
* contact_reason_CSRLevel3: Reason for customer contact at a detailed level.
* contact_reason_MainGroup: Main category for the customer contact reason.
* isContact: Indicates if the issue was resolved through customer contact.
* isSelfService: Indicates if the issue was resolved through self-service.
* ContactCSAT: Customer satisfaction score for contact channel.
* SelfServiceCSAT: Customer satisfaction score for self-service channel.
* NPS-Q-Score: Net Promoter Score for the order.

# Key Findings

* Top 10 Most Popular Kitchen Types: The analysis reveals that burgers, pizza, and pide are the most popular kitchen types, accounting for over 60% of total orders.
* Order Distribution by District: Çekmeköy, Beşiktaş, and Şişli are the top districts by the number of orders, reflecting a high demand for food delivery services in these areas.
* Payment Methods: Online payment is the most preferred method, used in nearly 50% of the orders, followed by meal cards and credit/debit cards.
* Customer Satisfaction: The self-service channel has a higher average customer satisfaction score (0.56574) compared to the contact channel (0.1366), indicating a preference for resolving issues through self-service.
* Seamless Order Rate: 74.62% of orders were completed seamlessly, suggesting that the majority of the order processes are efficient and meet customer expectations.

# Project Structure

* CX_metrics_analysis.ipynb: The Jupyter notebook containing the Python code used for data analysis and visualization.
* data/: Directory containing the dataset used in this analysis.
* images/: Directory containing any visualizations generated during the analysis.
* README.md: This file.

# How to Use

1. Clone the repository:

git clone https://github.com/yourusername/CX-metrics-analysis.git

2. Install the required Python libraries:

pip install -r requirements.txt

3. Open the Jupyter notebook and run the analysis:

jupyter notebook CX_metrics_analysis.ipynb

# Recommendations
Based on the analysis, several recommendations are provided to enhance the customer experience, particularly through the self-service channel. These include optimizing popular kitchen offerings, improving seamless order processes, and enhancing the self-service experience to increase customer satisfaction.
