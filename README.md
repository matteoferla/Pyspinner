# Spinning Python glyph
**NOTE:** I orginally called it pyspinner as a spinning icon is a spinner. Turns out there is some other thing called pyspinner.
Sorry about that!

**NOTE:** It has been pointed out to me that the a python has roundish blotches while a snake with triangles on its back is a rattlesnake, diamondback or something else. I apologise for any zoological misunderstandings.

A small CSS to make a spinner (throbber) icon of a snake biting its tail (for Python-based webpages, either Brython or server-side python).

The CSS is very simple, nothing fancy like Font-Awesome.
There are four classes:
*  pyspinner = 1em B&W clockwise
*  pyantispinner = 1em B&W counterclockwise
*  bigpyspinner = 32px colour clockwise
*  bigpyantispinner = 32px colour counterclockwise
*  pycorpse= 1em static dead snake

With the except of the big ones, they have to be display:inline.

```
<span class=pyspinner></span>
<div class=bigpyspinner></div>
```

[Example page](https://rawgit.com/matteoferla/Pyspinner/master/demo.html).

[Brython Hello world with pyspinner](https://rawgit.com/matteoferla/Pyspinner/master/pyspinner_brython.html)

[Bacterial namegen](http://extra.matteoferla.com/bacterial_namegen.html)

Figures:

![pyspinners](https://rawgit.com/matteoferla/Pyspinner/master/pyspinners.png)

