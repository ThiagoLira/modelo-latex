# IME/USP LaTeX Template

A LaTeX template for Masters and PhD/Doctorate dissertations/theses
according to IME/USP guidelines. Note that the actual formatting of
the document (fonts, cover layout, spacing etc.) is *not* mandatory;
the guidelines deal with the document structure only (the [description
of the guidelines](https://www.ime.usp.br/dcc/pos/normas/tesesedissertacoes)
is included in the template). The template is expected to be useful
for unexperienced LaTeX users. Feel free to customize to your needs
and, if appropriate, send us improvements. :)

The generated PDF file includes a FAQ, a short (but reasonably
compreehensive) LaTeX tutorial, and some examples of LaTeX commands.
Besides that, there are lots of comments in the "tese-exemplo.tex"
and "miolo-preambulo.tex" files about the packages used and things
you might want to customize or learn more about. These comments are
in Brazilian Portuguese. Even if you have some LaTeX experience, you
may benefit from skimming the comments, tutorial, and examples, as
they include some useful tips.

You need a working LaTeX installation, including biber and biblatex
(among other packages). The document may be compiled with "make" or
"latexmk" (preferred) and this repo includes a compiled version of it.

## FAQ

There is a FAQ in the example document and this repo includes a
compiled version of it in PDF format.

## Used packages and installation

There are some instalation instructions in the example document,
included in this repo in PDF format. The template uses makeindex,
biber, and many LaTeX packages.

These packages are used in the template: nag, geometry, etoolbox,
ifxetex, ifluatex, ifpdf, fontenc, inputenc, amsthm, babel, microtype,
indentfirst, footmisc, emptypage, caption, hyperref, biblatex,
setspace, parskip, xcolor, ragged2e, textcase, slantsc, fancyhdr,
graphicx, float, flafter, placeins, pdflscape, rotating, subcaption,
wrapfig, pdfpages, tablefootnote, array, dcolumn, longtable, multirow,
makecell, booktabs, tocbibind, imakeidx, verbatim, latexsym, amsmath,
amssymb, mathtools, csquotes, hypcap, hyperxmp, url, listings,
textcomp, multicol, metalogo, epigraph, imakeidx.

The default fonts depend on these packages: lmodern, fix-cm,
inconsolata, libertine, newtxmath, biolinum.

These packages are not used, but are mentioned and might be useful:
paralist, titletoc, titlesec, lastpage, braket, siunitx, varioref,
cleveref, todonotes, gensymb, glossaries, backref, newtxtt, newtxtext,
gentium, DejaVuSansMono.

These packages are needed if you intend to use xelatex/lualatex:
polyglossia, fontspec.

As of 2018, in debian/ubuntu systems, you need to install (with their
dependencies) at least: texlive-base, texlive-latex-base,
texlive-fonts-recommended, texlive-generic-recommended,
texlive-latex-recommended, texlive-latex-extra, texlive-fonts-extra,
texlive-bibtex-extra, texlive-lang-portuguese, texlive-lang-english,
lmodern, biber, and latexmk. Just run

`sudo apt install texlive-base texlive-latex-base texlive-fonts-recommended texlive-generic-recommended texlive-latex-recommended texlive-latex-extra texlive-fonts-extra texlive-bibtex-extra texlive-lang-portuguese texlive-lang-english lmodern biber latexmk`

## Acknowledgements

 * Original version: Jesús P. Mena-Chalco
 * Revision: Fabio Kon and Paulo Feofiloff
 * Latest updates (utf8, biblatex etc.): Nelson Lago

## TODO

 * Recent biblatex versions (2017) use "labeldate+extradate" instead of
   "labelyear+extrayear"; in a couple of years we should modify the
   files plainnat-ime.bbx and plainnat-ime.cbx accordingly.

 * The translated version of the natbib package included in the template
   is old; we should update it.

## License

The files that are derived from other projects (natbib-ime.sty,
alpha-ime.bst etc.) are subject to their own licenses. The rest
of the code is available under the MIT License.
