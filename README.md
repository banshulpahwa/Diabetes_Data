# Diabetes_Data
Diabetes is a prevalent disease that affects numerous bodily systems, often leading to a restrictive and challenging lifestyle. The motivation behind this project was to tackle diabetes, both as a personal interest and as an opportunity to practice SQL with a substantial dataset that Excel couldn't handle.

Cleaning and Insights in SQL

Recalling my SQL skills initially took some adjustment, as I had set aside data analysis for a while. However, after a few queries, I regained my footing and started extracting the insights I was looking for. An intriguing discovery prompted further investigation – the occurrence of diabetes in two-year-olds.

Using BigQuery, I conducted data cleaning and validation. I checked for NULL values (there were none) and then explored the possibility of duplicate entries, which was unlikely given the range of variables like BMI, age, smoking history, and glucose levels. To streamline the dataset, I used `SELECT DISTINCT`.

The Dashboard

Analyzing the dataset, I observed that the number of diabetics tends to cluster and increase significantly around the age of 60, with another sharp rise at age 80. There was also a notable surge in diabetics with a BMI around 27, signifying a correlation between high BMI and diabetes.

Exploring A1c levels (a metric for blood glucose over time) and blood glucose levels revealed intriguing patterns. As A1c levels increased, the number of diabetics declined, eventually stabilizing around 6 percent. Conversely, blood glucose levels increased in tandem, but with clustering around 150.

It's important to note that the data did not distinguish between Type 1 and Type 2 Diabetes. Individuals with Type 1 diabetes often contend with low blood sugar.

One significant finding was that the average blood sugar level for diabetics was 194 mg/dL, while for non-diabetics, it stood at 133 mg/dL.

Out of nearly 100,000 collected samples (after cleaning), approximately 8.83 percent of individuals had diabetes.

This project provided valuable insights into the prevalence and factors associated with diabetes, serving as a reminder of the importance of data analysis in addressing health challenges.
