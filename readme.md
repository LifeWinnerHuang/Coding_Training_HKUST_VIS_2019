# HKUST VisLab Coding Training 
### by Renfei Huang

This is a training for the coding skills in HKUST VisLab. 
Please tolerant some not so well written/organized code segments, as they are not fully polished. 
Here are the results of each level. 

## Level 1
Level 1 covers lots of basic knowledge of D3.js, such as axis, scales, and shapes (rectangles). 
All the 4 tasks are finished in the following figures: 

- The high temperature with tooltips shown.
![Level1_1](figures/Level1_1.png)

- The low temperature with tooltips shown.
![Level1_2](figures/Level1_2.png)

## Level 2
Level 2 is slightly more complex, with line charts added. 
Line charts require knowledge of using paths and properly set the positions of the charts and scales, choosing the proper colors for lines, etc. 

- The high temperature with tooltips shown.
![Level2_1](figures/Level2_1.png)

- The low temperature with tooltips shown.
![Level2_2](figures/Level2_2.png)


## Level 3
Level 3 is both harder and eaiser, it is easy because a lot of resources can be found online that are similar. It is hard because the data structure is more complicated than Level 1 and 2. This requires some advanced use of D3.js. 

This code should be run with a simple server with command within the folder Level_3. 

```
python -m http.server 8000
```

and open up localhost:8000 we can see the result. 
In the node-link diagram, the number of coauthor papers is encoded by the radii of the circle and the width of the links. 
In the matrix view, the number of coauthor papers is encoded by the saturability of color blue. 

The results of the node-link diagram along side of the matrix view. 

- Without highlighting: 
![Level3_1](figures/Level3_1.png)
- With highliting of Prof. Qu Huamin:
![Level3_2](figures/Level3_2.png)
- With highliting of Prof. Qu and reorder the matrix by full name of professors:
![Level3_3](figures/Level3_3.png)


## Level 4 
For level 4 I choosed the challenge of Spotify's Worldwide Daily Song Ranking. 

### Task 1 
The the top 10 tracks in the global throughout year 2017 with their total stream counts. 
![Level4_1](figures/Level4_1.png)


### Task 2

### Task 3

### Task 4






