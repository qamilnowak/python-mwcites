Extract academic citations from Wikipedia
=========================================
This project contains a utility for extracting academic citation identifiers.

**NOTE:** As one of its dependencies (`Mediawiki-Utilities <https://github.com/halfak/Mediawiki-Utilities>`_) requires
Python 3 so does mwcites.

``pip install git+https://github.com/qamilnowak/python-mwcites``

Usage
-----
In the folder with the Wikipedia dump files run the command:
::
    $ mwcitations extract enwiki-20180401-pages-meta-history*.xml*.bz2 > citations.tsv 
    
Documentation
-------------
Documentation is provided ``$ mwcitations extract -h``.
