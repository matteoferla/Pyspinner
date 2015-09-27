# Pyspinner
A small CSS to make a spinner icon of a snake biting its tail (for Python-based webpages, either Brython or server-side python).

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


[Example page](https://rawgit.com/matteoferla/Pyspinner/blob/master/demo.html).



