
<center>
<h3> Mathematics of Clustering and Related Problems </h3>
<img src="https://satijalab.org/img/tsne-example.png" width="400">
</center>

**Background:** Suppose we are given a large collection X of points in a high dimensional real vector space V, as well as one or more 
functions d:V x V -> R that give some measure of similarity between points.  Our goal is to partition
the set X into subsets X(i) in such a way that the elements of a given subset are all similar to each other, while
points chosen from different subsets are less similar.  Ideally, we would be able to characterize the sets X(i) in 
some way and thereby reveal structure in the original set X.

The literature is filled with a wide range of techniques for addressing the problem.  Many such are enumerated on 
the clustering methods page in the  [scikit-learn documentation](https://scikit-learn.org/stable/modules/clustering.html),
where a collection of images shows how different approaches to the problem yield different partitions of sets with different structure.

Two additional problems that are closely related to the clustering problem are *dimensionality reduction* and *visualization.*  Dimensionality
reduction takes a high dimensional set and projects it into 2 or 3 dimensions, hopefully preserving some aspects of the orginal data.
Visualization seeks ways to present the dataset graphically in a way that humans can interpret it.    Many clustering methods
involve finding a reduction to, say, 2 dimensions, visualizing the data there somehow, and then using the human eye to recognize clusters.

**Goals:** The goal of this seminar is to explore the problem of rigorously characterizing clusters in data and of finding methods for discovering those clusters whose results can be related to this characterization.  

**Methods:** Initially, members of the seminar will explore the literature in search of existing work related to the seminar goal, and will present what they find to the group.  Over time, I hope we will begin to develop some new ideas in this field.

**Prerequisites:** This is an exploratory project and there are no formal prerequisites beyond  a command of linear algebra,
some mathematical sophistication, and a willingness to participate.

**Time and Place:** Tuesdays at 2 p.m. in Monteith 313.

**Credits:** Image on top from the [Satija Lab](https://satijalab.org).

**References:** See [this list of references](references.md).

**For more information:** Contact Jeremy Teitelbaum (fname.lname@uconn.edu)


