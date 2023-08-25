# advanceddynamics - Advanced Dynamics Notation Package
## v1.0 (2023/08/24)
---
>--------------------------------------------------------------------------------
>Copyright (c) 2023 by Nolan Canegallo <nacanega at ncsu dot edu>
>--------------------------------------------------------------------------------
>
>This work may be distributed and/or modified:
>
>    1.  under the conditions of the LaTeX Project Public License, either version
>        1.3c of this license or (at your option) any later version.
>        The latest version of this license is in
>            https://www.latex-project.org/lppl.txt
>        and version 1.3 or later is part of all distributions of LaTeX
>        version 2005/12/01 or later.
>        Version 1.3c is also provided in 
>            doc/latex/advanceddynamics/licenses/LICENSE-LPPLv1.3c.txt
>        for convenience.
>
>    and/or
>
>    2.  under the GNU General Public License, either version 3 of this license 
>        or (at your option) any later version.
>        Version 3 of this license is in
>            https://www.gnu.org/licenses/gpl-3.0.txt
>        Version 3 is also provided in 
>            doc/latex/advanceddynamics/licenses/LICENSE-GPLv3.0.txt
>        for convenience.
>
>This work has the LPPL maintenance status `maintained'.
>
>The Current Maintainer of this work is Nolan Canegallo.
>
>This work consists of 16 files:
>    advanceddynamics.sty
>    advanceddynamicsmanual.tex
>        advdyndoc-00-title.tex
>        advdyndoc-01-introduction.tex
>        advdyndoc-02-frames.tex
>        advdyndoc-03-general-terms.tex
>        advdyndoc-04-advanced-terms.tex
>        advdyndoc-05-differentiation.tex
>        advdyndoc-06-vectors.tex
>        advdyndoc-07-matrices.tex
>        advdyndoc-08-equations.tex
>        advdyndoc-09-misc.tex
>        advdyndoc-10-add-info.tex
>        advdyndoc.bib
>    advanceddynamicsmanual.pdf
>    advdyndoc.sty

`advanceddynamics` provides a set of macros and commands to easily create equations and typeset in the notation of the graduate courses [*MAE 511 - Advanced Dynamics I*][1] and [*MAE 789 - Advanced Dynamics II*][2] taught by [Dr. Mazzoleni][3][^1] at [North Carolina State University][4][^2]. The primary intended use is to aid in typesetting derivations of equations of motion and to that end, in addition to providing commands to easily typeset individual terms, the package also includes many of the fundamental equations and definitions written in the notation of the aforementioned courses. 

A full list of commands with examples, required packages, basic installation instructions, and more is located in the [Advanced Dynamics Notation Package Manual][5]. The manual is fully linked using `hyperref`, so downloading it is recommended.

To easily get started, there are currently two main ways to use this package:
- The first is to download the [`advanceddynamics.sty`][6] file from GitHub and simply place it in the same folder as your document. 
- The second is to download a [release][7] and copy it to your local distribution so that you can use it from any document. More information can be found in the [manual][5].

Dependencies:
- `accents`
- `amsmath`
- `amssymb`
- `mathttools`
- `tensor`

[1]: https://www.engineeringonline.ncsu.edu/course/mae-511-advanced-dynamics-with-applications-to-aerospace-systems/
[2]: https://www.engineeringonline.ncsu.edu/course/mae-789-advanced-dynamics-ii/
[3]: https://www.mae.ncsu.edu/people/apmazzol/
[4]: https://www.ncsu.edu/
[5]: ../master/doc/latex/advanceddynamics/advanceddynamicsmanual.pdf
[6]: ../master/tex/latex/advanceddynamics/advanceddynamics.sty
[7]: https://github.com/nacanega/advanceddynamics/releases

[^1]: The material located in this respository is not endorsed, sponsored, or provided by or on behalf of Dr. Mazzoleni. Please do not contact Dr. Mazzoleni about this package, all communications about this package should be directed to Nolan Canegallo.
[^2]: The material located in this repository is not endorsed, sponsored, or provided by or on behalf of North Carolina State University. 
