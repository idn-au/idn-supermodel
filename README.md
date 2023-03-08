# IDN Supermodel

This repository contains the source code for the website documenting a data model for the [Indigenous Data Network](https://mspgh.unimelb.edu.au/centres-institutes/centre-for-health-equity/research-group/indigenous-data-network) within the [Indigenous Studies Unit](https://mspgh.unimelb.edu.au/centres-institutes/centre-for-health-equity/research-group/indigenous-studies) of the University of Melbourne.

The website built from this content is online at 
Please see the documentation's online location:

* <http://idn-au.github.io/idn-supermodel/>

## License & Rights

This repository's content is available for reuse according to the [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

This content is copyright as follows:

&copy; Indigenous Data Network, 2023

## Contacts

System Owner:

**Sandra Silcot**  
Indigenous Data Network  
*contact [via the IDN](https://mspgh.unimelb.edu.au/centres-institutes/centre-for-health-equity/research-group/indigenous-data-network)*

For technical matters, please contact:

**Nicholas Car**  
_Data Architect_  
[KurrawongAI](https://kurrawong.ai)  
<nick@kurrawong.ai>


# Technical Operations

This repository uses the [MkDocs](https://www.mkdocs.org/) tool to build a static website - just HTML pages, no database etc. - from simple [Markdown](https://www.markdownguide.org/) text files and images.

MkDocs uses [Python](https://www.python.org/) scripting to compile the Markdown files, images etc. into HTML. It can be run locally - on a desktop/laptop - to test documentation changes, and pushed to GitHub to be auto-deployed.

To serve this content as a static site locally, run:

`mkdocs serve`