**ABSTRACT**

Natural Gas (NG) plays a crucial role in global energy supply chains and is known for its price
volatility, making it a significant commodity for price prediction. This research paper presents
a detailed analysis of applying Machine Learning (ML) algorithms to forecast natural gas prices
using weekly price data, including Date, Price, Open, High, Low, Volume, and Percentage
Change. The dataset spans from February 20, 2019, to December 31, 2024, providing a
comprehensive foundation for analysing price dynamics, volatility, and trading patterns.
The primary objective of this study is to examine historical NG price trends, develop and
evaluate machine learning models for accurate forecasting, investigate the relationship between
trading volume and price movements, and offer actionable insights for traders, investors, and
policymakers in the energy sector. The research includes data preprocessing, exploratory data
analysis (EDA), feature engineering, and the implementation of various ML models such as
Linear Regression, Random Forest, Gradient Boosting Machines (GBM), and Long Short-
Term Memory (LSTM) networks.
Model performance is assessed using metrics like Mean Absolute Error (MAE), Root Mean
Squared Error (RMSE), and R-squared. The results indicate that LSTM outperforms other
models in capturing long-term dependencies and sequential patterns in the data. Additionally,
the study explores the impact of trading volume on price fluctuations, highlighting its
significance as a predictive feature, particularly in highly volatile market conditions.
Furthermore, market regime detection using clustering techniques like K-Means and Gaussian
Mixture Models (GMM) presents opportunities for adaptive trading strategies that perform
effectively across varying market conditions. The research also discusses the potential
integration of reinforcement learning for dynamic portfolio optimization. Overall, this work
contributes to the broader field of energy market forecasting by advancing machine learning
applications in natural gas price prediction and setting the stage for future research and practical
implementations in the energy sector.

**INTRODUCTION**

Natural gas (NG) is a fundamental energy source for power generation, industrial applications,
and household heating, making it one of the most crucial commodities in the global energy
landscape. Due to its lower carbon footprint compared to coal and petroleum, natural gas is
often considered a transitional fuel toward renewable energy adoption, contributing to its
increasing global consumption. However, natural gas prices are highly volatile, influenced by
a wide range of factors such as geopolitical events, supply-demand dynamics, weather patterns,
storage levels, and macroeconomic trends. This price unpredictability poses a significant
challenge for market participants, including energy companies, traders, financial institutions,
and policymakers, all of whom rely on accurate forecasts to make informed decisions.
Traditional econometric models and expert-driven analysis often struggle to fully capture the
complexities and non-linearity of natural gas price movements. In recent years, Machine
Learning (ML) has emerged as a powerful tool for analysing large datasets and generating more
precise predictions, offering a viable alternative to conventional forecasting techniques.
Machine Learning’s ability to process vast amounts of data, identify hidden patterns, and adapt
to evolving market conditions has made it increasingly valuable in financial and commodity
markets. By leveraging historical price data, trading volumes, and other relevant factors, ML
models can improve the accuracy of natural gas price forecasts. Since natural gas price
movements follow a time-series structure with temporal dependencies, models such as Random
Forest, Gradient Boosting Machines (GBM), and Long Short-Term Memory (LSTM) networks
have proven particularly effective. These models can capture both short-term fluctuations and
long-term trends, making them well-suited for predicting the highly dynamic and uncertain
nature of natural gas markets.
This research paper focuses on developing and evaluating advanced Machine Learning models
for natural gas price forecasting using a comprehensive dataset spanning from February 20,
2019, to December 31, 2024. The dataset includes daily price values, trading volumes, and
percentage changes, providing a robust foundation for analysis. The study begins with
Exploratory Data Analysis (EDA) to uncover key trends and patterns, followed by feature
engineering to create additional predictive variables such as technical indicators, moving
averages, and lagged prices. These features are then fed into various ML models, including
Random Forest, GBM, LSTM networks, and Linear Regression, which are assessed for their
predictive accuracy and stability.
The significance of this research lies in its practical applications. Accurate price predictions
can help energy producers optimize production schedules, enable traders to refine their
strategies, and assist policymakers in managing market stability during periods of extreme
volatility. Additionally, incorporating trading volume data enhances the understanding of its
influence on price movements, an aspect often overlooked in traditional forecasting
approaches. By harnessing the power of Machine Learning, this study contributes to the
growing field of energy market forecasting and provides a foundation for future research. The
methodologies and insights presented in this paper are not only relevant to natural gas markets
but can also be extended to other commodities and financial assets.
The primary objective of this study is to enhance natural gas price forecasting by integrating
data-driven ML techniques with traditional methodologies. Through comprehensive analysis
and advanced modelling, the research aims to improve predictive accuracy and efficiency,
ultimately facilitating more informed decision-making in the energy sector. The following
sections of this paper delve into the methodology, model development, findings, and
implications of Machine Learning in natural gas price prediction.
