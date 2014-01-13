---
layout: post
title:  "What is Text?"
author: Cliff
date:   2014-1-13 05:08:00 UTC
categories: blog
---

###What is the right model for digital text?

In a [paper from 1990](http://dl.acm.org/citation.cfm?doid=264842.264843), Steven DeRose and his co-authors argued that text is essentially "an 'ordered hierarchy of content objects' or 'OHCO'" (p. 4). They differentiated this essential structure from the accidental or "superficial and transient" appearance of text on a page (p. 3). When marking up a text in SGML, for example, the OHCO model requires us to abstract away from the presentation of that text in order to model its underlying structure. 

DeRose *et. al.* distinguished the OHCO approach from alternative models: "text as bitmap" (p. 6); "text as a stream of characters" (p. 7); "text as characters and formatting instructions" (p. 7);  "text as page layout" (p. 8); and "text as a stream (not hierarchy) of content objects" (p. 9). Though written in 1990, variants of all these textual models still exist in contemporary digital library projects.

###Discerning the models at work

When studying a digital library project, it's helpful to ask about the dominant model of textual representation. 

Some projects rely primarily on binary images. While these projects may not display bitmaps *strictly speaking*, they rely on graphical representations in JPEG or PNG formats. A good example of a modern digital library project of this sort is [The Digital Library of Abraham Kuyper](http:kuyper.ptsem.edu). A large portion of this digital library is archival. See, for example, this [document attesting to his conversion in 1848](http://kuyper.ptsem.edu/id/Kuyper1-2/dmd003). How does this use of binary images serve or detract from the goals of this digital library? What would be lost with a TEI only version?

Other projects store and display texts with different OHCOs. For example, texts are marked up as TEI in [The Princeton Lectures on Youth, Church, and Culture](http://www.ptsem.edu/lectures/). However, these texts are rendered to users as HTML. This is a common pattern in many digital library projects. While most browsers can render XML formats to users with appropriate stylesheets, it's often easier to rely on the XML format for search and then to convert the XML to HTML for display. As a consequence, users may not know that TEI has been used to encode the underlying digital text. Do you see any disadvantages to this approach?

###Encoding multiple models?

James Cummings raises the question in [The Text Encoding Initiative and the Study of Literature](http://nora.lis.uiuc.edu:3030/companion/view?docId=blackwell/9781405148641/9781405148641.xml&chunk.id=ss1-6-6&toc.depth=1&toc.id=ss1-6-6&brand=9781405148641_brand) whether the logical structure of a document should alway takes precedence over its physical layout. Are there not cases in which a physical structure is normative? 

Our citation standards provide a good example. Typically, these standards require us to cite the page from which we are quoting. While the TEI provides a method for encoding information about physical page breaks, the milestone elements used for this purpose are distinct from the OHCO model of the document; they represent an alternative hierarchy based on a different model of the text. See [this DjVu format from the Internet Archive](https://ia600302.us.archive.org/30/items/detheologievandr00eerd/detheologievandr00eerd_djvu.xml) as an example of what this alternative model might look like; which textual model does this correspond to?

As Cummings indicates, "There has been a great deal of discussion recently among markup experts concerning both the problems of overlapping hierarchies and solutions for them in XML and other possible options." No standard solution exists, perhaps because XML requires privileging a single hierarchy above all others. 

###Questions

* Which model of text do you use when producing scholarly documents?
* Which model of text do you prefer when reading digital texts? Do you experience the tension between models in your own scholarly work?
* Where do PDF documents fit into this taxonomy of textual models?