# Task Complexity Analysis: A Mobile Application Case Study
These control graphs are used to measure interaction structure on user interfaces and are particularly relevant to the field of human-computer interaction and computational interaction.

## Accessing the Thesis
https://aaltodoc.aalto.fi/handle/123456789/115196

## Abstract

>Interfaces are used to perform various tasks and in HCI particularly a human performs some task with the aid of a computer with the mediation of an interface. Tasks and interactions can be modelled as graphs, where the graph attributes contain information relevant to the understanding of the interaction task. Based on the interaction graph, it is possible to compute numerical task complexity measures that help compare the complexities of different tasks. However, determining the nature of tasks with manual evaluation is labor-intensive and does not work well with large-scale problems such as algorithmic design or evaluation of large datasets. In this work, we have shown that it is possible to algorithmically infer tasks structures from user interfaces and compute task complexity measures for the task structures represented by graphs. More specifically, the graphs contain descriptions of the components and the interaction modes associated with them, such as a tap. The graphs have been generated from Enrico dataset view hierarchies. The accuracy of the generated graphs is 53.5 % (90 % CI, 15 % ME). Majority of the errors are caused by issues in the underlying dataset. The computed task complexity measures include Wood’s task complexity and Halstead’s E measure. The task complexity measures behave in a fundamentally different way, and their applicability requires further validation. The results demonstrate that it is possible to computationally model and understand tasks performed by humans on interfaces based only on the interface structure. The ability to infer interface task structure as a graph and an adjacency matrix adds a novel perspective for analyzing and modeling user interfaces.

## Getting Started With the Code
To get started please refer to main.ipynb file as this project was done using Jupyter.

In order to browse examples you can access a particular Rico ID screenshot or hierarchy under the respective folder names.
The corresponding graph can be found under the graphs folder. The up-to-date plots of the complexity computation summaries are available under the results folder. 

Analytics.csv file contains the computed results for all of the complexity graphs.

## Brief Background
This code was generated as part of my Master's thesis research project, where the purpose was to generate task complexity control graphs for Enrico mobile interfaces in a large scale setting. 

## References
Thesis reference <To be uploaded>

For background on the dataset please see
```
L. A. Leiva, A. Hota, A. Oulasvirta. 
Enrico: A High-quality Dataset for Topic Modeling of Mobile UI Designs. 
Proc. MobileHCI Adjunct, 2020.
```
and
```
Deka, Biplab, et al. Rico: A mobile app dataset for building data-driven design applications. 
Proceedings of the 30th Annual ACM Symposium on User Interface Software and Technology, 2017.
```
