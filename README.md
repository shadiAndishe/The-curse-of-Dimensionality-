# The-curse-of-Dimensionality
![27770527-soccer-football-field-stadium-grass-line-ball-background-texture-light-shadow-on-the-grass](https://user-images.githubusercontent.com/45369296/113853593-1e112880-979e-11eb-8f85-47a801f82cd5.jpg)

## we will have lots of problem with high Dimensionality!
Imagine dropping a penny on a straight line the length of the football field. How long would it take you to find it.
Now, imagine dropping that penny on a football field. How long would it take you to find it?

Now, imagine dropping that penny within a three dimensional space the size of a football field. How long would it take you to find it.
The difficulty of searching through the space gets a *lot* harder as you have more dimensions. You might not realize this intuitively when it's just stated in mathematical formulas, since they all have the same "width". That's the curse of dimensionality. It gets to have a name because it is unintuitive, useful, and yet simple.

# AS much as the dimensionality increase, the need of data to generalize accurately the problem exponentially increase!
## see my provieded code to understand better the problem in Python Notebook.
![download](https://user-images.githubusercontent.com/45369296/113876593-2bd3a780-97b8-11eb-80b3-99f7841bfc0c.png)

## lets Analyse the plots!
One the X axis the value of the distance calculated and one the Y axis we have how many data points that have this value of the distance!
## so what?
ok , in ths plots we can see in all distributions we have a Max which most of the distances between 2 points are distributed around that , as far as we go in higher Dimension , this range is going to thiner and thiner , means how the notion of distance is going to be usekess to seprate data from eaxh other based on distance(similarity or disSimilarity)


When we have too many features, observations become harder to cluster — believe it or not, too many dimensions causes every observation in your dataset to appear equidistant from all the others. And because clustering uses a distance measure such as Euclidean distance to quantify the similarity between observations, this is a big problem. If the distances are all approximately equal, then all the observations appear equally alike (as well as equally different), and no meaningful clusters can be formed.
