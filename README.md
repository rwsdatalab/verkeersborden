# Workshop beeld herkenning.

[![Open In Colab Deel 1](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rwsdatalab/verkeersborden/blob/master/notebooks/deel_1_Verkeersborden_classificeren.ipynb)
[![Open In Colab Deel 2](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rwsdatalab/verkeersborden/blob/master/notebooks/deel_2_DCNN_classificeren_vervolg.ipynb)



* Tijdsduur workshop: Totaal 2uur. 25 tot 35 minuten theorie en dan tot 1.5uur hands-on gedeelte. Het hands-on gedeelte zou nog iets meer kunnen worden afhankelijk van het niveau.
* Tijd voorbereiding Workshop: Max. 1 dagdeel om zowel het theoretische en praktische gedeelte goed neer te zetten. Dus ook de laptops controleren op de werking en of de goede bestanden en meest recente update vd workshop erop staat.
* Maximaal aantal deelnemers is afhankelijk van het aantal laptops (ongeveer 20 nu).

Het doel van deze workshop is eenerzijds bekent te raken met state-of-art technieken omtrent beeldherkenning en daarnaast een beter begrip te krijgen over hoe nu precies neurale netwerken werken onder de motorkap. De workshop bestaat uit twee delen, het theoretische gedeelte waar onderwerpen uitgelegd worden zoals de werking van neurale netwerken, cost functies, backpropegation, epoch maar ook het belang van train en test sets, roc/auc scores. Het workshop gedeelte bevat een jupyter notebook waarin ge-experimenteerd kan worden in de classificatie van verkeersborden. Voor de experts is er een aanvullend gedeelte wat dieper ingaat op het gebruik van meerdere lagen in het netwerk en parameter tuning, overfitting.
Niveau: met programmeer ervaring

## Requirements 
* Zie: githubrequirements.txt

## Install
Open een terminal (ctrl+alt+t) en voer uit (regel voor regel):
 * `git clone https://git.intranet.rws.nl/Datalab/workshops/workshops/image_recognition_traffic_signs.git`
 * `git clone git@git.intranet.rws.nl:Datalab/workshops/workshops/image_recognition_traffic_signs.git`
 * `cd image_recognition_traffic_signs`
 * `conda env create -f workshop_image.yml`
 * `source activate workshop_image`
 * `jupyter notebook 1\)\ Verkeersborden\ classificeren.ipynb`

# Presentation
* 15-20 minuten presentatie over inleiding machine learning
* Beeldherkenning en de opdracht (t/m slide 10)
* Tutorial (vanaf slide 12)
* 50 min de tutorial over verkeersborden 
* Toon hoe te navigeren door een jupyter notebook

# Data (original source):
* !wget https://btsd.ethz.ch/shareddata/BelgiumTSC/BelgiumTSC_Training.zip
* !wget https://btsd.ethz.ch/shareddata/BelgiumTSC/BelgiumTSC_Testing.zip

# Check environment(s):
conda env list

# Remove environment(s):
conda env remove -n workshop_image


