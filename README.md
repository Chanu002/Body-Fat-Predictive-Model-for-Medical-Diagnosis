# Body-Fat-Predictive-Model-for-Medical-Diagnosis
This project aims to develop a simple, accessible, and reliable model to predict body fat percentage using only basic body measurements. The model is designed for practical medical or personal health use without relying on expensive or invasive methods like hydrostatic weighing or DXA scans.

📌 Project Overview
Objective: Estimate body fat percentage using easily obtainable body measurements.

Key Features:

Focuses on simplicity and accessibility.

Uses only common measurements:

Circumference of Body Parts like Abodomen, Thighs, Neck etc

Height

Weight

Age

Suitable for use with just a measuring tape and a scale.

Language & Tools: Developed in R, using packages for data modeling and analysis.

⚙️ Methods
This model is built using the following statistical and machine learning techniques:

Ridge Regression: Helps manage multicollinearity and improve prediction stability by penalizing large coefficients.

Poisson Regression (for count-style interpretations): Explored as a modeling alternative, though body fat is continuous—used here to experiment with generalized models.

Other models or methods may be explored for comparison (e.g., linear regression, lasso, etc.).

✅ Why This Is Useful
Medical & Health Use: Offers a low-cost, non-invasive screening tool that can be used in clinics, gyms, or at home.

Accessibility: Avoids reliance on costly tools or specialized facilities.

Speed: Results can be generated quickly with simple inputs.

Public Health Potential: Useful for large-scale screenings in resource-limited settings.

📁 Dataset
The dataset contains body composition data including body fat percentage and multiple body measurements. Only non-complex features are used in the modeling process to ensure ease of replication.

📊 Output
The final model predicts body fat percentage based on the selected variables. Model performance is evaluated using metrics such as:

RMSE (Root Mean Squared Error)

MAE (Mean Absolute Error)

R² (Coefficient of Determination)

🔧 How to Run
Open the R project or script.

Install required libraries (e.g., glmnet, caret, ggplot2, etc.).

Load and clean the dataset.

Run the modeling pipeline.

View predictions and diagnostics.

👩‍⚕️ Disclaimer
This model is not a replacement for professional medical diagnosis. It is intended as a supportive tool for preliminary assessments or research.

