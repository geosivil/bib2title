# bib2title
A simple converter from bibtex to title in markdown and plain text format. 

# Physics Citation Converter

A lightweight, browser-based tool to convert raw BibTeX entries into formatted Plain Text or Markdown citations tailored specifically for physics journals. 

Many standard citation generators fail to format physics citations correctly (e.g., placing the year at the end). This tool fixes that, making it easy to paste from Google Scholar/arXiv and output clean text for your notes or proposals.

## Features
* **Physics Formats:** Correctly places the publication year at the end of the citation.
* **Smart Capitalization:** Respects `{B}races` in BibTeX titles to protect acronyms and specific casing (e.g., `{S}queezed light`).
* **Flexible Sources:** Handles both `@article` and `@book` entries.
* **Fully Local:** Runs 100% locally in your web browser with no dependencies.

## Supported Styles
* APS (American Physical Society)
* AIP (American Institute of Physics)
* Nature
* Science
* Optica (formerly OSA)

## How to Use
1. Open `bib2title.html` in any web browser.
2. Paste your raw BibTeX string into the input box.
3. Select your target journal style and output format (Markdown or Plain Text).
4. Toggle "Include titles" on or off.
5. Click **Copy to Clipboard**.
