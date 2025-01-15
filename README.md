# Startup-Founders-Graph-Analysis
Web-scrape list of journals published by startup founders, and performed graph analysis to analyze relationships between founders

## Web-Scraping Notebook

*   **Citations:** Given a journal, extract the list of citations/references it cited. Use Regex to parse each citation, before storing it in a dictionary. Respective functions created for each of the following publications/versions: IEEE, Nature, PLOS and PDF.

*   **Cited By:** Given a journal, extract the list of all other journals that cited it. Each time the code is run, maximum of 250 citations scraped. Restart notebook to continue scraping.

*   **Profile:** Given a founder, extract basic information from his/her Google Scholar profile page.

*   **Publication:** Given a founder, extract the list of all published journals from his/her Google Scholar profile page. Each time the code is run, maximum of 250 journals scraped. Restart notebook to continue scraping.

*   **Pubs without Profile:** If a founder has no Google Scholar profile page, use this code to scrape his/her list of published journals. Each time the code is run, maximum of 250 journals scraped. Restart notebook to continue scraping.
