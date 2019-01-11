---
layout: post
title: "Flag Project - Final Submission"
date: 2018-12-21
---

## Flag of Tunisian by Mason McKnight

## Describe your program

I am making the Tunisia flag and I am execpting at least a 3. I think I shold at least get a three because my flag came out exact how it was suppose to but my explaination of the project probably isn't going to be the best.

## Current output

* * *
![Flag of Tunisia](\_images\download.png)
* * *

## Describe your process.

The big problem I ran into when I was working on the flag was the rotating function and how it was working fine by itself but wasn't working when I was use the function with the rest of the program. It took messing around with the program to figure out that the positioning of a function can determine whether or not it will be used in the entire program.


## Explain your code.

* * *

```
size=100
width=size * 3
height=size * 2
RR= rectangle(width, height, "solid", "red")
WC= circle(width / 5, "solid", "white")
WC2= circle(width / 8.5, "solid", "white")
RC= circle(height / 4.5, "solid", "red")
RS= star(width / 9, "solid", "red")
My program is technically only 13 lines so this is more than half of it.
```

* * *

-   Explain the code you posted by telling us about each argument.
-   Then tell us how your code section fits into the whole.
 
Width and height makes it easier to make changes in the program when it comes to the size of an images. This aurgument changes the size of the indivilual shapes by making them scalable by make necessary to only change two numders and when you changes the two numbers it changes the size of the entire image. This section of code is all of the images I have use in the program to make my finished flag of Tunisia.


## Program code

```
include image
size=100
width=size * 3
height=size * 2
RR= rectangle(width, height, "solid", "red")
WC= circle(width / 5, "solid", "white")
WC2= circle(width / 8.5, "solid", "white")
RC= circle(height / 4.5, "solid", "red")
RS= star(width / 9, "solid", "red")
RR-WC=place-image(WC, width / 2, height / 2, RR)
RC-WC2=place-image(WC2, width / 5.4, height / 4.5, RC)
RR-WC-RC-WC2=place-image(RC-WC2, width / 2, height / 2, RR-WC)
RSR= rotate(310, RS)
Tunisian-Flag=place-image(RSR, width / 1.875, height / 2.00526315789, RR-WC-RC-WC2)

```
