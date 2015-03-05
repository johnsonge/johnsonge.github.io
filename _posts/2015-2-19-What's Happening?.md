---
layout: post
title: What's Happening?
---
   
__TOS Chapter 7 Exercises:__
The exercises for TOS chapter 7 were relatively straight forward. Chapter 7 talked about patches and walked me through some sample problems. the first of which was seeing the difference between two files that had a small change in them. Running Both
<br>
<br>
diff -u hello.c.punct hello.c > hello-excitement.patch  
diff hello.c.punct hello.c > hello-excitement.patch
<br>
<br>
commands to see the differences that runing it with and withough -u would cause, I saw that including "-u" to the command resulted in an output that had the file names, dates, times, and code. On the other hand, when I ran the command without "-u", the output was only the print statement for each file highlighting the differences.
<br>
<br>
_with -u_

--- hello.c.punct	2015-02-24 09:42:29.000000000 -0500  
+++ hello.c	2015-02-24 09:45:21.000000000 -0500  
@@ -5,6 +5,6 @@  
include <stdio.h>  
int main() {  
-    printf("Hello, World.\n");  
+    printf("Hello, World!\n");  
     return 0;  
 }  
\ No newline at end of file>'
<br>
<br>
_without -u_

8c8  
    printf("Hello, World.\n");  
    printf("Hello, World!\n");
<br>
<br>
The rest of the problems were about the same in that you just needed to read the sections and follow the instructions to answer the questions. I didn't run into too many issues and the ones that I did were resolved relatively quickly by going back over the readings for the chapter.
<br>
<br>
__Reading: Finding the Right Data for software Cost Modeling:__

The article in the magazine that I chose to read was about software cost modeling and finding the right way to do it. In our Software Engineering coursed that we've taken so far, there has been a recurring theme of developers having a hard time keeping on time and within budget. This article talked about many of the methods used in managing a software project to follow its set critera. The article opens with a statement that "Off-the-shelf "untuned" models have been up to 600% inaccurate in their estimates", I think this is saying something either about the culture of software engineers, expectations of companies of developers, or the project managers. There was a section titled "Cost modeling with Cocomo(Constructive Cost Model)"; it talked about how it helps developers reason about cost and schedule related to the project at hand. A main advantage listed was that it's an open model with published data. It measures effort in calendar months and takes several variables into account including programmer capability and complexity. It was an interesting read, but it was hard to get a grasp on the actual calculations used since there were no examples. But from what I read, it seems like an effective model that helps greatly overall towards software cost modeling.
<br>
<br>
__12 predictions for the future of programming:__

The mot interesting prediction that I found from this article, was number 3: JavaScript for everything. After hearing Semmy talking about the importance of knowing JavaScript in today's software engineering world, and then seeing this article, pretty much solidified the fact in my mind that I need to start learning it. Maybe not necessarily for a job that I may want to get in the future, but just to be able to be where the action is in some sense. 

> "Biologists will probably stick with Python. Linux will be written in C. But almost everything else is fair game as JavaScript __gobbles the world__.

