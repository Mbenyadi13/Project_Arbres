# Trees of Grenoble
<span style="font-size:12px">
    Author: <span style="color:grey">Julien DUBOIS <br /></span>
    Status: <span style="color:grey">Completed<br /></span>
    Last Updated: <span style="color:grey">23/07/2025 <br /></span>
</span>
<br />
This is a small data science project done during my data science training at the Campus Numérique in the Alps. It aims at exploring open data related to trees within the French city of Grenoble. The data set is available <a href="https://data.metropolegrenoble.fr/visualisation/export/?id=arbres-grenoble&disjunctive.sous_categorie_desc&disjunctive.espece"> here</a>.

## <span style="color:grey">Iteration 1: Preliminary exploration</span>

The first iteration of the project consists of a naive approach to the problem using basic Python. The data set is explored using mostly built-in functions, and is essentially a pleminiary exploration of the data.

## <span style="color:grey">Iteration 2: Analysis of the diversity of trees</span>

In the second iteration, we investigate how the diversity of trees within the city evolved over time conclude as to whether diversity goals set by the city are met. This part is still done using basic Python, and the data is manipulated as a multi-dimensional list.

## <span style="color:grey">Iteration 3: Introduction to Pandas</span>

After the first two iterations, we go over the same tasks again but using the Pandas library this time, highlighting how efficient data frames are when it comes to exploring and analysing data in Python.

## <span style="color:grey">Iteration 4: Geographical distribution of trees</span>

Finally, the last iteration of the project aims to study how trees are spatially distributed within the city. We use the Folium and Geopy libraries. In the part of the project, we investigate more challenging questions that require a bit more technical solutions to solve, such as infering the average distance between all trees, finding the most and least isolated trees. Given the sample size (~30 000 trees), these tasks happen to be a bit too computionnally heavy to solve in a straightforward manner by computing a matrix of distances. As such, we solve this issue by using the k-d tree method.