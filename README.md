# matplotlib-challenge
A data analysis exercise from experimental data on tumor repression drug

This is a great data to play with. However, some very important analysis is missing from the list of assignments. I added a sample analysis for the rate of shrinkage of a drug. A more elaborate analysis is necessary if one would like to make sense of the data. Here are a few observations based on the figures:

Figure 1,2: The number of available mice for each drug is roughly in between 150-250. Without looking at the standard deviation of a certain measure, the number of mice usually doesn't give much insight.

Figure 3,4: This is an important check for animal testing. The number of male and female is roughly equal in total, meaning that the scientist who took the data gives equal-distribution of male/female to remove the bias on sex as much as possible. A better analysis would be to check the male/female ratio for each drug regimen.

Figure 5: The boxplot of the final tumor volume shows that out of four of the chosen drug regimen, Capomulin and Ramicane shows qualitatively better tumor shrinkage then Infubinol and Ceftamin.

Figure 7,8: It wasn't explicit, so I put in the average final tumor volume. From an initial tumor volume, the data shows that as the mice is lighter, the effect of the drug Capomulin is greater. This is most likely due to equal amount of drug delivered to each mouse. Normally, as the mouse gets heavier, the amount of drug delivered must be larger. If the amount of drug delivered is the same for each case, this figure implicitly shows when the drug becomes effective in shrinking the tumor. For the amount of drug delivered, we see the effect for mice weighing less than 25g.