# Startup-Founders-Graph-Analysis
Web-scrape list of journals published by startup founders, and perform graph analysis to analyze relationships between founders

## Web-Scraping Notebook

*   **Citations:** Given a journal, extract the list of citations/references it cited. Use Regex to parse each citation, before storing it in a dictionary. Respective functions created for each of the following publications/versions: IEEE, Nature, PLOS and PDF.
*   **Cited By:** Given a journal, extract the list of all other journals that cited it. Each time the code is run, maximum of 250 citations scraped. Restart notebook to continue scraping.
*   **Profile:** Given a founder, extract basic information from his/her Google Scholar profile page.
*   **Publication:** Given a founder, extract the list of all published journals from his/her Google Scholar profile page. Each time the code is run, maximum of 250 journals scraped. Restart notebook to continue scraping.
*   **Pubs without Profile:** If a founder has no Google Scholar profile page, use this code to scrape his/her list of published journals. Each time the code is run, maximum of 250 journals scraped. Restart notebook to continue scraping.


## Data Analysis Notebook

Performed basic data cleaning and analysis on web-scraped data. Aimed to determine the "success" of startup founders using the following metrics:
*   **Author position** in journal published
*   Total **number of citations** per year
*   **Depth** and **breadth** of research fields
*   Number of journals published in **influential publications** (IEEE and Nature)


## Foreign Citations Notebook

Aimed to determine the "success" of startup founders by analyzing the **distribution of foreign journals** that cited journals published by founders. Created a tree-map for each founder to plot distribution of foreign journals.


## Graph Analysis I Notebook

*   Created **multi-directed graph** to analyze the citation relationships among
startup founders and other researchers, up to one degree of separation. If one researcher cited another, a directed edge links the two nodes together.
*   Analyzed the top 10 researchers **most frequently cited** by each founder.
*   Used various graph **centrality measures** to determine the most influential researchers in each field.
