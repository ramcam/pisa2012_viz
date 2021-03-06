##PISA 2012
**A visualization based on 50000 samples from the [PISA 2012 dataset](https://www.oecd.org/pisa/pisaproducts/pisa2012database-downloadabledata.htm>PISA 2012 dataset) by Guillermo Ramírez Camarero.**


###Summary
The PISA test measures how 15-year-old students perform in reading and math across several countries. More important than knowing which country is first or second is knowing how far the worst performing countries lie from the top rankers. For example, a remarkable student in Romania (percentile 75) would be an average student in Denmark and close to the lowest quartile in Japan. The box and whiskers plot is coloured with the intention of dividing the countries into four groups according to their mean performance in the test. In a globalized world education inequality increasingly tranlates into economical inequality. Aggregate data can help us grasp the big picture, but it eventually hides some interesting subtleties. With the help of some buttons countries can be sorted with other criteria in order to discover how boys and girls differ in performance around the globe or which countries manage to educate top achievers without leaving too many students behind.


###Design
After the exploratory data analysis, my intention was to build a visualization that showed that a student in percentile 75 of some countries could be a student in percentile 25 in other countries. The main idea was to portrait the differences that exist in the mean score depending on the country in which the students have been educated.  Since I wanted to compare categorical data (countries) with continuous data (score in test) obtained by aggregation, a box and whiskers plot seemed the best option. Sorting the countries by mean score would help understand the differences in score better.

After feedback, I colored the countries in four groups according to their mean score. This would allow the readers to sort the countries into a few groups easily. This opened a new path: I decided that if I incorporated more data I could sort the countries with other criteria. The color of the groups would make it possible to track if the ranking is slightly affected or completely altered by the reordering. Having the possibility of reordering the ranking was interesting for me because it allowed me to emphasize other aspects of the data which are very relevant in order to gain insight on the kind of education that the examined students have received. After other feedback rounds I added more data labels (value that is being used to sort the countries) and also I improved the appearance of the buttons used to change between criteria.


###Feedback
I presented the graph in person to some of my friends. They understood the story I was trying to convey and they were able to identify relations in the data, such as how some countries have larger differences between top and bottom scores, how do girls and boys differ in performance, or which countries manage to achieve high scores without leaving too many students behind.

1- "When you explain the graph orally you refer to the countries as the *best scoring ones* and the *worst scoring ones*. It would help to make your point clearer if there was something marking which countries belong to which group".

2- "I understand that the countries are ranked from left to right, the ones at the right being the top performers according to the selected criterion, but it would help me understand the graph more easily if I could read somewhere what is the value that is being used to rank the countries."

3- "Its difficult to know that the buttons are actually buttons and that we are supposed to play with them."


###Resources
*Scott Murray:*

http://alignedleft.com/tutorials/d3/axes]

http://alignedleft.com/tutorials/d3/making-a-bar-chart

*Tooltips:*

http://bl.ocks.org/Caged/6476579

*Mouse events:*

http://bl.ocks.org/WilliamQLiu/76ae20060e19bf42d774

*D3 reference:*

https://github.com/d3/d3/blob/master/API.md