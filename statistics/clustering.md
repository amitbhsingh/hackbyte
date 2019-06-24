Well, we've seen some examples of supervised learning,
specifically regression and classification.
But what about unsupervised learning?
Now unsupervised learning techniques,
you don't have a known label with which to train the model.
But you can still use an algorithm that finds
similarities in data observations in order to group
them into clusters.
Suppose for
example our health clinic has a website that contains links to
articles and medical and healthy lifestyle publications.
Now I might want to automatically group similar
articles together.
Or maybe I wanna segment our study participants, and
we can categorize them based on similar characteristics.
There are a number of ways we can create a clustering model.
And we're gonna look at one of the most popular clustering
techniques, something called k-means clustering.
Now the key to understanding k-means is to remember that our
data consists of rows of data, and
each row has multiple features.
Now if we assume that each feature is a numeric value,
then we can plot them as coordinates.
Now here,
we're plotting two features on a two dimensional grid.
But in reality,
multiple features would be plotted in n-dimensional space.
We then decide how many clusters we want to create,
which we call k.
And we plot k points at random locations
that represent the center points of our clusters.
In this case, k is three, so we're creating three clusters.
Next, we identify which of the three centroids each point is
closest to, and assign the points to clusters accordingly.
Then we move each centroid to the true center of the points
and its cluster.
And reallocate the points in the cluster based on their
nearest centroid.
And we just repeat that process until we have nicely separated
clusters.
So what do I mean by nicely separated?
Well, we want a set of clusters that separate data by
the greatest extent possible.
To measure this, we can compare the average distance between
the cluster centers.
And the average distance between the points in the cluster and
their centers.
Clusters that maximize this ratio
have the greatest separation.
We can also use the ratio of the average distance between
clusters, and the maximum distance between the points and
the centroid of the cluster.
Now another way we could evaluate the results of
a clustering algorithm is to use a method called
principal component analysis, or PCA.
In which we decompose the points in a cluster into directions.
We represent the first two components of the PCA
decomposition as an ellipse.
The first principal component is along the direction of
the maximum variance or major axis of the ellipse.
And the second PCA is along the minor axis of the ellipse.
A cluster that is perfectly separate from the first cluster
shows up as an ellipse, with the major axis of the ellipse
perpendicular to the ellipse of the first cluster.
Every second cluster is reasonably well, but
not perfectly separated.
Then it will have a major axis that is not quite perpendicular
to the first ellipse.
And if the second cluster is quite
poorly separated from the first,
the major axis of both ellipses will be nearly colinear.
And the ellipse may be more like a circle,
because the second cluster is less well defined.

