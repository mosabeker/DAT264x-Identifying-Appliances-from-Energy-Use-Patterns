# DAT264x-Identifying-Appliances-from-Energy-Use-Patterns
DAT264x: Identifying Appliances from Energy Use Patterns

competition from :https://www.datasciencecapstone.org/competitions/10/appliances-energy-use/submissions/

a. Steps:
1. run Energy_Use_Patterns_C.ipynb
2. run Energy_Use_Patterns_V.ipynb
3. finally, run Energy_Patterns_Ensemble.ipynb to get ensemble.csv

b. File description:
1. train\ -> train data
2. test\ -> test data
3. "Energy_Use_Patterns_C.ipynb" using InceptionV3 for transfer learning
4. "run Energy_Use_Patterns_V.ipynb" using InceptionResNetV2 for transfer learning

c. Method:
1. Standardize images
2. Create model
3. Traning and validation
4. Finally, get two weight models.
5. Load two .h5 file to ensemble data into .csv file


