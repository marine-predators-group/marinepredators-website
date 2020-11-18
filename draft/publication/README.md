This directory was generated following these instructions:

To update/populate publications with we are using https://github.com/sourcethemes/academic-admin.
If not installed-- create a conda environment and run: pip3 install -U academic. When installed you can run: academic import --bibtex static/pubs/publications.bib
This will populate the /content/publication/ folder with a folder for each new publication. Please check the index.md within that folder to check key words, abstract, etc.

Found here: https://github.com/AlexanderLabWHOI/academic-kickstart

This framework is meant for academic not syna so some changes are required. I followed the schema outlined on the syna demo page for the table of fragments. Ultimately, may not be an aesthetically pleasing way to go but was very simple to convert a .bib to directories that, with little modification, can be served as a webpage using a series of .md pages.