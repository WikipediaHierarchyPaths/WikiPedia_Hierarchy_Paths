# All_Paths
We consider the level of each category, i.e., its shortest path to the root, as an indicator for the specificity of that category. As such and in order to evaluate specificity metrics, we have randomly sampled 240 unique root-to-leaf paths each with a length of 5, which form our test collection. The reason we include these paths is to enable the comparative analysis of several categories that are semantically related to each other and avoid the comparison of semantically dissimilar categories. Given a set of categories, the objective of an effective specificity metric would be to allow for the correct specificity-based ordering of these categories, the correct ordering of which exists in the test collection. It is then possible to evaluate the performance of each specificity metric using rank correlation measures such as  Kendall's Tau to determine the relationship between the actual order of categories observed in the test collection and the list of categories ranked based on the specificity metric. 
