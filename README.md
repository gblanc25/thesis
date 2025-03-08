## Concrete Oasis: Thesis Code Supplement
A thesis by Gabe LeBlanc '25 | gleblanc@college.harvard.edu

Advisors: Jim Waldo (Harvard Computer Science) & Adaner Usmani (Harvard Sociology)

### Files

This repository contains two .ipynb files responsible for data analysis and graph production: ``multicity_income`` and ``multicity_race``. It also contains several data folders, although the ``osm`` folder required in the code is missing due to large file sizes.

The ``boston.ipynb`` file contains the code used to generate visuals in the Introduction, though associated data files are not included here. 

### Usage

All required data for the multicity files can be obtained via the PROCESS FLOW provided in each code file; ACS data and TIGER shapefiles have already been provided. 

To produce income-related visuals found in Chapter 4, run ``multicity_income.ipynb``, and ``multicity_race.ipynb`` for Chapter 5. 

**IMPORTANT:** note where the ``num_divisions`` parameter is defined in the code; *all* visuals will be produced with that number of divisions (tertiles, quintiles, etc.). 

### Credits

I acknowledge the use of generative AI, specifically the OpenAI ChatGPT 4o model, largely for sporadic assistance with routine code production. All code was subsequently verified by me, and all written components of this thesis are my original work. 
