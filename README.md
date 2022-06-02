# Wine-quality-prediction
Made by: Santiago Villarreal
Use AI in order to predict the quality of a red wine
This project will use the data set of kaggle https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009

![imagen](https://user-images.githubusercontent.com/81925037/171689978-c4daa79f-db79-4066-b905-424cb73ddef6.png)

This dataset has 1599 samples, with 12 labels 

![imagen](https://user-images.githubusercontent.com/81925037/171690741-e2b534e6-064f-4e65-afd1-07539674c61d.png)

The project was made using Python and Colab. The code contains multiple tests on the data in order to obtain the best method for analysis.
For the develop of the project I follow the next steps

  1. Import all the libraries needed
  2. Import the .cvs with all the data and clean the nan values from it
  3. Made some plots for a visual analisis
  4. Get the x and y values and impor our clean data
  5. split the data in 70% 20% and 10% for train validate and test

![imagen](https://user-images.githubusercontent.com/81925037/171731323-cb20feb3-1cec-4b57-910e-1a8b1e64c371.png)

  7. standarization
  8. PCA

![imagen](https://user-images.githubusercontent.com/81925037/171731427-20002e0b-9d69-4aaf-8a37-7370e8d44d69.png)

  10.Train and test KNN and Decision tree with crossvalidation
