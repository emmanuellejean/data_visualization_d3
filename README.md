Summary 
Let's explore the number of survivors compared to the number of victim by class and by gender. 
Data story: 
People travelling in third class had much less chances of surviving during the Titanic catastroph. Let's see if that trend is the same by gender. 
I want to show how third class had much less survivors than the other classes and then emphasis the difference of survivors between gender. 




Design 
1st draft : Index.html

Let's start by a barchart showing the number of survivors and non survivors by class. 
Most of the styling are default styling or the one used in class. 
Three buttons on the righ allow the viewer to see the same barchart but for only men, or only women or come back to the initial barchart with all the gender. 



2nd Version : IndexV2.html

From the first feedback, I need to change to a percentage of survivors/victims by class. Doing so We will lose the information that there is much more people in 3rd class than in 1st or 2nd. 
I realized that the color of the victims and survivors changed depending on which button is clicked. 
I changed the color of the buttons to a more neutral color and added a more rounded rectangle.
I deleted the y axis label

3rd Version : IndexV3.html
I return to the original barchart showing the number of persons instead of the percentage. 


Feedback
1st feed back:  
What is your story? I don't understand it when I look at your chart !
If you want to compare information, first use proportion so I can compare 1st class to the 2nd and the 3rd class. 
Label on the y axis are too small. 
Add information in the charts.

2nd feedback : 
Dear Emanuelle,

here is my feedback to your visualization.

The message is quite straight forward and can be understood easily.
I also like the simplicity of the visualization.

In my opinion applying a stacked 100% bar chart is misleading because it distorts the absolute numbers of survivors vs. victims across the classes. E.g. when selecting all genders and comparing the classes 2 and 3, the bar for class 2 survivors is twice as high as the one for class 3 survivors. For that reason, I would rather favor the regular stacked bar chart.

For the sake of estetics I would select the same font type for all texts in the chart.
I would also center the legend at top of the chart.

The labels in the tooltip contain engineering terms like 'Survivedlabel' or 'ToCount'.
I would replace them by self-explanatory terms.

If you want you could increase the attractiveness by adding transition effects when switching between the genders.

I hope these comments are helpful.

All the best, Oliver




Resources
http://dimplejs.org/examples_viewer.html?id=scatter_vertical_grouped
http://stackoverflow.com/questions/26792932/dimple-js-scatter-plot-issues
http://dimplejs.org/advanced_examples_viewer.html?id=advanced_storyboard_control
http://dimplejs.org/examples_viewer.html?id=bars_vertical_stacked
https://discussions.udacity.com/t/custom-tooltip-legend-order/189042/6

http://stackoverflow.com/questions/35434829/get-correct-percent-in-dimplejs-vertical-100-bar-chart
http://dimplejs.org/advanced_examples_viewer.html?id=advanced_bar_labels

http://annapawlicka.com/pretty-charts-with-dimple-js/