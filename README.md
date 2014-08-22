RegressionModels
================

#COURSERA and Johns Hopkins University course

>NOTE: a couple of days after the submission of the Regression project and while working in another course project, something was "rare" with a github commit and now inside this repo are show a lot of another repos an files. Please, the only files that should concern about this Regression Model peer review project are:


>1. *__RegressionModelsProject.Rmd__* the source file

>2. *__RegressionModelsProject.pdf__* the compiled file from the source

>3. *__default.tex__* the latex template to produce the output

>4. This *__readme. md__* file


Hello,

You'll find the original R markdown file to produce the final report in PDF format.
To obtain exactly the same pdf output it is needed the default.tex file that is the latex template that pandoc use to create the document.

This template has only two minors modifications over the original that is installed by  `knitr+rmarkdown+markdow` libraries.
 
 1. Included in the preamble a package "\usepackage{booktabs}	% suport to table rule EDB" to be use for xtable inside R
 
 2. Three new lines at lines 162-163 and 164 to give to the abstract any other name as Sypnosis, Executive Summary, etc

```
162 $if(abstract-title)$
163 \renewcommand{\abstractname}{$abstract-title$}
164 $endif$
```

Enjoy it,
Eduardo
