## Background
Pymaceuticals Inc is a burgeoning pharmaceutical company based out of San Diego. Pymaceuticals specialises in anti-cancer pharmaceuticals. In its most recent efforts, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.


I have been given access to the complete data from their most recent animal study. In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study is to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. 

I have generated all of the tables and figures needed for the technical report of the study.

* Generated a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

* Generated a bar plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the total number of timepoints for all mice tested for each drug regimen throughout the course of the study.

* Generated a pie plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the distribution of female or male mice in the study.

* Calculated the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.

* Using Matplotlib, I have generated a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their colour and style.

* Generated a scatter plot of tumor volume versus mouse weight for the Capomulin treatment regimen.

* Calculated the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plot the linear regression model on top of the previous scatter plot.

## Visualisations
![drug treatment count](https://user-images.githubusercontent.com/80393628/131207827-f7dae018-5b97-4f66-9730-38a17f58576e.PNG)

![gender percentage](https://user-images.githubusercontent.com/80393628/131207830-e51370df-1f7e-44af-a1a9-74e334fd7e5f.PNG)

![tumor volume Capomulin](https://user-images.githubusercontent.com/80393628/131207831-9d78b059-5094-4ea5-b6ba-0f5dd23b8c4c.PNG)

![tumor volume Ramicane](https://user-images.githubusercontent.com/80393628/131207833-de10b704-e43a-412a-92ff-c59c4941d3d1.PNG)

![tumor volume Infubinol](https://user-images.githubusercontent.com/80393628/131207834-f2902f7d-2913-47b3-9e59-73c8c4a1064c.PNG)

![weight v tumor vol](https://user-images.githubusercontent.com/80393628/131207835-0dd14012-6842-427d-99e2-ae819b9701e4.PNG)
