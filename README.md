```diff
- I feel like I forgot to mention this about cohesion and separation: 
- Lower values for cohesion and higher values for separation are better, 
- and they do not have a range. According to the current formulas, the minimum value is 0, 
- but there is no maximum value. You may scale the cluster cohesion/separation values
- by diving them by the maximum cohesion/separation value, but this isn't required.
```

### Uploaded exercise 9 https://github.com/tchanda90/data-mining/blob/master/notebooks/finding_optimal_k.ipynb

### Uploaded exercise 8. For the calculation of cohesion and separation, follow the steps shown in the notebook. Please do not normalize the distances. Follow the exact formulae and steps shown in the notebook https://github.com/tchanda90/data-mining/blob/master/notebooks/cluster_validation.ipynb The values are confirmed correct.

### IMPORTANT: For the computation of the Silhouette coefficient in task 9.1, please calculate b as average distance to the points of the nearest cluster (just like in the book) and not as average distance to the points of all other clusters as shown in the slides. This is confirmed to be correct. https://github.com/tchanda90/data-mining/blob/master/notebooks/silhouette_score.ipynb ALSO, please calculate the overall clustering silhouette coefficient as average over all point silhouette values, as shown here in the notebook. In the slides, the overall clustering silhouette coefficient is calculated as average cluster silhouette coefficient which doesn't take different cluster sizes into account.

### If you have any doubts regarding the above, feel free to email me tirtha.chanda@ovgu.de



