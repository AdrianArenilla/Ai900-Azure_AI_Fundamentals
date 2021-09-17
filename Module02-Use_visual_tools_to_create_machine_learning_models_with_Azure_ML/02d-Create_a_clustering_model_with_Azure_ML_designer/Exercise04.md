# Microsoft Ai-900 (Adrián Arenilla Seco) - Microsoft Learning Path Exercises


## Exercise 04: Create a Clustering Model with Azure Machine Learning designer
![](penguins.png)

### [Go to Learning Path Exercise 04 -->](https://docs.microsoft.com/en-gb/learn/modules/create-clustering-model-azure-machine-learning-designer)


Create a dataset from web files.
![](Evidences/Image01.png)


Fill in all exercise fields and create.
![](Evidences/Image02.png)


Verify imported data from web file.
![](Evidences/Image03.png)


Change the compute target on which to run the pipeline.
![](Evidences/Image04.png)


Go to preview data within the penguin-data to review the schema of data.
![](Evidences/Image05.png)


Set the columns as in the image (Select Columns in Dataset).
![](Evidences/Image06.png)


Set the columns as in the image (Clean Missing Data).
![](Evidences/Image07.png)


Set the columns as in the image (Clean Missing Data).
![](Evidences/Image08.png)


Set the columns as in the image (Normalize Data).
![](Evidences/Image09.png)


Ensure your pipeline looks similar to the image and Submit the pipeline.
![](Evidences/Image10.png)


Set up pipeline run as new.
![](Evidences/Image11.png)


Correct result after running the pipeline.
![](Evidences/Image12.png)


View the data, noting that the Species column has been removed, there are no missing values, and the values for all four features have been normalized to a common scale.
![](Evidences/Image13.png)


Add and set the Split Data module to the canvas.
![](Evidences/Image14.png)


Add and set the Train Clustering Model module to the canvas.
![](Evidences/Image15.png)


Add and set the K-Means Clustering module to the canvas.
![](Evidences/Image16.png)


Ensure your pipeline looks similar to the image and Submit the pipeline.
![](Evidences/Image17.png)


Correct result after running the pipeline.
![](Evidences/Image18.png)


Note the Assignments column, which contains the cluster (0, 1, or 2) to which each row is assigned.
![](Evidences/Image19.png)


Add an Evaluate Model module to the canvas, select Submit, and run the pipeline using the existing experiment.
![](Evidences/Image20.png)


Correct result after running the pipeline.
![](Evidences/Image21.png)


Note the result to view the performance metrics.
![](Evidences/Image22.png)


Rename the new pipeline to Predict Penguin Clusters within Real-time inference pipeline.
![](Evidences/Image23.png)


Add a new module (Enter Data Manually) to the canvas.
![](Evidences/Image24.png)


Run the pipeline as a new experiment.
![](Evidences/Image25.png)


Set up pipeline run as new.
![](Evidences/Image26.png)


Correct result after running the pipeline and Deploy.
![](Evidences/Image27.png)


Deploy a new real-time endpoint.
![](Evidences/Image28.png)


Wait until the deployment status is healthy.
![](Evidences/Image29.png)


Create a new notebook file.
![](Evidences/Image30.png)


Verify that predicted cluster is returned.
![](Evidences/Image31.png)


### [<-- Back to readme](../../../../)