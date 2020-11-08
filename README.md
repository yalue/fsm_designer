Modified copy of the FSM designer
=================================

This project contains a modification of [madebyevan.com/fsm](http://madebyevan.com/fsm/),
which is also available [on github](https://github.com/evanw/fsm).

I created this when I was teaching a course on automata theory.  I am a big fan
of the original version, but there were a few enhancments that made life easier
in my personal use:

 - Allowed exporting the current image as JSON, and uploading JSON. This
   allows for saving designs and modifying them later. (Quite useful when you
   have large diagrams--the most likely ones to contain mistakes!)

 - Made it automatically crop the PNG output!

 - Allowed adjusting circle sizes, to fit more text if needed.

 - Added the ability to not draw circles at all for a given node. This was a
   quick hack to allow adding plain-text annotations.

 - Added escape sequences: \emptyset, \leftarrow, and \rightarrow. All of these
   can be useful when drawing more complex diagrams, including TMs.

 - Added a "clear everything" button.

 - Fix some bugs in LaTeX exporting with some non-escaped characters.


Miscellaneous Notes
-------------------

I know the structure of the repository is different from the original, but I
found that a single HTML + javascript file is sufficient for this!

