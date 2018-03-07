# NLP_MBTA
## NPL for assistant resarch for Shoshana Vasserman about MBTA

**Task:**
Form string descritions objects offered by sellers:
- [X] We need to make a "smart" *description* of these objects.
- [X] Then, we use this description to say if two objects are "*close*" of not, i.e.: make a distance function
- [X] Finally, we use a clustering alogorithm to make *sets* of objets that are "close".

**Note:** All task are made in the "NLP_main.ipynb" notebook, others files are just used for getting data from APIs, formating data, and make a few primary analysis.

**Note: (bis)** The data file isn't in this respository, for data-property reasons.

## The description of the objects is a dictionary:
![Image of an example of analysis](doc/analysis_example.png)
RED: description of the object<br>
ORANGE: no. of the line in the datafile of the object<br>
Dark BLUE: keys of the dictionary decribing the object<br>
Light BLUE: coresponding values of the dictionary decribing the object<br>
![Image of examples of analysis](doc/analysis_examples.png)

## The distance function:
![Image of an example of use of the distance function](doc/distance_function_example.png)
RED: description of the objects<br>
ORANGE: no. of the lines in the datafile of the objects<br>
BLUE: distance returned by the function in this case<br>
![Image of examples of uses of the distance function](doc/distance_function_examples.png)

## The clustering results:
![Image of a clustering plot](doc/clustering_plot_example.png)

