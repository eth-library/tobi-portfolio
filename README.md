# TOBI Portfolio

## About this Portfolio

### Description
This portfolio provides a collection of Jupyter Notebooks designed to facilitate the use of open bibliometric data sources for higher education institutions. The goal is to offer tools for cleaning, analysing and improving open data for bibliometric analyses.

### Benefits of Open Data Sources
Using open data sources for research assessment enables more compliance with [DORA](https://sfdora.org/read/) (San Francisco Declaration on Research Assessment), [CoARA](https://coara.eu/agreement/the-agreement-full-text/) (Coalition for Advancing Research Assessment) and [POSI](https://openscholarlyinfrastructure.org/) (The Principles of Open Scholarly Infrastructure) compared to licensed commercial databases. Open data are also aligned with FAIR principles (Findable, Accessible, Interoperable, Reusable). In comparison to established commercial databases, they usually provide:
- Unpaywalled access to the data
- More transparency and possibilities for reuse due to less restrictive licensing
- Broader inclusivity and diversity
- Community-driven improvements

### Included data sources

The portfolio currently includes two open **bibliometric data sources**, OpenAlex and OpenAIRE.

- [OpenAIRE](https://www.openaire.eu/)
   - Note: The data extraction has been updated to [Walden](https://oreo.openalex.org/), the full rewrite of OpenAlex. If you wish to know more or to access older versions of OpenAlex, check out [this link](https://groups.google.com/g/openalex-users/c/-1_wU8yQXGk)
- [OpenAlex](https://openalex.org/)


### Portfolio Scope
This portfolio offers scripts to start using the API of open bibliometric data sources like OpenAIRE and OpenAlex by providing:
- Tutorials in form of Jupyter Notebooks.
- Tools to identify quality issues (in preparation).
- Scripts to perform customized bibliometric analyses.


## Repository Contents

This repository contains Jupyter Notebooks and dependencies for conducting initial bibliometric analyses.

### Files:

##### 
- `requirements.txt` - List of required Python packages (install using `pip install -r requirements.txt`).
- `open_colors.py` - Open source color scheme we use for most the visualizations.
- `language_abbreviations.py` - A dictionary mapping of language abbreviations to full language names.
- `swiss_universities.py` - A dictionary mapping of swiss universities to OpenAlex IDs.

##### Starter Notebooks
- `openalex_first_analyses.ipynb` - Initial analyses of bibliometric data from OpenAlex.
- `openaire_first_analyses.ipynb` - Initial analyses of bibliometric data from OpenAIRE.
- `openalex_oa_analyses.ipynb` - Analysis of Open Access (OA) published article trends using OpenAlex.
- `openaire_oa_analyses.ipynb` - Analysis of Open Access (OA) published article trends using OpenAIRE.

##### Advanced Notebooks
- `openalex_language_distr_single_institutions.ipynb` - Analysis of non-English articles published by a selected institution.
- `openalex_language_distr_multi_institutions.ipynb` - Analysis of non-English articles across Swiss HEIs.
- `openalex_research_domains_nonenglish.ipynb` - Analysis of the research domain distribution of non-English articles.
- `openalex_landing_page_domains.ipynb` - Analysis of the most frequent landing page domains and prefixes across Swiss HEIs.

## Getting Started

### Prerequisites
Ensure you have Python installed (preferably version 3.8+). 

We recommend using a virtual environment to manage dependencies.

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/eth-library/tobi-portfolio
   ```
2. Create a virtual environment and activate it:
   ```bash
   python -m venv venv  # Create a virtual environment
   source venv/bin/activate  # Activate on macOS/Linux
   venv\Scripts\activate  # Activate on Windows
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Running the Notebooks
Launch Jupyter Notebook and open the desired `.ipynb` file:
   ```bash
   jupyter notebook
   ```
Or **open the Notebook file in your IDE.**

## Contributions
Contributions are welcome! If you find issues or want to suggest improvements, please open an issue or [send us an E-Mail](mailto:bibliometrics@library.ethz.ch).

## License
>Disclaimer: The exclusive right of use and the exclusive exploitation rights of the software belong to ETH Zurich ([Federal Act on the Federal Institutes of Technology, Art. 36, para. 2]( https://www.admin.ch/opc/en/classified-compilation/19910256/index.html#a36)). 

We are in the process of registering the software under an Open Source License. 

## Contributors

- Elisabeth Giryes 

   [<img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"/>](https://github.com/liuzzle)

- Simon Willemin 

   [<img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"/>](https://github.com/swillemin-eth)

- Dr. Julian Dederke 

   [<img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"/>](https://github.com/dederkej)
  
- Dr. Teresa Kubacka

## About TOBI
Towards Open Bibliometric Indicators (TOBI) is a project co-founded by the ETH Library and swissuniversities within the Open Science Program. 
> More on the **TOBI Website**: https://eth-library.github.io/tobi/ 


