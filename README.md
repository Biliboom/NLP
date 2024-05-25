# ADA_Final

Welcome to my Advanced Data Analysis project. This repository includes 3 different classification methods, all founded on top of the BERT model: Neural Net, Random Forest, and XGBoost. <br><br>
You can also find the original downloaded dataset in the dat_raw folder. These raw datafiles are cleaned in the Data Cleaning ipynb notebook and exported to the dat_cleaned folder, where they are further broken down by varying data size. <br><br>
You can see that besides the .py files where the main code is included (BERT_NN.py, BERT_XGBOOST.py, and BERT_RF.py), there are other files present. The showcase ipynb files are included as a way of demonstrating how each section of code functions independently, since the final .py files can get to be quite large. <br><br>
The notebooks named as a lowercase version of their respective .py files (bert_nn.ipynb, bert_xgboost.ipynb, and bert_rf.ipynb) are where the .py files are run and the results are presented. <br><br>
You will notice that for the largest datasets (7852), pickle versions of the trained models are saved in the Pickle folder. These trained models are going to be used in the Advanced Programming project where a GUI will use them to make predictions.
