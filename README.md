
# Anomaly Detection in User Login Data

**Overview**

This project is a Python-based implementation of anomaly detection using machine learning. It focuses on identifying unusual login behaviors in user login data, such as logins at uncommon times, which could indicate fraudulent activities or other irregularities.

I have used Isolation Forest algorithm for unsupervised anomaly detection and Principal Component Analysis (PCA) for dimensionality reduction and visualization. This project includes data preprocessing, anomaly prediction, and insightful visualizations to interpret the results.


**Project Features**

Data Simulation:
Randomly generates a dataset with user login information.
Features include login_time (numerical) and location (categorical).

Data Preprocessing:
Categorical encoding with LabelEncoder.
Imputation of missing values using KNNImputer (if applicable).

Anomaly Detection:
Anomaly detection is performed using the Isolation Forest algorithm.
Identifies outliers based on login patterns (time and location).

Dimensionality Reduction:
Principal Component Analysis (PCA) is applied to visualize data in a lower-dimensional space.
Helps interpret anomalies in a simplified feature space.

Visualization:
Scatter plots to visualize login behavior and highlight anomalies.
Visualizations provided for both the original feature space and PCA-reduced space.

IP Tracking:
Retrieves and logs the current IP address for identified anomalies.
Appends anomaly details and associated IP addresses to a file for auditing purposes.





## Tech Stack

The following tools and technologies are used in this project:

**Core Technologies:**

- Programming Language: Python
- Libraries/Tools:
  - scikit-learn (Machine Learning)
  - pandas (Data Manipulation)
  - matplotlib (Data Visualization)
  - numpy (Numerical Computation)
  - requests (API for IP Address Retrieval)








## Visualizations


<img width="665" alt="image" src="https://github.com/user-attachments/assets/f06855f3-ce79-4010-9645-5313dd5e5fc1">

This plot shows login behavior based on login_time (x-axis) and location (y-axis, encoded as integers).

*How to Interpret:*

- Normal Points: Represent common login behaviors.

- Anomalies (Red x): Highlight unusual logins, such as logins at odd times or from rare locations.

<img width="668" alt="image" src="https://github.com/user-attachments/assets/972134cb-7423-44cb-9c35-cddc13d0cf2f">

PCA Scatter Plot
Description:

This plot visualizes the data in a reduced-dimensional space using PCA, with PC1 and PC2 on the axes.

*How to Interpret:*

- Clusters: Represent dense groups of normal behavior.

- Anomalies (Red x): Highlight distinct login events that deviate from the main clusters.
## 🚀 About Me
Hello! 👋 My name is Krish Shah, and I am a passionate Data Analyst and aspiring Data Engineer with a strong foundation in data-driven problem-solving and technical innovation. With a keen interest in leveraging technology to extract meaningful insights from complex datasets, I specialize in creating robust, scalable solutions for data analysis and visualization.

