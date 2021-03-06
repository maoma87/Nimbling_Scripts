Nimbling\_Scripts
=================

Scripts to enhance graphic workflows in Illustrator and/or Mac OS X.

Some I wrote myself, some are others' work, attribution is in the scripts themselves.

I have these scripts bound to shortcuts using redsweaters' Fastscripts -
replacing several illustrator native shortcuts (taking care to remove them from
illustrator) and adding a few.

I have them set up like this:

Clip scripts
------------

![](<images/Clipper.png>)

~   Clipper Icon

![](<images/Bottomclipper.png>)

~   Bottom Clipper Icon

1.  Select two or more objects.

2.  (CMD + 7) "Clipper.jsx". AND (CMD + ALT + CTRL + 7) "Bottomclipper.jsx".

These clip scripts attempt to copy the initial objects appearance and paste it
to the resulting clipping mask. Due to illustrator limitations this only works
for single stroke, single fill appearances. Ideal for cell shading objects.
Allowing for a super smooth workflow when used with Astute Graphics' Dynamic
Sketch; Simply draw an object, draw the shadow / highlight bits, select both and
execute the "Bottomclipper".

![](<images/VectorLips.gif>)

~   Bottomclipper in Action

Send behind… & Bring in Front of…
---------------------------------

![](<images/Bring-in-Front-of.png>)

~   Bring in Front of Icon

![](<images/Send-Behind.png>)

~   Send Behind Icon

1.  Select two or more objects.

2.  (CMD + CTRL + SHIFT + [ ) & (CMD + CTRL + SHIFT + ] )

Put the selected objects in front of the topmost- or behind the bottom object of
the selection. Useful when you use large amounts of objects and you just keep
pressing "backward" or "forward" without revealing or eclipsing your other,
chosen object. *Fun fact: these even work when either object is inside- or
outside of a clipping group, allowing you to add or remove an object from a
clipping group super quick*

Clear fill, clear stroke scripts.
--------

Using these, you can directly clear a fill or a stroke using single shortcuts.
I have them set up to option+/ and cmd+/ - which maps just like photoshop!
If it's not working, use direct- or group selection tools to select your object.

Outliner
--------

![](<images/Outliner.png>)

~   Outliner Icon

1.  Select one or more objects.

2.  (CMD + SHIFT + O) "Outline Stroke and Text.jsx"

Outline both text and stroke, using the shortcut previously reserved only for
text.

Swap object colors
------------------

1.  Select exactly two objects.

2.  (CMD + ALT + CTRL + S) "Swap Object Colors.jsx"

This script swaps the colors (stroke and-or fill) of exactly TWO selected
objects.

Flip Horizontal & Vertical
--------------------------

1.  Select a single object.

2.  (CMD + SHIFT + H) & (CMD + SHIFT + V)

Flip Horizontal and Vertical.

SVG image bevel filters, for use inside of illustrator.
-----------------------------

1.  Select an object or group of objects.
2.  Got to "Effect > SVG Filters > Apply SVG filter...
3.  In the dialog you're presented with, press the "new SVG filter" icon (looks like new document)
4.  Paste "ImageBevel10Redshift.txt" or "ImageBevel20Redshift.txt" over everything there.

![](<images/fruitbevels.png>)

~   Slices of fruit made using these SVG filters

Axonometry actions
------------------

![](<images/iso45v.png>)

~   iso45v Icon

![](<images/iso45.png>)

~   iso45 Icon

![](<images/ssr30.png>)

~   ssr30 Icon

![](<images/fl2030.png>)

~   fl2030 Icon

![](<images/fl3020.png>)

~   fl3020 Icon

1.  Select a single object, run action.

2.  The Axonometry folder contains five illustrator actions sets that emulate
    different axonometries, of which the “SSR 30º” & “ISO 45º + Vertical scale”
    are likely what you want. The “Flatland -20º & 30º” set is the one I used to
    create the cabinet at http://nimbling.com/graphic.html

![](<images/Bookshelf.gif>)

~   Isometry in action

![](<http://nimbling.com/images/pr/gd-06-large.jpg>)

~   Build Your Own Cabinet - Style

![](<http://nimbling.com/images/pr/gd-07-large.jpg>)

~   Example of isometric artwork

 

Window Tiler Script (or .App)
-----------------------------

1.  Launch using your launcher of choice (Better touch tool, Alfred,
    Quicksilver, Launchbar, etc.) to tile up to 12 of your finder windows.
