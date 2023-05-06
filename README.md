![alt text](https://github.com/paulamartingonzalez/Targeted_Literature_Reviews_via_webscrapping/blob/main/tlr2.jpg)

# Targeted Literature Reviews using webscraping 

Web scraping to get articles for a given query. It returns an spreadsheet with titles, abstracts and pmids.

It works on Pubmed and it is based on biopython: https://biopython.org

You can run it on Google Colab without downloading anything locally! :) https://research.google.com/colaboratory/faq.html

## How it works?

For a given query, you can get:

1) an xlsx file with the titles and abstracts of the papers in your query
2) a graph with the papers in your query and their references. This lets us find highly cited papers in a given field
3) an xlsx file with the titles and abstracts of the references as well together with their degree (i.e. the number of connections in the graph). The higher the degree, the more papers in your query citing it

For the example query "Radiomics"AND"CT"AND"Ovarian Cancer" we get:




![alt text](https://github.com/paulamartingonzalez/WebScrappingLiterature/blob/main/Unknown-7.png)




## Next steps:
- At the moment it only works on PubMed. I'm working on making it work in arxiv and bioarxiv as well. Implementation in Google Scholar is complicated but I am also trying to get my head around it.
- I'm working on an implementation that requires no code whatsoever - via website or widgets.
- It would be great to import the articles to Mendeley, so I'm also working on that!

If you have any suggestion to improve the code, please feel free to raise an Issue!

## Questions:

### What happens to articles behind a paywall? 
You'll be able to get the abstract but unfortunately not the references. So those won't be added to the graph. Open science is the way to go!!
