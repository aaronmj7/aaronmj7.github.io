---
layout: default
title: Aaron Modiyil Joseph
description: Quantitative Data Science Graduate | IFoA Student Member | Aspiring Actuarial & Risk Analyst
---

Welcome to my portfolio.

I am an MSc Data Science graduate (Distinction) with a strong foundation in mathematics, statistics, and predictive analytics. My interests lie in actuarial science, pensions, insurance analytics, pricing, and risk modelling. Through academic research and practical projects, I have developed experience applying statistical techniques to analyse complex datasets, identify patterns, and support data-driven decision-making.

### Technical Skills
**Programming:** Python, R, SQL

**Analytics & Visualisation:** Excel, Power BI, Tableau

**Statistical Techniques:** Statistical Modelling, Regression Analysis, Time Series Analysis, Predictive Analytics, Generalised Linear Models (GLMs), Risk Analysis, Data Validation, Financial Reconciliation, Trend Analysis, Reporting, Process Automation.

---

# Featured Projects
## Financial Market Forecasting and Risk Analysis
A collaborative deep learning project designing a sequential LSTM network to predict the closing stock prices of Greggs plc.

### Key Contributions
* Engineered a time-series pipeline to process and scale 17 years of historical stock data (2006–2023) to capture temporal market dependencies.
* Developed and fine-tuned a sequential LSTM model with dense layers and dropout regularization to prevent market overfitting.
* Achieved over 91% prediction accuracy within a 2% error margin, significantly outperforming standard RNN architectures.
* Evaluated model robustness using statistical error metrics (RMSE, MAE) to demonstrate viable decision-support for equity analysis.

