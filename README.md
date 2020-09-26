<h1><center>Human Activity Recognition</center></h1>

This project is to build a model that predicts the human activities such as Walking, Walking_Upstairs, Walking_Downstairs, Sitting, Standing or Laying.

This dataset is collected from 30 persons(referred as subjects in this dataset), performing different activities with a smartphone to their waists. The data is recorded with the help of sensors (accelerometer and Gyroscope) in that smartphone. This experiment was video recorded to label the data manually.

<h2>How data was recorded</h2>
By using the sensors(Gyroscope and accelerometer) in a smartphone, they have captured '3-axial linear acceleration'(_tAcc-XYZ_) from accelerometer and '3-axial angular velocity' (_tGyro-XYZ_) from Gyroscope with several variations.

<li>prefix 't' in those metrics denotes time.</li>

<li>suffix 'XYZ' represents 3-axial signals in X , Y, and Z directions.</li>

<h2>Train and Test data were saperated</h2>
The readings from 70% of the volunteers were taken as trianing data and remaining 30% subjects recordings were taken for test data
<h2>Data</h2>
<li>All the data is present in 'UCI_HAR_dataset/' folder in present working directory.</li>
<li>Feature names are present in 'UCI_HAR_dataset/features.txt'</li>
<h3>Train Data</h3>
<li>'UCI_HAR_dataset/train/X_train.txt'</li>
<li>'UCI_HAR_dataset/train/subject_train.txt'</li>
<li>'UCI_HAR_dataset/train/y_train.txt'</li>
<h3>Test Data</h3>
<li>'UCI_HAR_dataset/test/X_test.txt'</li>
<li>'UCI_HAR_dataset/test/subject_test.txt'</li>
<li>'UCI_HAR_dataset/test/y_test.txt'</li>
<h3>Data Size :</h3>
<li>27 MB</li>
<h2>Problem Framework</h2>
<li>30 subjects(volunteers) data is randomly split to 70%(21) test and 30%(7) train data.</li>
<li>Each datapoint corresponds one of the 6 Activities.</li>
<h2>Problem Statement</h2>
<li>Given a new datapoint we have to predict the Activity<li>
