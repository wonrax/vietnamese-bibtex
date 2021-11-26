# vietnamese-bibtex
Bibliography in Vietnamese with BibTeX. Currently supports only numeric citation. Made with [custom-bib](https://www.ctan.org/pkg/custom-bib).

View the compiled PDF showcase [here](https://github.com/wonrax/vietnamese-bibtex/blob/main/test/test.pdf).

### How to use
Download the file `vietnumeric.bst` and use it within your `.tex` file.
For example, if you put the `vietnumeric.bst` in the same directory with your `.tex` file, specify the bibliography style with this command:
```
\bibliographystyle{vietnumeric}
```
Example, compilable code is available under [test/](https://github.com/wonrax/vietnamese-bibtex/tree/main/test).
### About book edition translation
Book edition (e.g., "3rd edition" or "phiên bản thứ 3") is not translated since it involves deep modification of the code. If you want to customize the style to translate the book edition, please refer to the section [#Customization](#customization) below.
### Customization
To make edits to the translated words, change the content of the file `vietnamese.mbs` and recompile with:
```
latex vietnumeric.dbj
```
It should output a new version of `vietnumeric.bst`.

To make advanced changes or further modification, please visit [custom-bib's page](https://www.ctan.org/pkg/custom-bib) for documentation and tutorials.
