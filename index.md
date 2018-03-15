As discussed in the [Book Design thread](http://www.edwardtufte.com/bboard/q-and-a-fetch-msg?msg_id=0000hB) of Edward Tufte's [Ask E.T Forum](http://www.edwardtufte.com/bboard/), this site is home to LaTeX classes for producing handouts and books according to the style of Edward R. Tufte and Richard Feynman.

Download the latest release, browse the [source](https://github.com/Tufte-LaTeX/tufte-latex), join the [mailing list](http://groups.google.com/group/tufte-latex), and/or submit patches. Contributors are welcome to help polish these classes!

Some examples of the Tufte-LaTeX classes in action:

* [Some papers](http://swtools.wordpress.com/papers/) by Jason Catena using the handout class
* A [handout](http://people.ucsc.edu/~weissman/MathClubTalk2009.pdf) for a math club lecture on volumes of n-dimensional spheres by Marty Weissman
* A [draft copy of a book](http://slugmath.ucsc.edu/mediawiki/index.php/Image:NumberTheory.pdf) written by Marty Weissman using the new Tufte-book class
* An [example handout](http://tufte-latex.googlecode.com/files/week5lecture.pdf) ([source](http://tufte-latex.googlecode.com/files/Week5Lecture.tex)) using XeLaTeX with the `bidi` class option for the ancient Hebrew by Kirk Lowery

The following LaTeX packages are required:

* chngpage (or changepage)
* fancyhdr
* fontenc
* geometry
* hyperref
* natbib and bibentry
* optparams
* paralist
* placeins
* ragged2e
* setspace
* textcase
* textcomp
* titlesec
* titletoc
* xcolor
* xifthen

The following packages are optional and will be automatically used if available:

* beramono
* helvet
* letterspace (in the microtype package)
* mathpazo
* soul