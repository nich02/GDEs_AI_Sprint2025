## Machine Learning-Based Scoring Model Ranks Climate Variables Better in Credit Default Risk Prediction 

<img src="images/german_bank.jpg" width="800" height="450">

### 1. Project Highlight 
- The intersection of environmental factors and financial stability has sparked a growing debate, particularly concerning the influence of ESG (Environmental, Social, and Governance) climate variables on customer credit default probability. \
- This project rigorously assessed the validity of the claim that specific climate-related risks, such as flood, drought, and landslide probabilities, significantly impact an individual's likelihood of defaulting on credit.
### 2. Step One
- To investigate this hypothesis, a robust machine learning approach was employed, leveraging a Random Forest model due to its efficacy in handling complex datasets and identifying feature importance. The project commenced with an initial credit scoring model developed using a traditional dataset devoid of environmental indicators.
- In this preliminary phase, the model demonstrated strong predictive performance, identifying conventional financial metrics like 'Loan amount' and 'Outstanding balance' as the most influential features in forecasting customer default.

### 2. Step Two
- Subsequently, the dataset was augmented to incorporate granular climate variables, specifically flood, drought, and landslide probabilities. This data can be worked on from <a href="https://developers.google.com/earth-engine/datasets" target="_blank" rel="noopener noreferrer">Google Earth Engine data Catalog</a>. We can explore on how to achieve that in separate project. Climate Engine developed a <a href="https://climateengine.com/introducing-spatiafi/" target="_blank" rel="noopener noreferrer">SpatiaFi</a>- a cloud-based Spatial Finance analytics platform, which provides access to petabytes of climate and environmental data, enabling users to extract insights and perform analyses without needing to manage complex infrastructure. These critical environmental data points were meticulously acquired and integrated from the Google Earth Engine platform, providing a spatially informed dimension to the credit risk assessment.
- A spatial data scientist played a pivotal role in this integration, ensuring the accurate mapping and alignment of climate risks with customer locations. 

### 3. Step Tree
Upon retraining the Random Forest model with this enriched dataset, a remarkable shift in feature importance was observed. The newly introduced climate variables—flood, drought, and landslide probabilities—emerged as the top-ranked predictors, surpassing the traditional financial indicators previously deemed most significant. 
This compelling finding strongly supports the assertion that climate variables are not merely contributing factors but indeed critical, highly influential elements in predicting customer probability of default. 
The study concludes that incorporating such environmental data is essential for developing more comprehensive, resilient, and accurate machine learning-driven credit scoring models, offering a crucial advancement in risk management within a climate-changing world.

#### This Project demonstrate the Impact of Overlooked Influence of Climate Variables on Customer Credit Default a less explored concept in the finance industry.

<img src="images/n.png">

4. Credit amount and Duration are strongly positively correlated. Credit services with longer durations generally are associated with higher credit amounts and vice-versa.

<img src="images/x.png">

5. Customers with little saving and checking accounts tend to present higher credit risk. Particularly, almost 50% of the customers who have little checking accounts are bad risk ones. Moreover, when a customer takes credit from the bank for vacation/others and education purposes, it must be alert. Specifically, almost 50% of the customers who took credit for education are bad risk.

<img src="images/n.png">
<img src="images/n.png">

### Project Dev is Earth Engine GDE 
Linkedin: <a href="https://www.linkedin.com/in/nicholas-musau/" target="_blank" rel="noopener noreferrer">Nicholas Musau - Earth Engine GDE</a> 

Join Our Community: <a href="https://gdg.community.dev/gdg-for-earth-engine-nairobi/" target="_blank" rel="noopener noreferrer">Google Earth Engine Developer Community Nairobi</a>   
Follow us 

LinkeId: 

Twitter: 

