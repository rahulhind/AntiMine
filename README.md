# AntiMine
Anti Hero Project\
#Prediction output abbreviations\
    M---->Mine\
    R---->Rock\
To predict the model:\
->Download "antiMine.pkl" file\
#Libraries 
    ->import joblib #To load data\
    ->import numpy as np\
    
->loaded_model = joblib.load('antiMine.pkl')\
->new_data = ...  # Prepare your new data #2D array\
->predictions = loaded_model.predict(new_data)\
->print(predictions)\
----------------------------------------------------------------
//Sample inputs to test data\
First convert 1D array to 2D array if it is:\
->input_data_2d = input_data2.reshape(1, -1)\

---->Rock Data<------\
input_data1=np.array([0.0200,0.0371,0.0428,0.0207,0.0954,0.0986,0.1539,0.1601,0.3109,0.2111,0.1609,0.1582,0.2238,0.0645,0.0660,0.2273,0.3100,0.2999,0.5078,0.4797,0.5783,0.5071,0.4328,0.5550,0.6711,0.6415,0.7104,0.8080,0.6791,0.3857,0.1307,0.2604,0.5121,0.7547,0.8537,0.8507,0.6692,0.6097,0.4943,0.2744,0.0510,0.2834,0.2825,0.4256,0.2641,0.1386,0.1051,0.1343,0.0383,0.0324,0.0232,0.0027,0.0065,0.0159,0.0072,0.0167,0.0180,0.0084,0.0090,0.0032])\
---->Mine Data<------\
input_data2=np.array([0.0116,0.0179,0.0449,0.1096,0.1913,0.0924,0.0761,0.1092,0.0757,0.1006,0.2500,0.3988,0.3809,0.4753,0.6165,0.6464,0.8024,0.9208,0.9832,0.9634,0.8646,0.8325,0.8276,0.8007,0.6102,0.4853,0.4355,0.4307,0.4399,0.3833,0.3032,0.3035,0.3197,0.2292,0.2131,0.2347,0.3201,0.4455,0.3655,0.2715,0.1747,0.1781,0.2199,0.1056,0.0573,0.0307,0.0237,0.0470,0.0102,0.0057,0.0031,0.0163,0.0099,0.0084,0.0270,0.0277,0.0097,0.0054,0.0148,0.0092])\


