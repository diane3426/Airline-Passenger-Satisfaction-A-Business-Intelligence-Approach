# Airline Passenger Satisfaction Analysis

## Introduction
This project aims to enhance airline passenger satisfaction by leveraging Business Intelligence and Data Mining techniques. The competitive nature of the airline industry makes passenger satisfaction a critical factor for profitability and customer loyalty. By employing advanced data analytics and machine learning techniques, the objective is to transform raw data into actionable insights. These insights are intended to guide airlines in refining their services, tailoring offerings to meet diverse customer needs, and ultimately, building stronger, loyalty-driven relationships with passengers. The project underscores the role of data-driven decision-making in elevating the passenger experience and fostering a culture of continuous improvement within the airline industry.

## Objectives
- To predict passenger satisfaction based on various service features.
- To identify key determinants that impact passenger satisfaction in airline services.
- To segment passengers into distinct groups for targeted service improvements.

## Dataset
The dataset, sourced from a Kaggle repository, includes passenger demographics, flight attributes, and satisfaction ratings. It covers aspects like in-flight services, seat comfort, cleanliness, and booking ease, among others.

## Model Used
We evaluated three predictive models:
- Logistic Regression: To estimate the probability of satisfaction based on service features.
- Random Forest: To capture complex interactions between features and satisfaction.
- Lasso Regression: For feature selection and to reduce model complexity.
Additionally, the K-Prototypes algorithm was used for clustering passengers based on categorical and numerical attributes, aiding in the identification of distinct passenger segments.

## Conclusion
To conclude, The Logistic regression showed a 93.4% accuracy, highlighting the importance of travel type, class, and service ratings. Random forest improved accuracy to 96.4% with computational constraints. Lasso, focusing on mean squared error, explained 55.06% variability with customer type, travel type, class, and online boarding as key features. Clustering identified four customer groups based on travel purpose, class preference, age, and travel distance, with varied satisfaction levels and service ratings. By leveraging business intelligence and data mining techniques, the study highlights the critical role of personalized services, operational efficiency, and customer feedback in enhancing the travel experience. The findings suggest that airlines should focus on continuous improvement and adaptability to meet the evolving needs and expectations of passengers, ensuring a positive and memorable journey for all travelers.

