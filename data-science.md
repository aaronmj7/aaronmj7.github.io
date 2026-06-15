---
layout: default
title: Aaron Modiyil Joseph
description: MSc Data Science Graduate | Machine Learning & Advanced Analytics
permalink: /data-science/
---

Welcome to my Data Science portfolio.

I am an MSc Data Science graduate (Distinction) with a strong foundation in mathematics, statistics, and machine learning. I specialise in building predictive models, developing end-to-end data pipelines, and applying advanced analytics to generate actionable insights from complex datasets.

Through academic research and applied projects, I have worked on time-series forecasting, clustering, NLP, and deep learning models, translating data into meaningful business and analytical outcomes.

### Technical Skills
**Programming:** Python, R, SQL

**Machine Learning:** Predictive Modelling, Classification Modelling, Clustering, Neural Networks, Deep Learning, Computer Vision, NLP, LLM, Explainable AI, AI Ethics.

**Analytics & Visualisation:** Power BI, Tableau, Excel, Statistical Analysis, Model Evaluation, Feature Engineering

---

# Featured Projects

## Predictive Rating Engine & Feature Importance Analysis on MovieLens
A hybrid deep learning study utilizing attention mechanisms and SHAP values to predict user movie ratings and isolate key content drivers.

### Key Contributions
* Engineered a large-scale data processing pipeline for the MovieLens 32M dataset, generating Word2Vec embeddings from unstructured user tags alongside categorical genres.
* Developed and trained a hybrid wide-deep neural network with attention mechanisms using TensorFlow/Keras to capture complex, non-linear feature interactions.
* Achieved an exceptional validation Mean Absolute Error (MAE) of 0.091, demonstrating highly accurate predictive capabilities for content recommendation systems.
* Executed SHAP (SHapley Additive exPlanations) analysis to interpret model outputs, transforming a "black box" architecture into transparent, quantifiable insights regarding user preferences.

