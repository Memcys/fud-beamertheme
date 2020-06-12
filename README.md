# FUDefence
Memcys' UCAS thesis Defence theme based on [Focus v2.6](https://github.com/elauksap/focus-beamertheme).

Focus beamer theme aims at a clean and minimalist design,
so to minimize distractions and put the focus directly on the content.

Requires the packages
- [appendixnumberbeamer](https://ctan.org/pkg/appendixnumberbeamer)
- [PGF/TikZ](https://ctan.org/pkg/pgf)
- [fira](https://ctan.org/pkg/fira) (optional)

to be installed in your LaTeX distribution.

The UCAS logos are from https://www.ucas.ac.cn/site/11?zu=64925, and the usages of them should always follow the instructions conforming to the regulations.

Changes
-------
- Add a UCAS logo to the rightmost of the footline
- Default colors of titlelike, emph, block title and block body get changed
- logo in the titlepage of the demo changed to a UCAS logo

Instructions
============
After downloading, copy the files named beamer*themefud.sty into the same folder as your LaTeX source file.

Then include the theme by writing:
```latex
\documentclass{beamer}

\usetheme{fud}
```
in the preamble of your document.

Chinese support (optional)
--------------------------
Add the following line
```latex
\usepackage{ctex}
```
in the preamble of your .tex source file (and for Linux users at least, *compile* it with **xelatex** or **lualatex**).

Customize colors
----------------
Focus is based on two colors, namely `main` and `background`, that can be customized after including the theme.

For example:
```latex
\usetheme{fud}

\definecolor{main}{RGB}{92, 138, 168}
\definecolor{background}{RGB}{240, 247, 255}
```
produces the following ice-blue color theme.

![](https://github.com/elauksap/focustheme/blob/master/demo-screenshots/demo-titlepage-color.jpg)

Customize the footline
----------------------
The footline numbering can be customized through the theme option _numbering_. The standard value is:
```latex
\usetheme[numbering=progressbar]{fud}
```
that shows an progress bar of increasing length on the footline.

Alternatively, a full footline bar with the frame numbering can be shown with:
```latex
\usetheme[numbering=fullbar]{fud}
```

The footline may also be disabled by typing:
```latex
\usetheme[numbering=none]{fud}
```

Customize fonts
---------------
Focus is using the [Fira fonts](https://bboxtype.com/typefaces/FiraSans/) by default.

This can be changed by using the option _nofirafonts_:
```latex
\usetheme[nofirafonts]{fud}
```
You may **prefer** this way for your thesis *defence* and in addition:
```latex
\usefonttheme{professionalfonts}
```

License
=======
This software is released under the [GNU GPL v3.0 License](https://www.gnu.org/licenses/gpl-3.0.en.html).

Contacts
========
If you are enjoying this theme please share it with your friends or colleagues!

Any suggestions, comments, criticism or appreciation are welcome!

Contact information are available to registered users on my Github profile page.

Contributors
============
Focus was initially created and designed by [Pasquale Africa](https://github.com/elauksap).

The following people deserve appreciation and acknowledgment for improving the template with
additions and modifications (in alphabetical order):

- Sebastian Friedl
- Benjamin Goldman

A more detailed contribution list is found [here](https://github.com/elauksap/focus-beamertheme/graphs/contributors).