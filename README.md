# Zimnat-Insurance-Zindi-competition
This notebook summarises the work we've done at the <a href='https://zindi.africa/competitions/zimnat-insurance-recommendation-challenge'> Zindi competition Zimnat Insurance Recommendation Challenge</a>: <br>
In this competition, you will leverage data and ML methods to improve market outcomes for insurance provider Zimnat, by matching consumer needs with product offerings in the Zimbabwean insurance market. Zimnat wants an ML model to use customer data to predict which kinds of insurance products to recommend to customers. The company has provided data on nearly 40,000 customers who have purchased two or more insurance products from Zimnat.
Your challenge: for around 10,000 customers in the test set, you are given all but one of the products they own, and are asked to make predictions around which products are most likely to be the missing product. This same model can then be applied to any customer to identify insurance products that might be useful to them given their current profile. <br><br><br>
Train.csv file contains the training data we used to train our models .<br>
Test.csv file contains the test data we have to use for the submission.<br>
Zimnat_Insurance_3.ipynb is the jupyter notebook containing the code for our work , you can either run it on a local jupyter notebook on your computer or on <a href='https://colab.research.google.com/notebooks/intro.ipynb#recent=true'> Google Colaboratory</a>. <br><br><br>
**Our strategy in this competition** : <br>
We first tried to use Catboost , Neural networks and LGBM then we did a little bit of stacking to increase the score by some percents and it actually worked.
We could've probably increased the score more by further fine tuning our models and some more stacking.

