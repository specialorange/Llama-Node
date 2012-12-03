Lama-Node
=========

A way to filter multi node/attribute data

Drawing
-----
[Google Doc](https://docs.google.com/drawings/d/1B95ajItJTAImL2WXISX0fkBLYk3nldea4Vm9eo-VyE4/edit) :

<img src="https://docs.google.com/drawings/pub?id=1B95ajItJTAImL2WXISX0fkBLYk3nldea4Vm9eo-VyE4&amp;w=2597&amp;h=1547">

Purpose
_____
When analyzing and manipulating data, there are often attributes of said data that are looked at in particular.  Shopping online, you un/click these attributes to filter, however these are the poles of the spectrum.  If you want to analyze a range of the spectrum of a specific attribute, something else is required.   Consider a bowl of candy.  It has many types, colors, and flavors, which all could be filtered by checkboxes.  But what about sweetness, how old is the treat, 

Design
-----
Given *n* nodes, there will be a polygon[or the circle] with *n* vertices, and *n* sliders (Circles seem appropriate, but maybe they also include the [< | <= | = | >= | >] symbols as well?).

Ranges
-----
<pre>
  Null <-> Full
   E        F
   0        1
   0	    10
   N	    !N
   0	    100 (%)
</pre>

< | <= | = | >= | >
-----
maybe clicking/right clicking on the element would change between the setting

Images
-----
Hopefully SVG, see attached svg.html; working on and learning...

Helping Documentation
-----
[Three Little Circles](http://mbostock.github.com/d3/tutorial/circle.html)
