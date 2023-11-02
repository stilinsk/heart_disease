# heart_disease

## We will be implementing this end to end project using the heart disease prediction , Where we will be predicting  where a patient is sick or not
   For the following project we are predicting whether someone has a heart disease or not based  the folowing factors:
   Age -age in years sex -(1=male,0 = female)
    cp =chest pain type 0.Typical angina :Chest pain related decrease of blood supply to the heart 1.Typicalangina:chest pain not related to heart 2.Non -anginal pain:typically esophageal spasms (non heart related) Asymptomatic -Chest pains not showing signs of heart diease 
    trestbps -resting blood presssure (in mm Hg on admission to the hospital) anything above 130-140 is typically a concern
     chol -serum cholestoral in mg/dl antything above 200 is a concern 
     fbs -(fasting blood sugar>120mg/dl)(1=true;0=false)
      7 restecg -resting electrocardiograph results Nothing to note ST-T Wave abnormality can range from mild to severe symptoms signals non normal heartbeat possible or definite left ventricular hypertrophy Enlarged hearts main pumping chamber
       thalac =maximum heart rate achieved exang = exercise induced angina(1=yes , 2=no) old peak =ST depression induced by exercise relative to rest looks at stress of heart during exercise unhealthy heart will stress more 
       slope =the slpoe of peak exercise ST segment 0.Upsloping:better heart rate with exercise( uncommon) 1.flatsloping;minmal change (typical healthy heart ) 2.downsloping -signs of an unhealthy heart 
       ca -number of major vessels (0-3)colored by flourosopy colored vessel means blood s passing through 
       thal -thalium stress result 1,3.normal 6.fixed defect used to be defect but ow fixed 77.reversable effect no proper blood mvt while exercising 
       target -have the disease or are healthy(1=yes,0=no)

        We a  first  by perfoming  EDA  then we will pre process our data  then we  will fit a random forest classifier model after that we will tune our hyperparameters to find our best model.  then we will pickle our model and we will be creating an app.py  app from where the interface will be . 
          
          We will create our environment