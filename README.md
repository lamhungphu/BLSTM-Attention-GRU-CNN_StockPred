# Stock Price Prediction with BLSTM-Attention-GRU-CNN Ensemble for 10 Companies

**This repository investigates the use of an ensemble model combining Bidirectional LSTM (BLSTM), Attention Mechanism, Gated Recurrent Unit (GRU), and Convolutional Neural Network (CNN) architectures for stock price prediction of 10 companies.**

**Conceptual Approach:**

- BLSTM & Attention: Capture long-term dependencies and focus on crucial information within time series data.
- GRU: Efficiently handle long sequences and potential vanishing gradients.
- CNN: Extract spatial features within the data, potentially identifying hidden patterns.
- Ensemble Approach: Combining the strengths of these architectures aims for more robust and accurate predictions.
  
**What's Included:**
- Jupyter Notebooks: BLSTMAttention+GRU+CNN(10_Companies).ipynb: Script for the whole model.
- Input file Folder: Contains preprocessed stock price data for the 10 companies.

**Getting Started:**
- Download Data and Jupyter Notebook script.
- Run Jupyter Notebooks: Open the Jupyter notebook environment and run the notebook.
- [You can seek for the results and comparisons to other models here](https://drive.google.com/drive/folders/1UM1biVocaGIN-8sI9jzJLhMHIsU38rif?fbclid=IwAR0vpI4n7VIuUb6r1EuCMLEvsyp_p0wDlfdE5JjpbBCQeNMclQdjXEFo73g_aem_Aca4o68SAqp1MTIjZeUFC-LiMeU1Bj1c86TJfO7PBXEXkIkS0H1wFqRKhjcfHJbRh-Co5qq1iKj6_s_VfH5WI4UZ).

**Disclaimer:**
- This is a for-educational-purposes implementation. Stock price prediction is inherently uncertain, and this model should not be used for real-world financial decisions.

**Further Exploration:**

- Experiment with hyperparameter optimization for each sub-model in the ensemble.
- Explore incorporating additional features specific to each company or the broader market.
- Implement a backtesting framework to evaluate the model's performance on historical data for each company.
- Compare the performance of the ensemble model with individual BLSTM, Attention-GRU, and CNN models.
- Feel free to contribute!  We welcome pull requests and suggestions for improvement.

Note:  This readme assumes the data is preprocessed for 10 companies. If the data needs separate preprocessing for each company, the structure of the script might need adjustments.
