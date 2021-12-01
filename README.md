# Generate Custom LaTeX Bibliography Styles

Might be useful for journals with creative guidelines such as “up to 5 authors, if more, just the first followed by et al.”

# Use

This utility can be run in place, just clone the repository, edit `myunsrt.dbj` to your liking, and generate the `.bst` file with:

```
latex myunsrt.dbj
```

This file can then be copied into your latex project, and loaded with `\bibliographystyle{myunsrt}` before the bibliography is loaded, e.g.:

```
\bibliographystyle{myunsrt}
\bibliography{./bib}
```



# Dependencies

This should only require texlive, available from the package manager of numerous distributions (e.g. `app-text/texlive` on Gentoo Linux).
