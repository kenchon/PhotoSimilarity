# PhotoSimilarity
Compute photos similarity based on photo tags.

Image tags can be index of what the piture is about. It is natural to think that two pitures which share more tags are more similar. 
From this idea, we can compute similarity of two images based on their tags.

Jaccard distance is used to compute similarity of two sets:

<img src="https://latex.codecogs.com/gif.latex?sim_J=\frac{|A{\cap}B|}{|A{\cup}B|}"/>

where A, B are sets whose i th elements correspond to i th tag. 

We can extend this similarity as below:

<img src="https://latex.codecogs.com/gif.latex?sim_w=\frac{\sum_i^Nw_i(a_i{\land}b_i)}{\sum_i^Nw_i(a_i{\lor}b_i)}"/>

