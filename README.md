# knitr, pandoc, docx and EMF image size issues

This is to document a simple suggestion to work around the issue that the size of EMF graphics cannot currently be determined by pandoc (see [issue 2720](https://github.com/jgm/pandoc/issues/2720)). It is interesting to use EMF in docx as it works in all Word installations by default. For example, EMF graphics can be created with [R](https://www.r-project.org/) using [devEMF](http://cran.at.r-project.org/web/packages/devEMF/index.html). See: 

- [Rendered Word document with instructions](https://github.com/rfhb/rmarkdownknitrpandocemf/blob/master/Report.docx?raw=true)
- [Rendered PDF file](https://github.com/rfhb/rmarkdownknitrpandocemf/blob/master/Report.pdf?raw=true)

(end)
