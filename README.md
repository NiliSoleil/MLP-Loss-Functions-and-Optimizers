# MLP-Loss-Functions-and-Optimizers
A class project to identify the impact of various Loss Functions and Optimizers on Dataset

**House Price Prediction with a Neural Network**

This repository contains a class project for Predicting House Price using a Multilayer Perceptron (MLP) neural network. 

**Project Objectives**

The main goal of this project is to **explore the impact of different choices in Loss Function and Optimizer in the deep learning process** using following procedure:

**Data Preparation:** 📊 To understand the process of preparing and preprocessing a real-world dataset. 

**Model and Loss Function Selection:** 🧠 To evaluate the performance of different loss functions on the model's accuracy.

**Optimizer Analysis:** ⚙️ To compare the performance of various optimizers and their effect on the learning curve.

**Model Training and Saving:** 💾 To train the model, evaluate its results, and save the best-performing model.

**Key Project Steps**

This educational project was completed based on the following stages:

1. Dataset Preparation📚 The dataset was loaded from the data folder.

    🗑️ The proximity_ocean column was removed for analysis.
   
    🏷️ The value_house_median column was selected as the label, and other columns were used as input features.
    
    🔪 The data was split into three sections: Training (70%), Evaluation (20%), and Testing (10%).
    
    📦 A DataLoader was used for batching the data.

2. Neural Network Model Definition🧠
    
    A suitable Multilayer Perceptron model with an appropriate activation function was defined.
   
3. Device Selection🚀 The model was moved to a GPU for faster training, and the type of device provided by Colab was printed.

4. Loss Function Definition and Comparison📉
   
   **Huber Loss**,
   
   **L1 Loss**,
   
   **MSE Loss**,
   
   and a **custom Adaptive Loss** were implemented and their performance was evaluated.
   
📊 The r2 metric was calculated for each loss function, and the results were compared in a table.

5. Optimizer Analysis🚀

  Using Adaptive Loss as the loss function, the performance of the Adam, SGD, SGD_M, SGD_Nest, and rmsprop optimizers was compared.

  📈 The learning curve for each optimizer was plotted on a single graph to show their performance differences.

6. Model Training and Saving✅ The best-performing model was selected, and its final loss and accuracy values were saved in an appropriate folder.
      
How to Run the CodePrerequisites:

  🛠️ Make sure you have the necessary libraries, such as PyTorch, installed.

  Run the Notebook: 🖥️ The code is available here

  https://github.com/NiliSoleil/MLP-Loss-Functions-and-Optimizers/blob/main/MLP_Loss_Functions_Optimizers.ipynb
  
  You can run it in Google Colab or any Jupyter environment. 
  
  
Niloufar Soleil




