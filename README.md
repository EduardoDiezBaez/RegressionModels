RegressionModels
================

#COURSER and Jhons Hopkins course

Hello,

You'll find the original R markdown file to produce the final report in PDF format.
To obtain exactly the same pdf output it is needed the default.tex file that is the latex template 
that pandoc use to create the document.  

This template has only two minors modifications over the original that is installed by 
`knitr+rmarkdown+markdow` libraries.
 
 1. Included in the preamble a package "\usepackage{booktabs}	% suport to table rule EDB" to be use for xtable inside R
 
 2. Three new lines at lines 162-163 and 164 to give to the abstract any other name as Sypnosis, Executive Summary, etc

```
$if(abstract-title)$
\renewcommand{\abstractname}{$abstract-title$}
$endif$
```

Enjoy it,
Eduardo
