---
#
# This area, between --- markers, is called the YAML header.
# It tells Jekyll about the page or post
#
title:      "Getting started"       # Make a title for the post
subtitle:   "A new storyteller"     # also a subtitle
date:       2020-11-19              # Optional, but make it match the filename date
layout:     post                    # For posts, this should always be "post"
active: journal                     # This is the active menu item. Normally "journal"
# published: no                       # Comment out this line to publish the post
# Images: in the YAML header, we use a relative path:
feature-img: "img/journal/Cast-Aside-Web.jpg" # An image to feature on the "journals" page
header-img: "img/journal/Cast-Aside-Web.jpg"  # This one is the header image
---

I'm getting used to a new kind of website for some of my photography. My husband tells me it's not the usual *Squarepress* kind of site used by many, and I quite like the look of this one. I have to learn some new tricks like **bold** text or *italics*.

### Headings
These depend on how many octothorpes you start the line with: one, for level 1, two, for level 2, and so on. This paragraph has a level 3 heading.

I need to remember to separate paragraphs with a blank line. Other than that, it looks quite easy. I can even embed another picture if I want to:

![]({{site.baseurl}}/img/journal/Cast-Aside-Web.jpg)
*Cast aside*

<!-- Notice in the body of the post, we have to add on "{{site.baseurl}}/" for the image. -->

<!-- 
This is an HTML comment that will be sent to the browser but not normally displayed to the user. Everything bewteen the delimiters is a comment. Handy for your own notes, but remember whatever you put here can be seen in the browser by "view source".
-->
