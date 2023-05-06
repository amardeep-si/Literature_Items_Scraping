
# Targeted Literature Reviews using webscraping 

Web scraping to get articles for a given query. It returns an spreadsheet with titles, abstracts and pmids.

It works on Pubmed and it is based on biopython: https://biopython.org

## How it works?

For a given query, you can get:

1) an xlsx file with the titles and abstracts of the papers in your query
2) a graph with the papers in your query and their references. This lets us find highly cited papers in a given field
3) an xlsx file with the titles and abstracts of the references as well together with their degree (i.e. the number of connections in the graph). The higher the degree, the more papers in your query citing it

