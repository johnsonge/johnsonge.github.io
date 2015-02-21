---
layout: post
title: Squashed?
---
   
The bug hunt is not going quite as well as planned. We're not discouraged though. We've reached out to the community and they have been very willing to help us resolve the issue. What we initially thought would be a very easy fix (with a solution like changing something from an int to a float or something) turned out to be something most likely regarding the RegEx used in the view inspector that doesn't allow doubles. The team is meeting up this weekend to get the issue figured out and hopefully started on our next bug fix. There have been more developers commenting on our bug listing, helping to pint us in the right direction and trying to figure it out themselves. We know the location and the issue of the problem, so now it's just a matter of figuring out a better testing method for our changes (because currently we're recompiling and rebuilding every time and it takes a while) and learning the regEx that QT uses. Overall it still doesn't seem like we're far off, it's just a matter of testing things out more efficiently

<br>
On the bright side, while trying to figure out this bug, we've run into lots of other bugs that we can fix after we figure out how to solve the RegEx issue. For example, there is one bug where the user is allowed to enter text into the tempo and it should only allow numbers. You can also enter infinitely (to our knowledge) many characters into the tempo field and it would be best to limit the tempo to either 2 or 3 decimal places if any. We are looking forward to figuring out this issue and we feel like we're getting very close.
