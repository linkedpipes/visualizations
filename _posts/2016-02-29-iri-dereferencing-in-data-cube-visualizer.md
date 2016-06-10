---
layout: post
icon: whatshot
title: IRI dereferencing in Data Cube visualizer
---

When you want to visualize a data cube and only provide the DSD and observations, we will dereference the IRIs of your dimension values to see if we can get labels for them.
This means that you don't have to provide the used code lists as long as their items are dereferenceable.
Try it out! Use these two URLs in the "URL containing RDF" field:
[Observations](http://visualization.linkedpipes.com/example/datacube.ttl), 
[DSD](http://visualization.linkedpipes.com/example/dsd.ttl).
If you examine the files, you will see that the labels for days, age categories and sexes are not there.
Nevertheless, you will see them in the visualization, because we get them by dereferencing their IRIs.