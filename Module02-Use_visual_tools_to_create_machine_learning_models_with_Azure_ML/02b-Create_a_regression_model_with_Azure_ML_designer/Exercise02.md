# Microsoft Ai-900 (Adrián Arenilla Seco) - Microsoft Learning Path Exercises


## Exercise 02: Create a Regression Model with Azure Machine Learning designer
![](automobile.png)

### [Go to Learning Path Exercise 02 -->](https://docs.microsoft.com/en-gb/learn/modules/create-regression-model-azure-machine-learning-designer)


Sign into Azure Machine Learning studio using your Microsoft account. Select your Azure directory and subscription, and your Azure Machine Learning workspace.
![](Evidences/Image01.png)


Create a new Compute instance.
![](Evidences/Image02.png)


Fill in all exercise fields and create.
![](Evidences/Image03.png)


Create a new pipeline into Designer page.
![](Evidences/Image04.png)


Change the compute target on which to run the pipeline.
![](Evidences/Image05.png)


Go to preview data within the Automobile price data to review the schema of data.
![](Evidences/Image06.png)


Review the data.
![](Evidences/Image07.png)


Drag a Select Columns in Dataset module to the canvas.
![](Evidences/Image08.png)


Set the columns as in the image (Select Columns in Dataset).
![](Evidences/Image09.png)


Set the columns as in the image (Clean Missing Data).
![](Evidences/Image10.png)


Set the columns as in the image (Normalize Data).
![](Evidences/Image11.png)


Ensure your pipeline looks similar to the image and run the pipeline.
![](Evidences/Image12.png)


Correct result after running the pipeline.
![](Evidences/Image13.png)


Add and set training modules to the canvas and Submit.
![](Evidences/Image14.png)


Correct result after running the pipeline.
![](Evidences/Image15.png)


Note that next to the price column (which contains the known true values of the label) there is a new column named Scored labels, which contains the predicted label values.
![](Evidences/Image16.png)


Add and set an Evaluate Model module to the canvas and Submit.
![](Evidences/Image17.png)


Go to evaluation results section and view the results. These include the regression performance metrics.
![](Evidences/Image18.png)


Create and run an inference pipeline.
Your inference pipeline predicts prices for cars based on their features.
![](Evidences/Image19.png)


Deploy a predictive service.
![](Evidences/Image20.png)


Wait until the deployment status is healthy.
![](Evidences/Image21.png)


Create a new notebook file.
![](Evidences/Image22.png)


Verify that predicted price is returned.
![](Evidences/Image23.png)


### [<-- Back to readme](../../../../)