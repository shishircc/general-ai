# Spatial Concepts Experiment 
Extracting Spatial Concepts from pair of two image(s). Automatic concepts based on 
1. Basic concept of spatial continuity in horizontal, vertical or any other plane 
1. Color similarity/continuity in spatial neighbourhood  
1. Depth similarity/continuity in spatial neighbourhood
1. Connectedness similarity/continuity in spatial neighbourhood 

The model need not start from empty page. It could have built in concept of spatial continuity that it uses in learning process. 

The model should also not be supervised learning. It should be able to use above concepts to extract "things" in the image, without initially knowing what those things are. 

## Acceptance Criteria 

The models should be able to answer basic questions then like 
1. What is the color of thing at pixel x,y ? 
2. Which "thing(s)" does it belong to, which should give list of things that it is connected to hierarchically ? 
3. What's the approximate distance of this pixel from camera ?

## Basic concept of spatial continuity in horizontal, vertical or any other plane 

How can we do this ? Does OpenCV cover some of these ? Would it be generic enough ? 