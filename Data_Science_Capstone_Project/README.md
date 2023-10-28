# Data Science Captsone Project - Spacex Falcon 9 Prediction model

## Overview

SpaceX has revolutionized the economics of space exploration with its Falcon 9 rocket launches, pricing at a competitive $62 million—dramatically undercutting competitors who charge up to $165 million. This cost efficiency stems from SpaceX's innovative approach of reusing the rocket's first stage. Therefore, predicting the successful landing of this first stage becomes pivotal in estimating launch costs. In this venture, our project harnesses cutting-edge data science techniques to delve into this business challenge, leveraging advanced analytical tools to unearth invaluable insights from our data

## Project background and context

SpaceX advertises Falcon 9 rocket launches on its website with a cost of 62 million dollars; other providers cost upward of 165 million dollars each, much of the savings is because SpaceX can reuse the first stage

## Problems you want to find answers

The aim is to predict if the Falcon 9 first stage will land successfully

## Methodology

• Data collection methodology:
• SpaceX Rest API
• Web Scrapping from Wikipedia
• Perform data wrangling
• One hot Encoding data fields for Machine Learning and Data Cleaning of null values and 
irrelevant columns.
• Perform exploratory data analysis (EDA) using visualization and SQL
• Perform interactive visual analytics using Folium and Plotly Dash
• Perform predictive analysis using classification models
• LR, SVM, DT, KNN models were built and evaluated for best classifier using GridSearchCV

## Results

• Orbit GEO, HEO, SSO, ES L1 has the best success rate.
• KSC LC 39A had the most successful launches of all sites.
• Low weighted payloeads perform better than heavier payloads.
• Decisiom Tree is the optimal model with accuracy of 0.89

## Conclusion

In this project, we aimed to predict the successful landing of this first stage and to do this we have performed various steps which includes acquiring the data using various methods such as api and web scraping. After having the data, we further performed data wrangling to refine the data and also explored the data using visualisation tools and sql.

Finally we performed various classification machine learning models, including decision trees and Support Vector Machine and noted that decision tree has the best accuracy. With further fine tuning of the hyperparameters, I personally feel that  a better accuracy can be obtained from the model.

Lastly, this project has allowed me to understand fully the end to end process of a machine learning project and I hope I am able to have more opportunity to do more projects in the future.
