---
layout: post
title:  "Learning XPath"
author: Cliff
date:   2014-1-28 17:10:14 UTC
categories: blog
---

As you know, we will be discussing [XPath](http://www.w3.org/TR/xpath-30/) during our next seminar. XPath is a language for exploring XML documents. XQuery and XSLT both make use of XPath. You'll need a good understanding of XPath to make effective use of XQuery.

Here's the input document we'll be using as a reference at our next meeting.

{{ gist 8671757 }}

As you see, it's basically a bare bones TEI document. So how can XPath help us to explore the nodes and atomic values in this document? Let's try a few examples:

* Write an expression to select the teiHeader.
* Write an expression to select the title of this TEI document.
* Write an expression to select all p elements in the document.
* Write an expression to select all p elements that have a body element as an ancestor.
* Write an expression to select the third p element that is a child of the body element.
* Write an expression to select only the text node of the same p element.
* Write an expression to select only the first and second p child elements of the body element.
* Write an expression to select the value of the when attribute of the date element.
* Write an expression to select the ancestor of any p element with an n attribute.
* Write an expression to select only those text nodes that are children of elements with n attributes.

We'll go through all these exercises in class. We'll also learn how to use oXygen to assist with writing and testing our XPath expressions.

See you next week!

