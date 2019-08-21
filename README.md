# Seminar: Mathematics of Clustering and Related Problems

**Background:** Suppose we are given a large collection $X$ of points in a high dimensional real vector space $V$, as well as one or more 
functions $\rho :V\times V\to {\bf R}$ that give some measure of similarity between points.  Our goal is to partition
the set $X$ into subsets $X_i$ in such a way that the elements of a given subset are all similar to each other, while
points chosen from different subsets are less similar.  Ideally, we would be able to characterize the sets $X_i$ in 
some way and thereby reveal structure in the original set $X$.

The literature is filled with a wide range of techniques for addressing the problem.  Many such are enumerated on 
the clustering methods page in the  [scikit-learn documentation](https://scikit-learn.org/stable/modules/clustering.html),
where a collection of images shows how different approaches to the problem yield different partitions of sets with different structure.

Two additional problems that are closely related to the clustering problem are *dimensionality reduction* and *visualization.*  Dimensionality
reduction takes a high dimensional set and projects it into $2$ or $3$ dimensions, hopefully preserving some aspects of the orginal data.
Visualization seeks ways to present the dataset graphically in a way that humans can interpret it.    Many clustering methods
involve finding a reduction to, say, $2$ dimensions, visualizing the data there somehow, and then using the human eye to recognize clusters.

**Goals:** The goal of this seminar is to explore the problem of rigorously characterizing clusters in data and of finding methods for discovering those
clusters whose results can be characterized in terms of such a characterization.  

**Methods:** Initially, members of the seminar will explore the literature in search of existing work related to the seminar goal, and will present
what they find to the group.  Over time, I hope we will begin to develop some new ideas in this field.

**Prerequisites:** This is an exploratory project and there are no formal prerequisites beyond  a command of linear algebra,
some mathematical sophistication, and a willingness to participate.

**Time and Place:** To be determined.  If you are interested in participating, fill out the form below and I'll get back to you soon.

<form name="seminar-survey" method="POST" action="https://formspree.io/jeremy.teitelbaum@uconn.edu">
<fieldset id="seminar-survey-inputs">
<label for="full-name">Full Name</label>
<input type="text" name="name" id="full-name" placeholder="First and Last">
<label for="email-address">Email Address</label>
<input type="email" name="_replyto" id="email-address" placeholder="your_name@uconn.edu" required="" id="email-address">

<fieldset id="person-type">
<label for="ptype">UConn position</label>
<select name="ptype" id="type" required="">
  <option value="Choose" selected="" disabled="">Choose</option>
  <option value="Faculty">Faculty</option>
  <option value="Grad">Grad Student</option>
  <option value="Undergrad">Undergrad</option>
  <option value="Other">Other</option>
  </select>
</fieldset>
<label for="background">What is your area of study?</label>
<textarea rows="3" name="background" id="background" placeholder="Field of research, major, advisor"></textarea>
<input type="hidden" name="_subject" id="email-subject" value="Seminar Responses">
</fieldset>
<input type="submit" value="Submit">
</form>






