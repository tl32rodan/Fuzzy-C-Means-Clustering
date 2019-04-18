# Fuzzy-C-Means-Clustering
An implementation of FCM~

## Useage
Open fuzzy_c_means.ipynb with jupyter notebook.

numpy,pandas,sklearn are required.

## Introductions

Generalized version of k-means clustering with fuzzy ytheory , I also wrote a k-means program.

All the settings are similar to it, so check it out if you need settings.

https://github.com/sedEZ/K-means-Clustering

Here, I will simply describe how I do it.

1.Initialize C clusters randomly
 
2.Update membership value table of all data
    
3.Update centroid via the membership value table

4.If the object function value converges ( < epsilon : defult = 1e-6), Do 2.

If you want to have a close look to FCM ,read the article below or just ask. :)

## Reference

https://blog.csdn.net/zjsghww/article/details/50922168
