# Detailed description of Iris Data 

#### We begin with importing a few modules
  * pandas
  * seaborn
  * matplitlib
  
We then load the Iris dataset, which is saved in Jupyter as well as Github account
We print what is in the Iris data to get an idea of what we are going to be using.

We also want to see how many examples we have to work with for each species.

#### Begining to plot our data
We first have to add the extension from panda that will allow us to add a graph. 
We do this by calling the .plot extension.
We make a scatter plot showing the difference between the PetalLength and Petal Width.

We also use seaborn to make a jointplot showing bivariate scatterplots and univariate histograms together in the same image.

We will also use seaborn to call the facetgrid which colors the scatterplots and shows the species of each color.

#### Individual features
We can use boxplot to see individula features of the Sepal Length as well as addint individual points on top of the boxplot with striplot.
This can be a lttle confusing as it make a plot look busy, so to simplify this we use violin plot.
Violin plot will combine the above two plots and simplifies them.

#### All feature combination
Pairplot is another seabron plot which will show us the relation between each pair of features.
This plot shows us that Iris-Setosa is seperated from the other two Iris species based on its features.


#### Panda plots
Panda allows us to make individual box plots for each speies showing their features. 
Panda also has a plot called Andrews Curves, this plot uses coefficients for fourier series.
We can also use this plot to show the parrallel coordinates of each feature on a separate column and then will connect the features for each data sample.
The final plot shows the multivariate visualizatio technique with radviz. 
This plot shows everything on a 2D plane, havign each sample attached to the points through a spring weighted by values for that feature.
