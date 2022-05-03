# MEDEA (Mapping Environmental DEbates on Adaptation)

## Mar 2014 – Dec 2014

### Project Description

The goal of the project was to identify the actors behind the assessment reports published by the IPCC (Intergovernmental Panel on Climate Change) and gather metrics to assess and compare their contributions over time.

The size of the data sets studied, 5 documents, 250+ chapters, 4000+ authors, is only a mere indication of the challenges faced when collecting and analyzing this data.

The main challenge came from the inconsistencies in the data, its contradictions, its ambiguities, and its evolutions over 25 years from the first report published in 1990 to the completion of the latest report in 2014.

The work-flow from the sources of the data, in PDF documents, to the interactive Web visualizations, in d3.js, spans multiple projects published on GitHub:

1. ipcc-fact-checking: collect data extracted from PDF documents, as CSV files and metadata
2. ipcc-facts-import: import records from CSV files as facts into an intermediate MySQL database
3. ipcc-database: edit and refine the data in the authoritative MySQL database, export as CSV files
4. ipcc-feedback-loop: export data from MySQL database back to the original CSV format for comparison with the source documents
5. ipcc-acquire: query the MySQL database to answer questions about the authors
6. ipcc-parse: convert the results from the above queries from CSV/TSV to JSON
7. ipcc.projetmedea.fr: an interactive visualization to explore and filter the data about IPCC authors
8. d3.explore: comparison of different visualizations including the above to answer questions about IPCC authors

### Other Creators

* [Timothée Collignon](https://www.linkedin.com/in/timoth%C3%A9e-collignon-6a217212/)
* [Tommaso Venturini](https://www.linkedin.com/in/tommaso-venturini-0310805/)
* [Ian Gray](https://www.linkedin.com/in/ian-gray-0005a54/)
* [Nicolas Baya-Laffite](https://www.linkedin.com/in/nicolasbaya/)
* [Audrey Baneyx](https://www.linkedin.com/in/audrey-baneyx-4b55b26b/)
* [Guillaume Plique](https://www.linkedin.com/in/guillaume-plique-24665484/)
* [Daniele Guido](https://www.linkedin.com/in/danieleguido/)
* [Paul Girard](https://www.linkedin.com/in/paul-girard-57822118/)
* [Monica Lafon](https://www.linkedin.com/in/monicalafon2014/)
* [Apolonia Rakowski](https://www.linkedin.com/in/apolonia-rakowski-28706492/)

### See Project

* [MEDEA (Mapping Environmental DEbates on Adaptation)](https://github.com/medea-project)