**Skills:** Python · LSTM (Deep Learning) · Time-Series Analysis · Stock Market Analysis
<br>
🔗 **[View Source Code on GitHub](https://github.com/aaronmj7/Stock-Market-Analysis)**

<details style="background-color: rgba(0,0,0,0.03); padding: 15px; border-radius: 8px; margin-top: 15px; cursor: pointer;">
  <summary style="font-weight: bold; font-size: 1.1em; color: #1b365d;">
    📄 View Detailed Report & Methodology (Click to Expand)
  </summary>
  
  <div style="margin-top: 15px; cursor: default;">
    <p><b>Project Deep Dive:</b><br>
    Developed during my MSc at the University of Hertfordshire, this collaborative project explored the predictive power of Long Short-Term Memory (LSTM) networks in financial markets. We focused on Greggs plc, utilizing historical market data spanning from 2006 to 2023. The primary challenge was effectively capturing the complex temporal dependencies and volatility inherent in daily stock movements.</p>
    <p> We developed a deep learning architecture using sequential LSTM and dense layers. To ensure the model generalized well to unseen market conditions, we implemented strict data scaling and optimized the network with dropout regularization. The final model successfully achieved over 91% accuracy in predicting future price movements within a strict 2% error margin. By evaluating the model against standard Recurrent Neural Networks (RNNs) using statistical metrics like RMSE and MAE, we demonstrated the superior capability of LSTMs as a quantitative decision-support tool for equity forecasting. </p>
    <p><i>Scroll through the full project presentation below:</i></p>
    <iframe src="{{ site.baseurl }}/assets/Financial_Market_Forecasting.pdf" width="100%" height="600px" style="border: 1px solid #ccc; border-radius: 4px;">
      This browser does not support PDFs. 
    </iframe>
    <p style="text-align: right; font-size: 0.9em; margin-top: 10px;">
      Having trouble viewing? <a href="{{ site.baseurl }}/assets/Financial_Market_Forecasting.pdf" target="_blank">Open PDF in new tab</a>
    </p>
  </div>
</details>

<br>

## Comparative Study of ARIMA and LSTM Models on Time Series Data
A benchmark study evaluating traditional econometric methods against deep learning approaches across stable and highly volatile financial datasets.

### Key Contributions
* Processed and analyzed contrasting time-series datasets: highly seasonal quarterly sales (Johnson & Johnson) and volatile daily equity prices (Amazon).
* Developed classical ARIMA and deep learning LSTM architectures to isolate predictive capabilities across linear and non-linear market regimes.
* Evaluated forecasting performance using statistical error metrics, with the LSTM achieving superior accuracy (RMSE of 0.005 on Amazon stock).
* Demonstrated how structural volatility dictates model suitability, highlighting the trade-offs between model interpretability and predictive power.

**Skills:** Python · ARIMA · LSTM (Deep Learning) · Time-Series Forecasting · Statistical Error Metrics
<br>
🔗 **[View Source Code on GitHub](https://github.com/aaronmj7/Time-Series-Modelling-Case-Study)**

<details style="background-color: rgba(0,0,0,0.03); padding: 15px; border-radius: 8px; margin-top: 15px; cursor: pointer;">
  <summary style="font-weight: bold; font-size: 1.1em; color: #1b365d;">
    📄 View Detailed Report & Methodology (Click to Expand)
  </summary>
  
  <div style="margin-top: 15px; cursor: default;">
    <p><b>Project Deep Dive:</b><br>
    This project explored the fundamental trade-offs between traditional econometric forecasting (ARIMA) and advanced deep learning (LSTM). To rigorously test both architectures, I utilized two fundamentally different datasets: Johnson & Johnson's stable, highly seasonal quarterly sales (1960–1980) and Amazon's volatile, non-linear daily stock prices (2018–2023). The objective was to determine how distinct market characteristics impact model reliability.</p>    
    <p>The comparative analysis yielded clear structural insights. ARIMA proved highly effective and computationally efficient for capturing the predictable seasonality of the Johnson & Johnson dataset (RMSE: 0.4). However, it struggled to map the complex, erratic movements of the stock market. Conversely, the LSTM network excelled across both regimes, drastically reducing the error rate (RMSE of 0.196 for J&J, and an exceptional 0.005 for Amazon). Ultimately, this study underscores that while classical models offer excellent baseline interpretability for stable environments, capturing non-linear market risk requires the dynamic architecture of neural networks.</p>    
    <p><i>Scroll through the full project report below:</i></p>
    <iframe src="{{ site.baseurl }}/assets/ARIMA and LSTM.pdf" width="100%" height="600px" style="border: 1px solid #ccc; border-radius: 4px;">
      This browser does not support PDFs. 
    </iframe>
    <p style="text-align: right; font-size: 0.9em; margin-top: 10px;">
      Having trouble viewing? <a href="{{ site.baseurl }}/assets/ARIMA and LSTM.pdf" target="_blank">Open PDF in new tab</a>
    </p>
  </div>
</details>

<br>

## Comparative Study of Clustering Models
An unsupervised machine learning study comparing clustering architectures on a large-scale USA property dataset to isolate pricing segments and geographic trends.

### Key Contributions
* Engineered a preprocessing pipeline for a large property dataset, executing outlier removal, feature selection (price, size, geospatial coordinates), and scaling via MinMaxScaler.
* Build Gaussian Mixture Models (GMM) to successfully capture complex market segments, clearly distinguishing between high-value/large and low-cost/small apartment clusters based on data density.
* Deployed K-Means clustering as a comparative baseline, revealing strong geospatial groupings (East vs. West Coast) but demonstrating limitations in handling varied pricing distributions.
* Analyzed cluster behaviors to prove how algorithmic selection fundamentally alters real estate portfolio segmentation and market interpretation.

**Skills:** Python · Unsupervised Learning · Gaussian Mixture Models (GMM) · K-Means · Exploratory Data Analysis
<br>
🔗 **[View Source Code on GitHub](https://github.com/aaronmj7/Assignment_DMD)**

<details style="background-color: rgba(0,0,0,0.03); padding: 15px; border-radius: 8px; margin-top: 15px; cursor: pointer;">
  <summary style="font-weight: bold; font-size: 1.1em; color: #1b365d;">
    📄 View Detailed Report & Methodology (Click to Expand)
  </summary>
  
  <div style="margin-top: 15px; cursor: default;">
    <p><b>Project Deep Dive:</b><br>
    This project investigated the application of unsupervised machine learning to real estate markets, specifically analyzing a dataset of 10,000 rental apartments across the USA. The objective was to uncover hidden structural relationships between pricing, square footage, and geographic distribution. Before modeling, the data underwent rigorous preprocessing, including the removal of anomalies and scaling via MinMaxScaler to ensure distance-based algorithms performed optimally.</p>    
    <p>The study conducted a comparative analysis between Gaussian Mixture Models (GMM) and standard K-Means clustering. The results highlighted a stark contrast in algorithmic behavior. K-Means primarily partitioned the data along geographical fault lines (e.g., separating the Western and Eastern USA) but failed to capture nuances in property value. Conversely, GMM excelled at identifying underlying economic structures. Because GMM can model elliptical clusters and varying data densities, it successfully isolated distinct sub-markets, such as low-cost/compact units versus high-cost/expansive properties.</p>
    <p>Ultimately, this study demonstrated that for complex financial or property portfolio segmentation, probabilistic models like GMM provide significantly deeper business insights than standard distance-based clustering.</p>
    <p><i>Scroll through the full project report below:</i></p>
    <iframe src="{{ site.baseurl }}/assets/Comparative Study of Clustering Models.pdf" width="100%" height="600px" style="border: 1px solid #ccc; border-radius: 4px;">
      This browser does not support PDFs. 
    </iframe>
    <p style="text-align: right; font-size: 0.9em; margin-top: 10px;">
      Having trouble viewing? <a href="{{ site.baseurl }}/assets/Comparative Study of Clustering Models.pdf" target="_blank">Open PDF in new tab</a>
    </p>
  </div>
</details>

<br>

## Predicting Movie Ratings and Analyzing Feature Importance Using Tags and Genres
A Research project utilizing attention mechanisms and SHAP values to predict user movie ratings and isolate key content drivers.

### Key Contributions
* Engineered a large-scale data processing pipeline for the MovieLens 32M dataset, generating Word2Vec embeddings from unstructured user tags alongside categorical genres.
* Developed and trained a hybrid wide-deep neural network with attention mechanisms using TensorFlow/Keras (in Python) to capture complex feature interactions.
* Achieved an exceptional validation Mean Absolute Error (MAE) of 0.091, demonstrating highly accurate predictive capabilities for content recommendation systems.
* Executed SHAP (SHapley Additive exPlanations) analysis to interpret model outputs, transforming a "black box" architecture into transparent, quantifiable insights regarding user preferences.

**Skills:** Python · TensorFlow/Keras · Word2Vec · SHAP (Model Interpretability) · Recommender Systems
<br>
🔗 **[View Source Code on GitHub](https://github.com/aaronmj7/MSc_project)**

<details style="background-color: rgba(0,0,0,0.03); padding: 15px; border-radius: 8px; margin-top: 15px; cursor: pointer;">
  <summary style="font-weight: bold; font-size: 1.1em; color: #1b365d;">
    📄 View Detailed Report & Methodology (Click to Expand)
  </summary>
  
  <div style="margin-top: 15px; cursor: default;">
    <p><b>Project Deep Dive:</b><br>
    Developed during my MSc at the University of Hertfordshire, this project focused on the mechanics of modern content recommendation systems. Utilizing the massive MovieLens 32M dataset, the objective was to move beyond simple collaborative filtering and understand exactly <i>why</i> users rate movies the way they do, based specifically on categorical genres and unstructured user-generated text tags.</p>
    <p>To process this diverse data, I utilized Gensim to create Word2Vec embeddings for the text tags, seamlessly integrating them with the structured genre data. I then built a hybrid wide-deep neural network featuring attention mechanisms in TensorFlow/Keras. The model achieved an outstanding validation Mean Absolute Error (MAE) of just 0.091. Crucially, rather than leaving the deep learning model as an uninterpretable "black box," I applied SHAP to provide rigorous statistical transparency. This allowed me to isolate, quantify, and explain the exact features driving user engagement, bridging the gap between advanced predictive modeling and actionable business insights.</p>
    <p><i>Scroll through the full project report below:</i></p>
    <iframe src="{{ site.baseurl }}/assets/MSc_project.pdf" width="100%" height="600px" style="border: 1px solid #ccc; border-radius: 4px;">
      This browser does not support PDFs. 
    </iframe>
    <p style="text-align: right; font-size: 0.9em; margin-top: 10px;">
      Having trouble viewing? <a href="{{ site.baseurl }}/assets/MSc_project.pdf" target="_blank">Open PDF in new tab</a>
    </p>
  </div>
</details>

<br>

---

For a detailed overview of my education, experience, certifications, and technical skills:



[Download CV](https://aaronmj7.github.io/assets/Aaron_Modiyil_Joseph_CV.pdf)
