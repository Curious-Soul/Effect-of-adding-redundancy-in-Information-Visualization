# Effect-of-adding-redundancy-in-Information-Visualization

**Question:** Does adding a (secondary) redundant visual encoding has any effect on speed of judgement and/or accuracy?	
**Hypothesis:** After representing the main dimensions of data, if we are left with any visual features, then we may consider using them to redundantly encode some of the already encoded data dimensions. This added redundancy can lead to faster, easier and more accurate comprehension of information. 

**Research:**
As importance of data visualizations have spiked to gain quick and compelling insights, it has become critical to evaluate effectiveness of these graphical presentations by testing effects of various additions or alterations to graphical components *(Bateman et al., 2010; Borgo et al., 2012; Skau, Harrison, & Kosara, 2015; Zhu, 2007)*.  However, there is very little research done on finding the efficiency of redundant encoding. Even Edward Tufte states that, “redundant and partially overlapping methods of data representation can yield a sturdy design” *(Tufte,1991)*. 
<br>
<br>
<p align="center">
<img width="800" height="450" src="https://github.com/Curious-Soul/Effect-of-adding-redundancy-in-Information-Visualization/blob/master/PieChart_Comparison.png">
</p>
<br>
 For example, let’s compare the two pie charts above:
 First pie chart has two encodings that represent values by multi-color slices and labels. Now, if we change this by adding a redundant encoding or ordering the  slices by value and color hue like shown in second pie chart, we observe that ordering the pie chart and adding color hue results in main dimensions to be encoded twice. This reduces the errors in misinterpretation and increases the speed and accuracy with which we can decode data. 

Studies have shown to have a redundancy gain in terms of perceptual accuracy and speed of interpretation when color and shape were used together in a scatter plot instead of using either of them alone (Kopala, 1979; Jubis, 1990; Nowell, Schulman, & Hix, 2002). We also found another study *(Russell Chun (2017) Redundant Encoding in Data Visualizations: Assessing Perceptual Accuracy and Speed, Visual Communication Quarterly, 24:3, 135-148)* in which they used four different visual encodings (position, length, area and angle) to introduce redundancy and test their effects on speed and accuracy of graphical perception.
<br/><br/>Steps followed in the study are as follows:
- Each graph type had 5 categories indicating different data values, labeled A, B, C, D, and E, and the participants were tested on their perceptual accuracy in judging proportions. 
- Each redundantly encoded graph pair was added with secondary encoding of varying grey levels.
- Each chart had a simple instruction - “make a quick visual judgment” of what the percentage of one category is to the largest. 
- The results were used to compute the accuracy and average time on task computed from Mechanical Turk for each type of visual encoding and its redundant encoding pair. 
<br>
<p align="center">
<img width="800" height="450" src="https://github.com/Curious-Soul/Effect-of-adding-redundancy-in-Information-Visualization/blob/master/EarlierResearch_1.png">
</p>
<br>
<br>
<p align="center">
<img width="800" height="450" src="https://github.com/Curious-Soul/Effect-of-adding-redundancy-in-Information-Visualization/blob/master/EarlierResearch_2.png">
</p>
<br>

They concluded that addition of value as a redundant encoding (paired with angle, length, position and area) had no positive or negative effect on perceptual accuracy or speed. 

However, the above conclusion does not hold good for all possible combinations of visual encodings. In this experiment, we want to explore the correlation between different pairs of visual variables (like color and shape in case of scatter plot) by considering one variable as main data dimension and other as secondary redundant visual encoding. <br/><br/>By doing so, we aim at finding:
- How redundant encoding affects speed and accuracy of perceptual judgement for these different encoding pairs.
- Is there any association between choice of secondary visual encoding and chart type? 
For instance, a secondary redundant encoding of “shape” is particularly more useful in improving readability of scatter plot compared to other chart types.
