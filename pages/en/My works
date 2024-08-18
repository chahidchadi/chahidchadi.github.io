---
layout: page
title: Projects
description: 
lang: en
---

# Chadi Chahid - Projects
## Credit Card Fraud Detection System

**Description:**  
Developed a machine learning model to detect fraudulent credit card transactions using a dataset of over 5.7 million transactions. This project involved extensive data preprocessing, feature engineering, and model development to address the significant class imbalance inherent in fraud detection tasks.

**Key Contributions:**
- **Data Preprocessing:** Cleaned and undersampled a large dataset of 5.7 million transactions to create a balanced subset for model training.
- **Feature Engineering:** Created novel features based on transaction patterns, customer behavior, and risk scores to enhance model performance.
- **Model Development:** Designed and trained an XGBoost classifier optimized for imbalanced datasets using SMOTE technique.
- **Model Evaluation:** Achieved high precision (1.00) for non-fraudulent transactions and good precision (0.94) and recall (0.75) for fraudulent transactions.
- **Financial Analysis:** Demonstrated potential savings of approximately $1.8 million by correctly identifying fraudulent transactions.

**Technologies Used:**
- **Machine Learning:** XGBoost, Scikit-learn, SMOTE
- **Data Analysis:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Programming Language:** Python

**Future Improvements:**
- Implement more realistic scenarios for model testing
- Refine performance metrics for better alignment with business objectives
- Enhance model robustness and scalability for large-scale deployment

 # Full Rapport

<embed src="/cv/credit_card_fraud_detection_model_rapport.pdf" width="100%" height="600px" type="application/pdf">


<script>
    // URL of PDF document
    var url = '/cv/credit_card_fraud_detection_model_rapport.pdf';

    // Load the PDF document
    pdfjsLib.getDocument(url).promise.then(function(pdf) {
        // Get the first page
        pdf.getPage(1).then(function(page) {
            var scale = 1.5;
            var viewport = page.getViewport({scale: scale});

            // Get canvas element
            var canvas = document.getElementById('pdf-canvas');
            var context = canvas.getContext('2d');
            canvas.height = viewport.height;
            canvas.width = viewport.width;

            // Render PDF page into canvas context
            var renderContext = {
                canvasContext: context,
                viewport: viewport
            };
            page.render(renderContext);
        });
    });
</script>

 

This project showcases the potential of machine learning in addressing the challenges of credit card fraud detection, while highlighting areas for continued research and improvement in the field.
