# Time-Series-Forecasting---AN2DL-Project
A project focused on developing a forecasting model capable of predicting multiple uncorrelated time series while exhibiting strong generalization capabilities across different time domains. The primary challenge was to create a model that could transcend domain-specific constraints, a crucial aspect for real-world applicability.
It's the second of two projects of the course *Artificial Neural Networks and Deep Learning*, Politecnico di Milano, 2023/2024.


**Project Overview**


Traditional time series forecasting models often struggle when applied to new, unseen domains or datasets with varying characteristics. This project delves into strategies for building a robust forecasting system designed to perform effectively across a collection of distinct, uncorrelated time series. We explored various data manipulation techniques and model architectures to address inherent complexities like domain imbalance and the need for cross-domain generalization.

While we experimented with several advanced approaches, this repository documents our investigation into a particularly challenging aspect of time series forecasting: how to leverage or mitigate the impact of data originating from distinct domains.

**Data Analysis & Challenges**


Our initial data analysis revealed a dataset composed of time series distributed across six distinct domains. A significant challenge was the strong imbalance among these domains, with some (like the fifth and first) being considerably underrepresented. The first domain, despite its lower representation, also had the highest mean time series length.

Rather than focusing on classification-style balancing, we shifted our attention to how the domain partitioning itself could be used strategically to improve forecasting.
