# A demo of some of my favorite reports using Posit Pro Products

This is a quarto presentation on different R report types and integration with Posit team. Enjoy!

It can be accessed at: <https://quartopub.com/sites/questionable/reporting-in-r-with-posit-team>

Some of the example reports included in this repo are: 

R: 

- Quarto presentation 
- RMarkdown (with blastula for email formatting)
- RMarkdown parameterized 
- RMarkdown being used to update a pinned dataset

Python: 

- Jupyter notebook
- Quarto document (with the lightbox extension)

This is part of this webinar reporting project: <https://github.com/22kcox/posit-webinar-series> 

## Publishing 

Notes for the developer: 

This presentation is published to the RStudio demo server using push button publishing from the RStudio IDE. 

It is also published to my quarto pub space. I run `quarto publish quarto-pub` from terminal after cd-ing in to the directory. Answer "Y" to overwrite my previous site and to use the correct account. For example, to publish this slide deck I'm running: `quarto publish quarto-pub reports.qmd`. It will need to be a quarto project. If you have an existing directory of documents that you want to treat as a project just invoke `quarto create-project` with no arguments from within the directory. 

I can access my account and see my deployments at <https://questionable.quarto.pub/>. 

