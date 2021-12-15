# vietnamese-bibtex
Bibliography in Vietnamese with BibTeX. Currently supports only numeric citation. Made with [custom-bib](https://www.ctan.org/pkg/custom-bib).

### Style examples
```
[1] Leonard Susskind và George Hrabovsky (2014), Classical mechanics:
the theoretical minimum (Penguin Random House, New York, NY).

[2] P. J. Cohen (1963), “The independence of the continuum hypothesis”.
Proceedings of the National Academy of Sciences, tập 50, số 6,
tr. 1143–1148.

[3] Jian Tang (1996), “Spin structure of the nucleon in the
asymptotic limit”. Luận văn Thạc sĩ, Massachusetts Institute of
Technology, Cambridge, MA.

[4] Judith Butcher (1981), Copy-editing (Cambridge University Press),
2nd edition.
```
### How to use
- Download the file `vietnumeric.bst` in [lastest release](https://github.com/wonrax/vietnamese-bibtex/releases/latest).
- Use that file within your `.tex` file.
For example, if you put the `vietnumeric.bst` in the same directory with your `.tex` file, specify the bibliography style with this command:
```
\bibliographystyle{vietnumeric}
```
Example, compilable code is available under [example/](https://github.com/wonrax/vietnamese-bibtex/tree/main/example).
### About book edition translation
Book edition (e.g., "3rd edition" or "phiên bản thứ 3") is not translated since it involves deep modification of the code. If you want to customize the style to translate the book edition, please refer to the section [#Customization](#customization) below.
### Customization
To make edits to the translated words, change the content of the file `vietnamese.mbs` and recompile with:
```
latex vietnumeric.dbj
```
It should output a new version of `vietnumeric.bst`.

To make advanced changes or further modification, please visit [custom-bib's page](https://www.ctan.org/pkg/custom-bib) for documentation and tutorials.
### Acknowledgement
- [custom-bib](https://www.ctan.org/pkg/custom-bib) for making this possible.
- [The quick BibTeX guide](https://www.bibtex.com/e/entry-types/) for the bibliography examples.
