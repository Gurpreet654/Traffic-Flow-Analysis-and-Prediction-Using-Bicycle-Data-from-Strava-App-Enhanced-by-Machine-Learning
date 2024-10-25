# Traffic-Flow-Analysis-and-Prediction-Using-Bicycle-Data-from-Strava-App-Enhanced-by-Machine-Learning
To quantify and predict the impact of traffic lights on bicycle traffic flow, using machine learning to enhance insights. This study will adapt and expand upon the methodology of the paper "Impact Analysis of Accidents..." by Golze et al., specifically applying predictive ML models to bicycle movement data collected through Strava.
## Project Phases:

### Data Collection and Preprocessing (Strava Integration):
Using the Strava app, I will gather bicycle movement data at various traffic-light-controlled intersections. Collected features will include timestamps, GPS location, speed, stop durations, and acceleration patterns. Preprocessing will include data cleaning, normalization, and feature engineering, specifically adding new features to represent waiting times, time of day, and speed variance around traffic lights.

### Traffic Light Impact Analysis (Initial Phase):
Following the methodology in Golze et al., the initial analysis will assess how cycling flow is interrupted by traffic lights. This baseline will involve:

### Identifying intersections regulated by traffic lights.
Extracting data on stop frequencies, wait durations, and acceleration/deceleration patterns.
Evaluating initial traffic flow patterns without ML to understand traffic light effects.
### Machine Learning Model Development:
In this phase, I will apply machine learning to enhance the model's predictive capabilities:

Feature Selection and Engineering: Additional features like day of the week, weather conditions, and cycling speed patterns will be considered.
### Training Predictive Models: 
Supervised learning models (e.g., Random Forest, Gradient Boosting, or Neural Networks) will be trained to predict the likelihood of a stop at a traffic light based on variables such as time, speed, and prior stop durations.
Sequence Prediction with RNNs: If temporal patterns are crucial, a Recurrent Neural Network (RNN) or Long Short-Term Memory (LSTM) network could be applied to predict the duration of stops at intersections based on sequential data.
### Model Evaluation and Improvement:
The model’s performance will be evaluated using metrics like Mean Absolute Error (MAE) for stop duration predictions and classification accuracy for predicting traffic light stops. Hyperparameter tuning will refine the models to improve predictive accuracy, potentially introducing ensemble methods to strengthen results.

### Comparative Analysis and Iterative Refinement:
Each machine learning iteration will be compared with the initial, non-ML results to identify significant improvements. Findings from each phase will be shared, allowing for adjustments in the ML models and additional feature engineering if required.

### Result Sharing and Final Report:
After iterative testing and refinement, final results will be documented, comparing the predictive accuracy of ML-enhanced models versus the baseline model. Insights will focus on how well the ML models predict traffic light impact on cycling flow and suggest potential improvements in traffic management at intersections for cyclists.

# Expected Outcomes:
The project aims to produce a highly accurate predictive model for traffic light impacts on bicycle traffic flow, leveraging ML for better precision in flow analysis and pattern recognition. The results could contribute to more cyclist-friendly urban traffic management strategies and provide a framework for future studies involving ML-based traffic flow analysis.

