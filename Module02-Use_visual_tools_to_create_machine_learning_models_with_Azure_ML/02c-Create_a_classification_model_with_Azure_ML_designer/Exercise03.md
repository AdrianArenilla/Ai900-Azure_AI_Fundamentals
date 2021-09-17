# Microsoft Ai-900 (Adrián Arenilla Seco) - Microsoft Learning Path Exercises


## Exercise 03: Create a classification model with Azure Machine Learning designer
![](diabetes.png)

### [Go to Learning Path Exercise 03 -->](https://docs.microsoft.com/en-gb/learn/modules/create-classification-model-azure-machine-learning-designer)


Create a dataset from web files.
![](Evidences/Image01.png)


Fill in all exercise fields and create.
![](Evidences/Image02.png)


Verify imported data from web file.
![](Evidences/Image03.png)


Change the compute target on which to run the pipeline.
![](Evidences/Image04.png)


Go to preview data within the diabetes-data to review the schema of data.
![](Evidences/Image05.png)


Set the columns as in the image (Normalize Data).
![](Evidences/Image06.png)


Ensure your pipeline looks similar to the image and run the pipeline.
![](Evidences/Image07.png)


Correct result after running the pipeline.
![](Evidences/Image08.png)


Add and set the Split Data module to the canvas.
![](Evidences/Image09.png)


Add and set the Train Model module to the canvas.
![](Evidences/Image10.png)


Add and set the Two-Class Logistic Regression module to the canvas.
![](Evidences/Image11.png)


Add and set the Score Model module to the canvas.
![](Evidences/Image12.png)


Add and set training modules to the canvas and Submit.
![](Evidences/Image13.png)


Correct result after running the pipeline.
![](Evidences/Image14.png)


Note a new column named Scored Probabilities columns containing a probability value between 0 and 1.
![](Evidences/Image15.png)


Add an Evaluate Model module to the canvas.
![](Evidences/Image16.png)


Select Submit, and run the pipeline using the existing experiment.
![](Evidences/Image17.png)


Correct result after running the pipeline.
![](Evidences/Image18.png)


Note the result to view the performance metrics.
![](Evidences/Image19.png)


Rename the new pipeline to Predict Diabetes within Real-time inference pipeline.
![](Evidences/Image20.png)


Add a new module (Enter Data Manually) to the canvas.
![](Evidences/Image21.png)


Add a new module (Execute Python Scrip) to the canvas.
![](Evidences/Image22.png)


Run the pipeline as a new experiment.
![](Evidences/Image23.png)


Correct result after running the pipeline.
![](Evidences/Image24.png)


Deploy a new real-time endpoint.
![](Evidences/Image25.png)


Wait until the deployment status is healthy.
![](Evidences/Image26.png)


Create a new notebook file.
![](Evidences/Image27.png)


Verify that predicted diabetes diagnosis is returned.
![](Evidences/Image28.png)


### [<-- Back to readme](../../../../)