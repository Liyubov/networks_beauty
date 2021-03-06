
# networks basic analysis tools 
this is repository for basic analysis tools of networks.
for galleries of some network visualisations please visit https://imaginary.org/gallery/networks-and-the-world 

in folder *network_code* we do basic network analysis.
here we consider networks embedded in space (spatial and in particular geometric networks),  see notebook *geometric graphs analysis.ipynb*,
then we consider networks non-embedded in space, which can be weighted (by weights assigned to links or nodes) 
or non-weighted (when adjacency matrix has only 0,1 entries), see e.g. notebook *standard_network_analysis_vizzz.ipynb* with standard network analysis

some of networks visualisations are collected at Imaginary.org open mathematics community, my gallery there https://imaginary.org/gallery/networks-and-the-world

# code 
for more detailed python resources see https://github.com/Big-data-course-CRI/materials_big_data_cri_2019/tree/master/resources%20Python 
in this repository we study several aspects:

## 1. network measures for analysis of the degree distribution 
degree distribution is one of the most basic linear characteristics of any network and we can always start with it

## 2. network measures for analysis of the shortest paths distributions 
in order to analyze networks of some types (such as transportational networks) we often need 
the characterisation of distances, such as Euclidean distance in R^D, for this we can use shortest paths between two nodes 
v_i, v_j: |v_i, v_j|

## 3. spectral analysis of networks 
(in progress)

## 4. visualisation of networks  
there are many ways to vizualize a network, depending on its type. we consider here spatial and non-spatial networks.
we show the visualisation of percolated random graph 
with edge color corresponding to the time-step when the edge appeared, see notebook *network percolation visualisation.ipynb*
