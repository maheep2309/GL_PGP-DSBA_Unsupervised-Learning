# GL_PGP-DSBA_Unsupervised-Learning
This project segments AllLife Bank’s credit card customers using K-Means and Hierarchical Clustering. It analyzes spending patterns, credit limits, and service-interaction behavior to create actionable customer profiles that support personalized marketing, service improvement, and better digital-banking strategies.

# Project Summary
This project helps AllLife Bank understand its credit-card customers by building unsupervised learning models that segment users based on their financial behavior and interactions with the bank. The dataset includes credit limits, number of cards, bank visits, online logins, and call-center usage. After ensuring no missing values, redundant keys are removed and the data is standardized for clustering.

Exploratory analysis reveals strong behavioral patterns—for example, higher credit-limit customers rely heavily on online banking and rarely contact support, while low-credit customers call frequently and have minimal branch activity.

Two clustering models are then developed: K-Means (K=3) and Agglomerative Hierarchical Clustering (K=3). Both models produce nearly identical customer groups, confirming the robustness of segmentation. Segment profiling highlights three clear customer types:
  1. Mid-Tier Traditional Customers – moderate credit limits, multiple cards, rely mainly on branch visits, low online usage.
  2. Low-Credit Support Seekers – low credit limits, few cards, moderate online activity but very high call-center usage.
  3. High-Value Digital-First Customers – very high credit limits, many cards, heavy digital usage, minimal branch visits or calls.

Actionable strategies are provided for each segment—enhancing branch services, improving call-center efficiency, promoting digital adoption, offering premium digital experiences, and designing personalized marketing campaigns. These insights equip AllLife Bank to improve customer satisfaction, optimize service delivery, and strengthen product targeting using data-driven segmentation.
