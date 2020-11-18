[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/27410/27410-2020-group-project-group11_-roseobacter/main)

# 27410 - Group assignment - Group 11 - [Laccase production in Roseobacter Litoralis ]

> Dear students, thank you for accepting the group assignment. Please fill in the
> requested information below and above ([Group Number] and [TITLE]) and remove this quoted part before submission (everything prepended with a >).
> Please also replace `[PUT-YOUR-REPOSITORY-HERE]` up in the first line 👆 with the name of your repository here on GitHub.
> That way someone can click on the Binder badge icon and open your project in Jupyter lab to explore it.
> For this to work you will also have to keep `requirements.txt` up to date (by running `pip freeze > requirements.txt`).
> Furthermore, this will only work if you decide to make your repository public (which you can do under Settings -> Options),
> which I would encourage you to do – up to you. A lot of good science happens out in the open these days.
> Good luck!

## Project summary (<300 words)
Describe the overall aim of your project and what you have achieved.

The goal of our project is to produce the enzyme laccase in roseobacter litoralis. Laccase is able to degrade polyethylene and is produced in a bacteria with high salt tolerance so that it can be used in ocean water. 

We were able to ....
but we didnt quite achieve.. 

## Project overview
Describe how your project is organized ...

File description:
The "Report.ipynb" file includes our report of the project
The "requirements.txt" file includes information about the Python packages that have been used 
The "Notebook.ipynb" file includes codes for building the model in carveme and the map of the model in escher
The "Roseobacter-litoralis-strain-B14.html" file includes the memote report 
The "Roseobacter-litoralis-strain-B14.xml" file includes the final model from carveme 
The "Roseobacter-litoralis-strain-B14.SBML" file includes
The "iML1515.xml" file is the E. coli model
The "all_fluxes.csv" a csv file with all the fluxes to be loaded in escher
The "carveme_model.json" is a json file with the carveme model
The "Yield_Comparition.ipynb" file includes adding the laccase reaction to the model and comparison of the production of laccase in E. coli and R. litoralis

## Description of our work process

We started by using carveme to create a draft reconstruction of roseobacter litoralis strain B14 from the genome database in NCBI and
gapfilled it with LB Medium. 

Next, we loaded the model with cobrapy and used escher to draw a pathway map of the central carbon metabolism. We will use this map and add reactions later on during the project.. 

We researched the amino acid composition of laccase and added a reaction to our model which consumes these amino acids. 

As a next step, we compared our maximal growth rate to the one found in the literature and we saw that our growth rate is much higher than the value found in the literature (0.69 compared to 0.27). This is why we reduced the carbon sources until we got a growth rate comparable to the literature value.
Other than that, we were not able to find more literature data like fluxes for example. 


Afterwards, we checked if our model is able to grow or not grow on the same carbon and nitrogen sources and in the same medium as found by the literature. 

Next: -further experimnets to improve the model, if model is good enough; look at laccase production pathway and improve the fluxes in this direction. 
-Use memote 

All this a to be found in the notebook file in this repository. 