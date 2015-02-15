---
layout: post
title: This Bugs Me
---

For this assignment, I decided to use MuseScore; the project that my group is doing for class.  

<br>
6.4:  
The oldest active bug entry for MuseScore is 5 years old. It's titled "Channel Conflict on MIDI export". What the bug is, is one where if you add a new instrument to MuseScore it assigns each of those instruments to its own channel, which wouldn't typically be much of an issue, but when exporting it as a MIDI file it results in the wrong instrument being played. Although this bug is still listed as active, I'm not sure if it has been fixed in the several updates that have come out in the past years. It seems like fixing the issue would be a matter of either specifying a merge of channels when exporting to MIDI or fixing whatever is going wrong during the export process that is causing the wrong instruments to be played.  

<br>
6.5, 6.6:  
Our group has done a good deal of searching through the MuseScore IssueTracker, and the bug that I'll be talking about in this blog is the one we're working on as a group to fix. The bug is easy to reproduce with the latest build. It is an issue with the display in the view inspect regarding tempo. When setting a particular tempo as a double such as 120.5 or 80.25, the tempo in the view inspector will only display the integer, for example 120 or 80 respectively. When working around trying to fix the bug, we found several other potential bug fixes that we will be able to use once we figure out how to fix this one.

<br>
6.7:   
There are several reported bugs related to entering values into fields. Whether that be tempo markings or creating text that are used in the score or used in the program itself. The five bugs that I looked at for the "Bug Triage" were:

<br>
[Deleting a line break in the middle of text automatically adds one at the end](http://musescore.org/en/node/36276)

<br>
[Text in Text-Frames not being seen in parts](http://musescore.org/en/node/47636)

<br>
[changing position of a line (8va, cresc., etc.) causes it to be way out of position on copy/paste](http://musescore.org/en/node/45356)

<br>
[New Inspector control: "Reset to Style" for text elements](http://musescore.org/en/node/47531)

<br>
and of course the one that my team is working on:

[Follow text doesn't work for tempo marking with decimal](http://musescore.org/en/node/46281)

<br>
By the time that I found these five related bugs and checked back in on them, other developers had already either fixed the bugs or checked in to let the poster know that it was being worked on. These were all well documented bugs that give a definite direction and documentation for them to be solved by the devs.
