# SENG550-taxi-prediction-project

### Set Up
This project was created on the Google Colaboratory platform. To run, please do the following:

1. Download the ipynb file
2. Download the test and train csv files
3. Upload the ipynb and csv files to your Google Drive
4. In the notebook file, navigate to the sixth cell containing the following:
   ```
   train_file_path = '/content/drive/My Drive/SENG 550 - Group Project/train.csv'
   import os
   with open(train_file_path, 'r') as file:
   content = file.read()
   ```
5. Replace the path with the actual path where the csv files are located in Google Drive
6. Click 'Runtime' in the top menu and select 'Run All' from the menu
7. Accept permissions to access files in your Google Drive when the overlay appears
