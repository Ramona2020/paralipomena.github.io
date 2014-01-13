---
layout: post
title:  "Introduction to DH and to XML: Notes for 1/13/14"
author: Dave
date:   2014-1-13 0	13:37:00 UTC
categories: blog
---
Dear Students,

Below is a very rough sketch of what we will cover in class today. This is provided just for our reference, do not treat it as anything other than a rought outline.

##General Schedule for 1/13/14
* Personal Introductions
* Discussion of Syllabus
	* [Course Website](http://paralipomena.com/)
	* [Blog](http://paralipomena.com/blog/) 
	* [Privacy Policy](http://paralipomena.com/blog/2014/01/12/privacy-and-ip-policy.html) 
* What is/are DH?
* What is a text?
* Break
* Introduction to XML
* Introduction to TEI
* Projects using TEI

#Introduction to XML Notes

Notes Based on Kevin Hawkins, ["Introduction to XML for Text"](http://www.ultraslavonic.info/intro-to-xml/) and David J. Birnbaum, ["What is XML and why should humanities scholars care?"](http://clover.slavic.pitt.edu/humcomp/what-is-xml.php)

* XML ("Extensible Markup Language") Cf:
	* SGML ("Standard Generalized Markup Language")
	* HTML (Hypertext Markup Language)
	
Definitions:

* Tags or Elements
	* Semantic rather than rendering style (is there a distinction?) 
	* Open and Close
	* Nest or Child Nodes
	* Document Tree

* Content (Data and Metadata)
* Attributes and Values

* Document Tree
	* heirarchy 
	* root, parent, child, sibling, ancestor, and descendent

* Declaration
	* Header
	* Namespace
	
* Schemas
	* DTD (Document Type Definition)
	* Well Formed 
	* Valid
	
* Escape Characters
	* `<`
	* `&`
	* `<!---`

* XML Standards
	* XSLT
		* "eXtensible Style Sheet Language Transformations, a programming language used to transform XML to other forms (other XML, HTML [web pages], plain text, etc.). The term style sheet is somewhat misleading; XSLT can be used to style an XML document, but it can also be used to create entirely new documents by transforming existing ones in almost unlimited ways."
	* XQuery
		* "A language used to query XML databases."
	* XPath
		* "A formal method of navigating the XML hierarchy, used by XSLT and XQuery. For example, if you want to generate a table of contents based on chapter titles, you use XPath to find (navigate to) all the chapter titles in your document and XSLT to generate an output document that contains the newly constructed table of contents."
		
#TEI: Text Encoding Initiative

* Guidelines (not a Schema)

Resources: 

* [TEI Guidelines](http://www.tei-c.org/index.xml)
	* [Appendix C Elements](http://www.tei-c.org/release/doc/tei-p5-doc/en/html/REF-ELEMENTS.html)
	* [Appendix D Attributes](http://www.tei-c.org/release/doc/tei-p5-doc/en/html/REF-ATTS.html)
* [TEI @ Oxford Teaching Pages](http://tei.oucs.ox.ac.uk/Talks/2013-05-23-BL/)


* TEI
	* teiHeader
	* text
		* div
			* p
			* choice
				* sic
				* corr
			* ref target=" "
			* Names Dates People Places Events
			

Recommended Exercises:

* TEI by Example, Modules 0 to 3.
* Required Response Paper: Identify and review an XML based digital humanities project relevant to your research or vocational interests.


				