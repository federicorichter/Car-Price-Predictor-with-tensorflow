# Car Price prediction using Machine Learning

This project aims to predict the price of a used car in the US market based on various attributes such as horsepower, manufacturing year, mileage (km), torque, and more. The dataset used for training is sourced from Kaggle. The model is built using TensorFlow and Keras.

### 📊 Data
In any machine learning project, understanding and preprocessing the data is crucial for achieving optimal results. In this project, I used a dataset from Kaggle and leveraged the Pandas library for data reading and processing. Additionally, I used Seaborn for data visualization to explore patterns and relationships between features.
### 🏗️ Model
For this project, I implemented a Sequential model using Keras' Sequential API. The architecture consists of:
  - A normalization layer to scale the input data.
  - Four dense layers, with the final layer producing a single output: the predicted car price.
  - **Compilation settings**:
     - **Optimizer**: Adam
     - **Loss function**: Mean Absolute Error (MAE)
    - **Metrics**: Root Mean Squared Error (RMSE)
   
![image](https://github.com/user-attachments/assets/9c0f6823-0b00-45c6-8618-dca6b9b4edd4)

The model was trained on the selected dataset for 100 epochs.

### 🧪 Validation and testing
After training, the model was evaluated by predicting car prices based on the input parameters (e.g., horsepower, mileage, etc.). The results were compared against the actual car prices using a visualization, which demonstrates the accuracy of the model.
![image](https://github.com/user-attachments/assets/51bc210a-b640-4e6f-a99e-ce33a1cd8bb0)

