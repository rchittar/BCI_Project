# BCI_Project
This github repository is the code for the LSTM-NARX and CNN models.

For the LSTM-NARX:
- The only runnable code if using the git page is the Feature Prediction(LSTM-NARX) notebook.
  It will run the train and test functions(lower most driver codes) for 300 timesteps of the power spectral entropy train/val/test datasets using a pre-trained PSE autoencoder model. Adjust input directory as needed and set the specific_run arguments to 0 in both prediction_driver and normalize_demap_driver

- If the Feature Prediction code does not work, or the dataset has not been uploaded yet, please use the following google colab notebooks:


  1. https://colab.research.google.com/drive/1DSX_Iu5jFhtYGyX78WzZLJLMLbMbgmS7#scrollTo=wTUVjJyBlNRv (Data Pre-processing Code)
  
  2.https://colab.research.google.com/drive/1Whpq4g0Xwp5mY-jf4cqh81a27sTch-Uy#scrollTo=bdjz9LR67EuK (Autoencoder Code)
  
  3.https://colab.research.google.com/drive/1872T68v1mfqTej0GV5MRU_PKj7m5oxWa (LSTM-NARX code)
  
  The entire data in drive has been shared: https://drive.google.com/drive/folders/1CkNyGw17D2Nct8l4alMKFijJYdwMBquv?usp=sharing 
  
  
For CNN Models:
- Download the Numpy form of the datasets from this repo and upload it to your google drive. Make sure the dataset directories match the ones in your drive.
- You may also use the following colab noteboook and make a copy for convenience (only available to Santa Clara University access):
https://colab.research.google.com/drive/1vPl8tN-wGCE0IaahZLfhWbayi3syImZz?usp=sharing
