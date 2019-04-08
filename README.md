# Assignment 1

![alt text](https://github.com/suyamag/info474A1/blob/master/Capture.PNG)

The aspect of the data that I am most effectively trying to communicate is the vastly higher amounts of minimum inhibitory concentration(MIC) for Penicilin in Negative Gram Staining bacteria, and the relatively higher amounts of MIC for Streptomycin and Neomycin in the Positive Gram Staining bacteria. This higher level view of the MIC levels is most effective at allowing the reader to notice how MIC changes between the three nominal values.


In order to make the bacteria and antibiotic nominal values stand out the most, I used the x and y **positions** respectively. This is the most **effective** way for the users to distinguish these differences. I then used **color/hue** to distinguish the Gram Stain, which is the second most effective way to distinguish nominal values. In addition to color, the data is also rearranged by position to separate the two Gram Stains. I used **Area** to represent the quantitative interval value MIC. While this method does not show the close nuances of the difference in the exact data, it is able to show a high level view on which values are bigger than others. 


I used a bubble chart to represent all 4 dimensions on this single graph. I found this to be the best way to **express** all of the important features. But because Penicilin had such large outliers, it made a lot of the smaller values harder to see. While the expression of the lower MIC values are lost, I believe that the overall trends revealed by the graph are more important and outweigh this loss.


I used Python Pandas and Matplotlib to transform and plot the data.