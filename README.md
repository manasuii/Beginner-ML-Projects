🚀 Beginner ML Projects

A collection of beginner-friendly Machine Learning and Deep Learning projects I built while learning core ML concepts, algorithms, and deployment workflows. Each project includes data preprocessing, model training, evaluation, and in some cases, deployment.

📌 Project 1 — Student Placement Prediction (Logistic Regression)

Goal: Predict whether a student gets placed based on CGPA and IQ.
Techniques Used:

Data preprocessing

Train–test split

Feature scaling

Logistic Regression

Decision boundary visualization

Model saving

Deployment using Streamlit

📌 Project 2 — Test Preparation Course Completion Prediction

Dataset: StudentsPerformance.csv (Kaggle)
Features: Math score, Reading score
Target: Test preparation course

0 → Not completed

1 → Completed

Techniques Used:

Logistic Regression

StandardScaler

Train/Test split

Decision boundary visualization

Model evaluation

Result: Achieved ~63% accuracy using only two numerical features.

📌 Project 3 — Spam Message Classification (Naive Bayes)

Built a text classification model using Naive Bayes to classify SMS messages as spam or ham.
Dataset: Adapted from Kaggle SMS Spam Collection.
Pipeline includes:

Text preprocessing (cleaning, tokenization, stopwords removal)

TF-IDF vectorization

Naive Bayes training

Evaluation metrics

📌 Project 4 — Breast Cancer Classification (Neural Network)

A binary classifier built using a simple Artificial Neural Network (ANN) to detect whether breast cancer is benign or malignant.
Includes:

Feature scaling

Model building using deep learning

Train/validation split

Accuracy evaluation

📌 Project 5 — Face Mask Detection (Deep Learning)

Built a deep learning image classifier to detect the presence or absence of a face mask.
Includes:

Image preprocessing

CNN model development

Data augmentation

Training & validation

Performance evaluation

📌 Project 6 — PINN Ball Trajectory Prediction (Physics-Informed Neural Network)

Goal: Predict the trajectory of a falling ball using a Physics-Informed Neural Network (PINN) that incorporates both data and the underlying physics (gravity) into training.

Techniques Used:

Data preprocessing and noisy observation handling

Neural network model building with input t and output h(t)

Physics-informed loss function incorporating the ODE: h''(t) = -g

Training using PyTorch with automatic differentiation

Model evaluation by comparing predicted trajectory to the exact solution

Visualization of results showing noisy data, exact solution, and PINN predictions

Result: Successfully learned a parabolic trajectory consistent with the physics of free fall, demonstrating the capability of PINNs to combine data and physical laws in predictive modeling.
