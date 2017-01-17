Summary 
Let's explore the number of survivors compared to the number of victim by class and by gender. 
Data story: 
People travelling in third class had much less chances of surviving during the Titanic catastroph. Let's see if that trend is the same for the females and males of every classes. 
I want to show how third class had much less survivors than the other classes and then emphasis the difference of survivors between gender. 




Design 
1st draft : Index.html

Let's start by a barchart showing the number of survivors and non survivors by class. 
Most of the styling are default styling or the one used in class. 
Three buttons on the righ allow the viewer to see the same barchart but for only men, or only women or come back to the initial barchart with all the genders. 



2nd Version : IndexV2.html

From the first feedback, I need to change to a percentage of survivors/victims by class. Doing so We will lose the information that there is much more people in 3rd class than in 1st or 2nd, but we have a clear understanding of the ratio of survivors vs victims. 
I realized that the color of the victims and survivors changed depending on which button is clicked. 
I changed the color of the buttons to a more neutral color and added a more rounded rectangle.
I deleted the y axis label as percentahe are informed in every barchart.

3rd Version : IndexV3.html
I returned to the original barchart showing the number of persons instead of the percentage. 
Then I added the percentage information in each barchar areas, so I solve my problem and show both numbers and ratio on the same graph. 
I changed the labels in the tooltip to make them more user meaningful. 

4th version after the 3rd feeback: 
Change of the text on the x-axis to be same size on the y-axis.
Added back the label on the y-axis.  
Added a subtittle to state a more defined point of view. 
I considered switching to a greyscale as recommanded in my third review because I like the idea as to be able to still understand when printed. But I did not want to lose the attractiveness of the color. So I decided to chose a red quite strong for the victims and to get a light blue for the survivors. If someone would print in black and white the graph, he will be able to see the differences. 


Feedback
1st feedback:  a friend 
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




3rd feedback : 
Hi @emmanuelle_185407894:

Thanks very much for the feedback on my visualization. Here are my comments on your work:

I like your graphic. It conveys the key messages (the chance of survival was much greater for females and 1st class passengers) in a clear and logical manner. I also enjoyed the fact that I could toggle between 'male','female' and 'all'.

Here are a few minor points (many of which are points of preference, so take them with a grain of salt):

Consider making the font sizes of the two axes equal (the y-axis font is much smaller than the x)

Consider a label on the y-axis (e.g. "Passengers", "Count", "Passenger Count" etc.)

Have you tried looking at how the graph might look in grayscale, instead of the standard red / blue for dimple? I'm a big fan of grayscale, unless the color really serves a purpose. For example, look at the Quadrant I example here and note how it avoids color and still looks great:

dataremixed.com

Clarity or Aesthetics? Part 2 – A Tale of Four Quadrants | DataRemixed

Previous Post (1 of 3): Data Visualization: Clarity or Aesthetics? Part 2 of 3: A Tale of Four Quadrants: In Part 1, we introduced the notion of a two dimensional plane on which a data [...]

Another advantage of grayscale is the graph can still be interpreted if someone prints it out on a non-color printer. I'm not sure the blue / red color scheme would be.

Consider adding a 2nd sentence to your subtitle that summarizes the key message (e.g. "By and large, 1st class female passengers survived and 3rd class male passengers perished".). I think it will add some punch to the subtitle and help focus your audience's attention on the key message, which they can then verify for themselves by playing with the graphic.
Hope this helps and best of luck to you!

Steve




Resources
http://dimplejs.org/examples_viewer.html?id=scatter_vertical_grouped
http://stackoverflow.com/questions/26792932/dimple-js-scatter-plot-issues
http://dimplejs.org/advanced_examples_viewer.html?id=advanced_storyboard_control
http://dimplejs.org/examples_viewer.html?id=bars_vertical_stacked
https://discussions.udacity.com/t/custom-tooltip-legend-order/189042/6

http://stackoverflow.com/questions/35434829/get-correct-percent-in-dimplejs-vertical-100-bar-chart
http://dimplejs.org/advanced_examples_viewer.html?id=advanced_bar_labels

http://annapawlicka.com/pretty-charts-with-dimple-js/