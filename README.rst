Extract academic citations from Wikipedia
=========================================
This project contains a utility for extracting academic citation identifiers.

``pip install git+https://github.com/qamilnowak/python-mwcites``

Usage
-----
In the folder with the Wikipedia dump files run the command:
::
    $ mwcitations extract enwiki-20180401-pages-meta-history*.xml*.bz2 > citations.tsv 
    
Documentation
-------------
Documentation is provided ``$ mwcitations extract -h``.
