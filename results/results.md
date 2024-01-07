I'll start with some basic descriptions of our data: 11 taste testers x 11 fries = 121 observations (a perfect square!) with no missing values (good job!). The fries came from 5 different brands, but were mostly meijer and ore-ida. The definition of "fry" included mashed potato product, tater tots, regular cut, thin cut, curly cut, steak cut, and waffle cut. 

One heatmap of the scores each person gave to each fry. The "yummy score" represents each person's scores min-max normalized to a [0,1] scale, where 0 is your least favorite and 1 is your favorite. My naive hope is that this makes things more comparable across people, since each of you each interpreted the original [1,100] scale differently. For example, Brandon Webster only gave values inbetween 65 and 76, while Anna made use of the entire range (15 - 97). You can see that most people ranked the Arby's curly fries as their favorite, but you can also see some outliers (you know who you are).

boxplot looks at which fry is most divisive. I personally define "divisiveness" as the interquartile range of min-maxed normalized fry scores (i.e. bigger boxes in the boxplot = more divisive). By this definition, the most divisive fry was the crinkle cut fry, followed by the steak fries. 

barplot shows how consistent each of you were at rating french fries. To do this, I looked at the first and second time you tried Meijer Regular Cut Fries and calculated the percent difference in your two scores. A tall bar means you gave a very different score the second time you tasted this fry compared to the first. I interpret this as either you weren't reliable, or you picked up on subtle differences in how I cooked the two batches of fries.

second heatmap shows how each person's score correlates with the amount of sodium, fat, and calories in each fry. You can see that, especially for Brandon Beal and Riley, scores tended to strongly correlate with the amount of sodium in the fries. The sodium, fat, and calorie levels combined explain 32.81 % of the variation in your observations. Sodium seems to have the strongest impact on your scores overall, but it's hard to say this for sure because sodium and fat are strongly correlated.

My takeaway: I basically tested everyone's ability to taste salt and they did pretty okay