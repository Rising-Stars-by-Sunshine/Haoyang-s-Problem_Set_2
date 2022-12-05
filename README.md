# Title [How to Choice a Good Title?](https://www.nature.com/articles/s41562-021-01152-2)
## Project information
- **Author**: Haoyang Yu, Applied Mathematics & Computational Sciences, class 2024, Duke Kunshan University
- **Instructor**: Prof. Luyao Zhang, Duke Kunshan University
- **Disclaimer**: Submissions to the Problem Set 2 for STATS201 Introduction to Machine Learning for Social Science, 2022 Autumn Term (Seven Week - Second) instructed by Prof. Luyao Zhang at Duke Kunshan University.
- **Acknowledgments**: Prof. Luyao Zhang, [Plotly](https://plotly.com/python/), [ARIMA](https://www.machinelearningplus.com/time-series/arima-model-time-series-forecasting-python/), [Yahoo Finance](https://finance.yahoo.com/)
- **Project Summary**: 

In Part I, we visualized the change of decentralization degree of [Lusd](https://www.liquity.org/) token along time. We plotted it by heat map, which is an intuitive way to visualize the tendency of the decentralization degree of a certain token. 

In part II, we predicted the stock price tendency of [Kraft Heinz Company(KHC)](https://www.kraftheinzcompany.com/) with [ARIMA](https://www.machinelearningplus.com/time-series/arima-model-time-series-forecasting-python/) machine learning approach. Since Warren Buffet lost a lot in the big stock collapse of Kraft Heinz ([Agnihotri, Arpita, and Saurabh Bhattacharya.](https://dx.doi.org/10.4135/9781529754216), 2021), and he prefers fundamental analysis rather than technical analysis ([financialstockdata.com](https://www.financialstockdata.com/warren_buffett_ta), 2022). It is worth trying machine learning prediction method to verify if technical analysis could have saved his loss.

## Table of Contents
| Tables        | Part I Explanatory           | Part II Prediction and Classification   |
| ------------- |:-------------:| -----:|
| code        | [Explanation Code](https://github.com/Rising-Stars-by-Sunshine/Haoyang_Problem_Set_2/blob/main/code/Explanation_Data.ipynb) | [Process Code](https://github.com/Rising-Stars-by-Sunshine/Haoyang_Problem_Set_2/blob/main/code/Process_Data_Prepare_X_and_Y_for_Classification_and_Regressions.ipynb), [Prediction Code](https://github.com/Rising-Stars-by-Sunshine/Haoyang_Problem_Set_2/blob/main/code/Analyze_Data_Machine_Learning_for_Predicting_KHC_stock_price.ipynb) |
| data        | [Part I Lusd Data](https://github.com/HaoyangMarcusYu/portfolio/blob/main/data/Processed_Data/Lusd_Processed.csv)      |   [Part II Raw & Train & Test data](https://github.com/Rising-Stars-by-Sunshine/Haoyang_Problem_Set_2/tree/main/data) |
| image      | [Part I Explaination image](https://github.com/Rising-Stars-by-Sunshine/Haoyang_Problem_Set_2/blob/main/spotlight/figures/Decentra_Index_Lusd.png)     |  [Part II KHC stock price prediction](https://github.com/Rising-Stars-by-Sunshine/Haoyang_Problem_Set_2/blob/main/spotlight/figures/KHC_Stock_Pred.png) |




## Data
- Data Source: [Yahoo Finance](https://finance.yahoo.com/quote/KHC/history?p=KHC), [SoK: Blockchain Decentralization](https://arxiv.org/abs/2205.04256)
- [Queried Data](https://github.com/Rising-Stars-by-Sunshine/Haoyang_Problem_Set_2/blob/main/data/Queried_Data/KHC.csv)
- [Processed Data](https://github.com/Rising-Stars-by-Sunshine/Haoyang_Problem_Set_2/tree/main/data/Processed_Data)


## Code
- Code Source: [Sample Code](https://github.com/Rising-Stars-by-Sunshine/stats201-tutorial-prediction)
- [Process Code](https://github.com/Rising-Stars-by-Sunshine/Haoyang_Problem_Set_2/blob/main/code/Process_Data_Prepare_X_and_Y_for_Classification_and_Regressions.ipynb)
- [Analyze Code](https://github.com/Rising-Stars-by-Sunshine/Haoyang_Problem_Set_2/blob/main/code/Analyze_Data_Machine_Learning_for_Predicting_KHC_stock_price.ipynb)
- [Explanation Part Code](https://github.com/Rising-Stars-by-Sunshine/Haoyang_Problem_Set_2/blob/main/code/Explanation_Data.ipynb)

## Spotlight

### Part I Explanatory
![image](https://github.com/Rising-Stars-by-Sunshine/Haoyang_Problem_Set_2/blob/main/spotlight/figures/Decentra_Index_Lusd.png)

**Figure 1: Decentralization Index of the Lusd Token shown in heat map**

Source: Created by [Plotly](https://plotly.com/python/2D-Histogram/) using data from [SoK: Blockchain Decentralization](https://arxiv.org/abs/2205.04256)

Figure 1 shows the Decentralization Index of Lusd token from Apr. 2020 to Oct. 2022. The X-axis represents the date and Y-axis represents the decentralization value. The bright boxes indicate a increasing number of decentralization index during the corresponding period. The brighter the box, the faster the decentralization index increases. In this figure, we can observe that the bright part is moving toward to low-index direction along the time, so the decentralization index is smaller. Thus, we conclude that Lusd token is becoming more and more centralized during from Apr. 2020 to Oct. 2022.

### Part II Prediction
![image](https://github.com/Rising-Stars-by-Sunshine/Haoyang_Problem_Set_2/blob/main/spotlight/figures/KHC_Stock_Pred.png)

**Figure 2: Comparison of prediction and real data of KHC stock price**

Source: Created by [Plotly](https://plotly.com/python/2D-Histogram/) and [ARIMA](https://www.machinelearningplus.com/time-series/arima-model-time-series-forecasting-python/) using data from [Yahoo Finance](https://finance.yahoo.com/)

Figure 2 shows the daily close price of KHC from May.6 2015 to Dec.2 2022. The X-axis represents the date and Y-axis represents the daily close price of KHC. The blue line is the prediction line generated by [ARIMA](https://www.machinelearningplus.com/time-series/arima-model-time-series-forecasting-python/). The line indicates that, from Jan.9 2022 to Dec.11 2022, the the close stock price of KHC will present an increase tendency. 


## References

Agnihotri, Arpita, and Saurabh Bhattacharya. "Growth Strategic Options of Kraft Heinz." SAGE Business Cases. SAGE Publications: SAGE Business Cases Originals, 2021. https://dx.doi.org/10.4135/9781529754216

Financialstockdata.com. "Warren Buffett on Technical analysis and Trading". 2022. https://www.financialstockdata.com/warren_buffett_ta

Instructions for GitHub Readme:
https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax

Levin, Dan, and Luyao Zhang. 2020. “Bridging Level-K to Nash Equilibrium.” *The Review of Economics and Statistics* 104 (6): 1329–40. https://doi.org/10.1162/rest_a_00990.

Sample Code for Prediction:
https://github.com/Rising-Stars-by-Sunshine/stats201-tutorial-prediction

Yahoo Finance. (2022). The Kraft Heinz Company (KHC) Historical Data. Queried from https://finance.yahoo.com/quote/KHC/history?p=KHC

Zhang, L. (Sunshine). (2022). Machine Learning for Predictions. Machine Learning for Social
Science. Retrieved from https://ms.pubpub.org/pub/ml-prediction

Zhang, L. (Sunshine). (2022). Venues for Computer Security and Beyond. Machine Learning for
Social Science. Retrieved from https://ms.pubpub.org/pub/security

Zhang, L. (Sunshine). (2022). Venues for Machine Learning&nbsp; Machine Learning for
Social Science. Retrieved from https://ms.pubpub.org/pub/ml

Zhang, L. (Sunshine). (2022). Computing Platforms: Set up the Workspace for Machine
Learning Projects. Machine Learning for Social Science. Retrieved from
https://ms.pubpub.org/pub/computing

Zhang, L. (Sunshine). (2022). Resources for Blockchain Network Studies. Machine Learning for
Social Science. Retrieved from https://ms.pubpub.org/pub/network
