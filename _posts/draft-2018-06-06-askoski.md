---
title:  "AskOski"
layout: post
date:   2018-06-06
projects: true
category: project
description: "UC Berkeley course recommendation system.  Explore personalized course suggestions based on historic enrollments."
hidden: true # don't count this post in blog pagination

---

<!-- (More info <a href="{% post_url 2018-06-06-askoski %}" target="_blank">here</a>) -->
<figure>
<a href="https://askoski.berkeley.edu" target="_blank">
	<img src="/assets/images/featured_images/askoski.png" alt="AskOski Logo" style="width:200px;
    height: auto; display: block; margin: 0 auto;">
  	<figcaption> <h4> Main site </h4> </figcaption>
</a>
</figure>


### Search Feature

- <a href="{{ site.url }}/assets/files/askoski_brochure.pdf" target="_blank">System Background</a>
- I incorporated the <a href="https://askoski.berkeley.edu/search" target="_blank">enhanced course catalog / search</a> into the site to improve the course discovery process / browsing experience. 
- What differentiates this search feature is that a query will not only be matched against default catalog information, but also to additional inferred topics for each course.  These inferred keywords are produced by a machine learning model tagging course embeddings with semantics, i.e. generalizing a class' description based on the descriptions of similar classes. 

- <a href="https://link.springer.com/chapter/10.1007%2F978-3-030-29736-7_36" target="_blank">Full paper</a>, <a href="{{site.url}}/assets/files/ECTEL-paper.pdf" target="_blank">Full paper PDF</a>
- <a href="https://github.com/mdong127/ICS-research" target="_blank">Repository</a> containing code for model and training scripts
<!-- - Tools used -->
<!-- - What makes this course catalog “intelligent” is that a search query will not only be matched against course titles and descriptions, but also to additional “inferred keywords” for each course.  The inferred keywords are a machine learning model’s prediction as to what a class is about based on its true description and its mathematical representation learned from student behavior, intending to capture a semantic portrayal of courses beyond university catalog descriptions.  -->
<!-- These predicted keywords are a generalized description that contains words pulled from other course descriptions by way of a classification model mapping from a behaviorally informed course embedding space to a literal course description semantic space.   -->
<!-- - [Poster]({{site.url}}/assets/files/EDM-poster.pdf), [Short paper pdf]({{site.url}}/assets/files/EDM-paper.pdf) -->
<!-- More details [here]({{site.url}}/assets/files/research-poster-final.pdf). --> 
