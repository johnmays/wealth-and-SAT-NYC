Investigating The Relationship Between Housing Value and SAT Scores in New York City
====================================================================================
A short project exploring the relationship between housing value (as an indicator of wealth) and SAT scores (as an indicator of academic success & prospects) by ZIP code in New York City

Environment & Stack:
====================
I am using Python 3.8.9 with a list of packages that can be found in `requirements.txt <./requirements.txt>`_.  I am also using Jupyter.  I prefer to use VS Code to edit and view them.

If you would like to run this project yourself, execute the following commands in your shell:

..  code-block:: sh

    $ git clone https://github.com/johnmays/wealth-and-SAT-NYC.git
    $ cd wealth-and-SAT-NYC
    wealth-and-SAT-NYC $ pip install virtualenv
    wealth-and-SAT-NYC $ virtualenv -p < optional path to python 3.12 > .venv
    wealth-and-SAT-NYC $ source .venv/bin/activate
    (.venv) wealth-and-SAT-NYC $ pip install -r requirements.txt
    (.venv) wealth-and-SAT-NYC $ mkdir data

then, download the requisite data from the `NYC OpenData website <https://opendata.cityofnewyork.us/>`_ into the ``/data`` directory and the notebook should run!

Data:
=====
- `SAT (College Board) 2010 School Level Results OpenData Dataset <https://data.cityofnewyork.us/Education/SAT-College-Board-2010-School-Level-Results/zt9s-n5aj>`_ as **.csv**
- `NYC Citywide Annualized Calendar (Property) Sales OpenData Dataset <https://data.cityofnewyork.us/City-Government/NYC-Citywide-Annualized-Calendar-Sales-Update/w2pb-icbu>`_ as **.xls** (listed as **.csv**)
- `Modified Zip Code Tabulation Areas (MODZCTA) OpenData Dataset <https://data.cityofnewyork.us/Health/Modified-Zip-Code-Tabulation-Areas-MODZCTA-/pri4-ifjk>`_ as **.geojson**
- `2014 - 2015 DOE High School Directory OpenData Dataset <https://data.cityofnewyork.us/Education/2014-2015-DOE-High-School-Directory/n3p6-zve2>`_ as **.csv**

Results:
========
See `notebook. <./notebooks/investigation.ipynb>`_

Resources:
==========
- `NYC OpenData Database Website <https://opendata.cityofnewyork.us/>`_
- `NYC DOE School District Map Tool <https://schoolsearch.schools.nyc/>`_

Statistical Faults:
===================
See final section of `notebook <./notebooks/investigation.ipynb>`_