**Skills:** Python · TensorFlow/Keras · Word2Vec · SHAP (Model Interpretability) · Recommender Systems
<br>
🔗 **[View Source Code on GitHub](https://github.com/aaronmj7/YOUR-REPO-NAME)**

<details style="background-color: rgba(0,0,0,0.03); padding: 15px; border-radius: 8px; margin-top: 15px; cursor: pointer;">
  <summary style="font-weight: bold; font-size: 1.1em; color: #1e40af;">
    📄 View Detailed Report & Methodology (Click to Expand)
  </summary>
  
  <div style="margin-top: 15px; cursor: default;">
    <p><b>Project Deep Dive:</b><br>
    Developed during my MSc at the University of Hertfordshire, this project focused on the mechanics of modern content recommendation systems. Utilizing the massive MovieLens 32M dataset, the objective was to move beyond simple collaborative filtering and understand exactly <i>why</i> users rate movies the way they do, based specifically on categorical genres and unstructured user-generated text tags.</p>
    
    <p>To process this diverse data, I utilized Gensim to create Word2Vec embeddings for the text tags, seamlessly integrating them with the structured genre data. I then built a hybrid wide-deep neural network featuring attention mechanisms in TensorFlow/Keras. The model achieved an outstanding validation Mean Absolute Error (MAE) of just 0.091. Crucially, rather than leaving the deep learning model as an uninterpretable "black box," I applied SHAP to provide rigorous statistical transparency. This allowed me to isolate, quantify, and explain the exact features driving user engagement, bridging the gap between advanced predictive modeling and actionable business insights.</p>
    
    <p><i>Scroll through the full project report below:</i></p>
    
    <iframe src="{{ site.baseurl }}/assets/MovieLens_Rating_Engine.pdf" width="100%" height="600px" style="border: 1px solid #ccc; border-radius: 4px;">
      This browser does not support PDFs. 
    </iframe>
    
    <p style="text-align: right; font-size: 0.9em; margin-top: 10px;">
      Having trouble viewing? <a href="{{ site.baseurl }}/assets/MovieLens_Rating_Engine.pdf" target="_blank">Open PDF in new tab</a>
    </p>
  </div>
</details>

<br>

## Fine-Tuning DistilBERT for Toxicity Classification
A natural language processing (NLP) study leveraging a lightweight transformer model to identify and filter harmful online content.

### Key Contributions
* Processed and balanced the Wiki Toxic dataset to optimize transformer model training for binary text classification.
* Fine-tuned a DistilBERT language model, achieving 92% validation accuracy and an exceptional 0.955 ROC-AUC score on imbalanced test data.
* Analyzed precision-recall trade-offs, explicitly prioritizing high recall to ensure maximum detection of toxic content for community moderation.
* Evaluated model limitations regarding false positives, outlining strategic architectural improvements such as secondary filtering models.

**Skills:** Python · NLP · DistilBERT (Transformers) · Text Classification · Precision-Recall Analysis
<br>
🔗 **[View Source Code on GitHub](https://github.com/aaronmj7/Assignment_3_LLM)**

<details style="background-color: rgba(0,0,0,0.03); padding: 15px; border-radius: 8px; margin-top: 15px; cursor: pointer;">
  <summary style="font-weight: bold; font-size: 1.1em; color: #1e40af;">
    📄 View Detailed Report & Methodology (Click to Expand)
  </summary>
  
  <div style="margin-top: 15px; cursor: default;">
    <p><b>Project Deep Dive:</b><br>
    Developed as part of my MSc coursework at the University of Hertfordshire, this project explored the application of advanced Large Language Models (LLMs) in creating safer digital environments. The core objective was to build a robust binary classification engine capable of detecting toxic online comments. I utilized the Wiki Toxic dataset, carefully balancing the data during preprocessing to optimize the model's training phase and prevent majority-class bias.</p>    
    <p>For the architecture, I selected DistilBERT—a lighter, faster variant of BERT that retains exceptional language comprehension while remaining computationally efficient. The fine-tuned model performed exceptionally well, securing a 92% accuracy rate on balanced data and a 0.955 ROC-AUC score on the imbalanced test set. Crucially, the model demonstrated high recall, meaning it successfully flagged the vast majority of harmful content. While this resulted in occasional false positives, this conservative behavior is ideal for strict content moderation environments. Future iterations of this pipeline would focus on integrating a secondary filter model to refine accuracy on edge cases.</p>    
    <p><i>Scroll through the full project report below:</i></p>    
    <iframe src="{{ site.baseurl }}/assets/DistilBERT_Toxicity_Detection.pdf" width="100%" height="600px" style="border: 1px solid #ccc; border-radius: 4px;">
      This browser does not support PDFs. 
    </iframe>    
    <p style="text-align: right; font-size: 0.9em; margin-top: 10px;">
      Having trouble viewing? <a href="{{ site.baseurl }}/assets/DistilBERT_Toxicity_Detection.pdf" target="_blank">Open PDF in new tab</a>
    </p>
  </div>
</details>

<br>

## Image Segmentation with Deep Learning
A computer vision study developing a custom convolutional neural network to perform multi-class instance segmentation on the COCO dataset.

### Key Contributions
* Engineered a robust preprocessing pipeline for a specialized subset of the COCO-2017 dataset, incorporating normalization, resizing, and augmentation.
* Implemented sample weighting to address severe class imbalances across the four target categories (cake, car, dog, person).
* Designed and trained a custom encoder-decoder Convolutional Neural Network (CNN) architecture using TensorFlow/Keras(Python).
* Evaluated pixel-wise classification using the Intersection over Union (IoU) metric and Sparse Categorical Cross-Entropy loss, identifying how dominant background classes impact model generalization.

**Skills:** Python · Computer Vision · TensorFlow/Keras · Image Segmentation · CNNs (Encoder-Decoder)
<br>

<details style="background-color: rgba(0,0,0,0.03); padding: 15px; border-radius: 8px; margin-top: 15px; cursor: pointer;">
  <summary style="font-weight: bold; font-size: 1.1em; color: #1e40af;">
    📄 View Detailed Report & Methodology (Click to Expand)
  </summary>
  
  <div style="margin-top: 15px; cursor: default;">
    <p><b>Project Deep Dive:</b><br>
    Developed as part of my MSc coursework at the University of Hertfordshire [cite: 3], this computer vision project explored the complexities of semantic image segmentation. Using a specialized subset of the COCO-2017 dataset, the objective was to train a neural network to accurately map distinct boundaries for four target classes: cake, car, dog, and person.</p>    
    <p>The preprocessing pipeline was designed to maximize training efficiency. Images were standardized to 512x512 pixels and augmented using translation, zoom, and contrast adjustments to introduce necessary variability. Because the dataset featured a significant class imbalance, specific class weights were calculated and sampled to prevent majority-class bias. The core architecture was a custom encoder-decoder model, optimized via the Adam optimizer and evaluated against the standard Intersection over Union (IoU) metric.</p>    
    <p>Crucially, the evaluation phase required deep diagnostic analysis. While the training loss was remarkably low, the mean IoU revealed challenges in generalizing to unseen validation data. By analyzing the model's predictions, I identified that the dominant background class heavily influenced the outcome, exposing the limitations of training complex architectures on smaller, constrained datasets. This rigorous diagnostic process highlights my ability to critically evaluate model behavior beyond top-line accuracy metrics.</p>    
    <p><i>Scroll through the full project report below:</i></p>    
    <iframe src="{{ site.baseurl }}/assets/Image_Segmentation_Report.pdf" width="100%" height="600px" style="border: 1px solid #ccc; border-radius: 4px;">
      This browser does not support PDFs. 
    </iframe>    
    <p style="text-align: right; font-size: 0.9em; margin-top: 10px;">
      Having trouble viewing? <a href="{{ site.baseurl }}/assets/Image_Segmentation_Report.pdf" target="_blank">Open PDF in new tab</a>
    </p>
  </div>
</details>

<br>

## Financial Market Forecasting and Risk Analysis
A time-series forecasting project analysing historical market data to identify trends and evaluate forecasting performance.

### Key Contributions
* Engineered a time-series pipeline to process and scale 17 years of historical stock data (2006–2023) to capture temporal market dependencies.
* Developed and fine-tuned a sequential LSTM model with dense layers and dropout regularization to prevent market overfitting.
* Achieved over 91% prediction accuracy within a 2% error margin, significantly outperforming standard RNN architectures.
* Evaluated model robustness using statistical error metrics (RMSE, MAE) to demonstrate viable decision-support for equity analysis.

**Skills:** Python · Time-Series Analysis · Forecasting · Power BI
<br>
🔗 **[View Source Code on GitHub](https://github.com/aaronmj7/Stock-Market-Analysis)**

<details style="background-color: rgba(0,0,0,0.03); padding: 15px; border-radius: 8px; margin-top: 15px; cursor: pointer;">
  <summary style="font-weight: bold; font-size: 1.1em; color: #1e40af;">
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

---

For a detailed overview of my education, experience, certifications, and technical skills:



[Download CV](https://aaronmj7.github.io/assets/Aaron_Modiyil_Joseph_DS_CV.pdf)
