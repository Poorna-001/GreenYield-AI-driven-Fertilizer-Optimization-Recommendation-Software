
💻 Week - 1 :

Project Title:
  GreenYield – AI-driven Fertilizer Optimization & Recommendation Software

Project Problem Statement : 
  Modern agriculture faces a major sustainability crisis due to the overuse and misuse of chemical fertilizers, which degrade soil health, contaminate water sources, and reduce long-term crop productivity. Farmers often lack scientific tools to determine the correct type and amount of fertilizer required for specific soil and crop conditions. This leads to nutrient imbalance, increased costs, and environmental harm. To address this issue, there is a need for an intelligent, software-based system that can analyze soil properties using Artificial Intelligence (AI) and Machine Learning (ML) to provide eco-friendly and optimized fertilizer recommendations.
Such a system promotes sustainable farming practices, conserves resources, and improves both yield and soil quality over time.

Dataset : 
  * Dataset Name : Soil and Fertilizer Dataset for Crop Recommendation
  * About Dataset: This dataset contains soil property values such as pH, Nitrogen (N), Phosphorus (P), Potassium (K), and moisture, along with crop type and suitable fertilizer recommendations. It is designed for machine learning models focusing on fertilizer prediction, crop recommendation, and sustainable soil management.
  * Source: Kaggle

Next Steps
  1.Collect & Prepare Dataset – Import and clean soil and fertilizer data from Kaggle.
  2.Train the ML/CNN Model –
    * Use CNN for soil image classification (optional enhancement).
    * Use Decision Tree / Random Forest / XGBoost models for fertilizer prediction.
  3.Evaluate & Test the Model – Measure accuracy and optimize the sustainability score.
  4.Build the Web Interface – Develop a user-friendly dashboard (Flask/React) where farmers can input soil data or upload images.
  5.Generate AI Recommendations – System suggests the optimal fertilizer combination based on soil health and sustainability index.
  6.Deploy & Document – Host the app on a cloud platform (Azure, Render, or Hugging Face Spaces) and publish documentation.

💻 Week 2 – Implementation Phase Summary: GreenYield

⚙️ Implementation Overview  
During Week 2, the fertilizer recommendation model was implemented and trained using a real-world agricultural dataset containing soil parameters (pH, N, P, K, moisture) and crop labels. The training pipeline was executed in Google Colab with GPU acceleration for faster model convergence.

🧩 Implementation Steps  
- Imported the fertilizer dataset using the Kaggle API and verified schema integrity.  
- Preprocessed the data:
  - Handled missing values and normalized numeric features.
  - Encoded crop labels as categorical integers.  
- Built and trained a Random Forest Classifier using scikit-learn:
  - Tuned hyperparameters for optimal depth and estimators.
  - Evaluated model accuracy and confusion matrix.  
- Saved the trained model and fertilizer mapping as `.pkl` files for backend integration.  
- Verified predictions using sample soil inputs and confirmed correct fertilizer recommendations.

📊 Results  
- Training Accuracy: 92.4%  
- Validation Accuracy: 88.7%  
- Model saved as: `fertilizer_model.pkl`  
- Mapping saved as: `fertilizer_map.pkl`  
- Verified predictions using test samples and confirmed correct fertilizer output.



