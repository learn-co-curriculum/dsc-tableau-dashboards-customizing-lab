
# Tableau Dashboards Customizing - Lab

## Introduction
We have taken a look at the tools available for building a _Dashboard_ in the previous lesson. In this lab, we will put those tools to use. We will start with a data set, and create a few visualizations to help highlight some important information for the stakeholder, and finally we will combine that work into a useful _Dashboard_ that can be shared.

## Objectives
You will be able to: 
* Create a Dashboard with 3 informative vizzes
* Add and customize a title and header ti the Dashboard
* Add an interactive element to the vizzes

## Import the Data
For this lab, you will continue to use the Superstore data set you have been using and you will use the visualizations you have already created. You should have saved the workbook you used in the __Useful Visualizations Lab__ so we will use those worksheets and assemble them into a _Dashboard_ that and we will add some interactivity to it as well.

## Create a Dashboard
Using one of the two methods described in the previous lesson, create a new blank _Dashboard_.  Once the _Dashboard_ is open, you should see all of your worksheets you have created on the left side of the screen. To add these visualizations to the workspace, we will first need to create some containers to put them in so we can organize them. Before creating the containers, however, you will first want to take a moment and decide how your dashboard will be viewed. In our case, we want to format the dashboard to be viewed on a desktop computer. The default device will likely be for a phone, and you will want to remove this device by clicking on the set of three horizontal dots to the right of the option and selecting __Delete Layout__. Next you will want to choose the size of the dashboard by clicking on the dropdown menu under _Size_ and clicking on __Range__ to change the selection to __Fixed Size__ then another dropdown will appear with a selection of sizes, choose __Generic Desktop__. You should now have a dashboard suited for viewing on a desktop computer. Now you can begin placing objects to create your dashboard. Below is what the final dashboard should look like, so take a moment to look at it and think about the components.

<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/tableau/completed_dashboard.png" alt="Example of our finished dashboard to aid in design" width=100%>

## Adding Containers
In the example, you can see that we want two vizzes side by side, so you will need to first add a horizontal container to the workspace. You will also see that there are two other containers that we will need, so add two more horizontal containers to the workspace. Don't worry about the sizes of the containers yet, you can adjust those once you have added in the vizzes.

## Adding in the Vizzes
The middle of the example viz has the bar chart on the left and the scatter plot on the right. Drag each of those vizzes into the middle container and place them side by side. You'll notice that the legends for each of the vizzes get placed automatically and they are not always placed in the best position. To fix this we will drag each of the legends into the top container and drop them side by side. You can adjust the width of each of the items individually, but Tableau has a tool to help with that. Click on any of the legends and open the _More Options_ menu. Here you will see an option to select the horizontal container and choosing this option will indeed select the entire container. Now you can open the _More Options_ menu for the container and you will see an option to _Distrubute Contents Evenly_, select this option and you will see your legends will look much better. Do the same with the vizzes as well. You can also adjust the size of each of the objects by selecting and then dragging the edges to adjust the size to fit better and make the vizzes easier to view, take a moment to adjust what you have this far and make it better for the viewer. Once you have finished these steps, the result should be something like the image below.

<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/tableau/container_example.png" alt="Example of the dashboard after adding in the vizzes and adjusting the size of the objects" width=75%>

Next, let's add in another viz in the remaining container. Drag the _Line Graph_ into the bottom container and adjust the sizes of all of the objects to make it easy for your viewer to see all of the information. Your _Dashboard_ should look similar to the one below.

<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/tableau/bar_scatter_line.png" alt="Example of our finished dashboard to aid in design" height=350>

## Adding Interactive Elements
Now that we have the vizzes where we want them, we want to make some tools for the viewer to filter the view according to their needs. For this, we will add some filters, which can be done by selecting _Filters_ from the _More Options_ menu on each viz. Do this with the bar chart and choose _Category_ as the filter. You should see a section get added to the dashboard which contains checkboxes for the _Category_. If you click on any of the selections in this box, you will notice that it only affects the bar chart. We want this action to affect all of the vizzes, to make this happen, you simply need to select _Apply to Worksheets>All Using This Data Source_. Once you have done this you will see that all other vizzes change when you make a selection. You can also change the selection behavior in the _More Options_ menu to allow for only one selection, multiple selections, etc. Set the behavior to the manner in which you wish your viewer to be able to control the vizzes.

## Summary
Summary goes here
