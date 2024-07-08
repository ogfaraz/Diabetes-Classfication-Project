# Diabetes-Classfication-Project
This is a Machine Learning oriented project that predicts if a Human has diabetes or not.
It also have a Prediction front-end Interface; which is made with HTML+CSS.

Diabetes Prediction using various human factors, such as age, Blood Pressure, Glucose, Skin thickness etc.
The factors might be extracted from medical records or tests of the object.

## Use:
The Diabetes Classification.ipynb notebook is the data analysis, model evaluation and model selection.
On this current dataset, Random Forest Classifier was relatively more efficient than other Classfifiers.

ML-Proj-Report.pdf is the Project Report of our group project.


### TO USE THIS MODEL: 

- 'requirements.txt' contains the required modules for this project.
- Install each using the 'pip install' command.

  
- I have uploaded the model in this repository, but if you want to create your own...
- Go to the project Directory and run 'Diabetes Predictor - Deployment.py' file.
- It will train and dump the model i.e. a pkl file: 'diabetes-prediction-rfc-model.pkl'


- Now you can run the app.py which will use that dumped model for prediction.
- The interface will be loaded for the files 'index.html' and 'result.html'

  Have Fun!
