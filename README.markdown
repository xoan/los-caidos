(PDF LaTeX Edition of) Los Caídos, a book by Magnus Dagon
=========================================================

Copyright (C) 2010 Magnus Dagon  
Copyright Edition (C) 2011 Xoan Sampaiño  
Copyright Artwork (C) 2010 Pablo Vaquero

Permission is granted to copy, publish and/or distribute this work freely and/or derivative works of this work, in whole or in part, by any means and any nonprofit purpose, provided this notice is preserved.

Original text
-------------

<http://ngc3660.es/index.php?option=com_content&view=article&id=2006:magnus-dagon&catid=35:colaboradores&Itemid=159>

Dependencies
------------

* babel
* mathdesign
* textcomp
* graphicx
* microtype
* hyperref, hyperxmp
* eso-pic
* geometry
* crop
* fancyhdr
* titlesec
* appendix

Generating PDF Files
--------------------

    # getnonfreefonts-sys garamond
    $ pdflatex magnus_dagon-los_caidos.tex
    $ pdflatex !$
