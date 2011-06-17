This is the distribution package for cascadilla.cls, a LaTeX document class for
typesetting documents that conform to the Cascadilla Proceedings Project
stylesheet, used by various linguistics conference proceedings (such as WCCFL).
Also included are an example document (example.tex and example.pdf), a BibTeX
bibliography style (cascadilla.bst) and a BibTeX database used by the example
document (exampleref.bib).

This package was written by Max Bane, copyright 2008-2011, and is maintained by
the same. It is distributed under the conditions of the LaTeX Project Public
License, a copy of which is included in LICENSE.txt; the license boilerplate is
also included at the top of each source file.

The reference stylesheet that this document class aims to implement is described
by the Cascadilla Proceedings Project at the following location:
http://www.lingref.com/cpp/authors/style.html

The style is occasionally updated by Cascadilla; if you find that this document
class no longer implements the stylesheet correctly, or if you discover any
bugs, please contact Max Bane at max.bane@gmail.com.

As of version 1.7, you may now also report and view bugs, check out the latest
source code, or even contribute your own changes to the source code, at the
github project page for this project:
https://github.com/maxbane/cascadilla.cls

Special thanks to Jonathan Brindle for helping to resolve some glitches in
previous versions.

VERSION HISTORY

Version 1.6
    Redefined \thanks command once more, to conform with the new requirement for
an "invisible asterisk".

Version 1.5
    Redefined the \thanks command for use in titles.

Version 1.4
    Updated the appearance of citations and references to be more in line with
the Cascadilla stylesheet.

Version 1.3
    Put in some missing \selectfont's
    Adjusted \abovecaptionskip and \belowcaptionskip for use with \centering
rather than the center environment.

Version 1.2
    Restored blank space between title and author

Version 1.1
    Made title matter optional
    Added notimes option
    Added additional blank line after title
    Section labels end with a space rather than a quad
    Made figure/table captions bold
    Added "immediate" subsection commands for proper spacing of sub-headings
that immediately follow super-headings.

Version 1.0
    Initial release
