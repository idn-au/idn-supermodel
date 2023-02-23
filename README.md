# GSQ Supermodel

This repository contains the source code for the website documenting the [Geological Survey of Queensland](https://dmp.wa.gov.au/Geological-Survey/Geological-Survey-262.aspx) within the [Department of Resources](https://www.resources.qld.gov.au).

Please see the documentation's online location:

* <http://nicholascar.com/gsq-supermodel/>

## License & Rights

This repository's content is available for reuse according to the [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

This content is copyright as follows:

&copy; Government of Queensland, 2023

## Contacts

For technical matters, please contact:

**Nicholas Car**  
_Data Architect_  
[KurrawongAI](https://kurrawong.ai) 
<nick@kurrawong.ai>

For other matters, please contact:

**Geological Survey of Queensland**  
<https://www.business.qld.gov.au/industries/mining-energy-water/resources/geoscience-information/gsq>

# Technical Operations

This repository uses the [MkDocs](https://www.mkdocs.org/) tool to build a static website - just HTML pages, no database etc. - from simple [Markdown](https://www.markdownguide.org/) text files and images.

MkDocs uses [Python](https://www.python.org/) scripting to compile the Markdown files, images etc. into HTML. It can be run locally - on a desktop/laptop - to test documentation changes, and pushed to GitHub to be auto-deployed.

To serve this content as a static site locally, run:

`mkdocs serve`