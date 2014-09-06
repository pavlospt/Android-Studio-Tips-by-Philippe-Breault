---
layout: post
title:  "Hightlight All The Things"
date:   2014-08-13 4:00:00
categories: android-studio tips editing
---

Look up the shortcut to the right of this menu: *Edit* → *Find* → *Highlight Usages in File*

This will highlight every occurrence of a symbol in the current file. This is more than some simple pattern matching, it will actually understand the current scope and  only highlight what is relevant.

You can then navigate up or down using the shortcuts from *Edit* → *Find* → *Find Next/Previous*

Additional tips:

 - Highlighting a "return" or a "throw" statement in a method will also highlight all the exit points of the method.
 - Highlighting the "extends" or the "implements" portion of the class definion will also highlight the methods that are overriden/implemented.
 - Highlighting an import will also highlight where it is used.
 - You can cancel the highlighting by pressing Escape﻿

![](https://lh4.googleusercontent.com/-PHQFYqcYi58/U-tQtazuCbI/AAAAAAAAMrE/SGNBmtGwMAk/w198-h184-no/01-highlight.gif)