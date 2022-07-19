# Project Name
### Berlin bike thief prediction

## Table of Contents
* [General Info](#general-information)
* [Dataset](#dataset)
* [Technology stack](#technology_stack)
* [Project Status](#project-status)
* [Room for Improvement](#room-for-improvement)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)
<!-- * [License](#license) -->


## General Information
Prediction bikes thief crimes in Berlin using Machine Learning Models.

## Dataset
The dataset is available in a csv file [link](https://daten.berlin.de/datensaetze/fahrraddiebstahl-berlin).

Dataset contain information about bike thief in Berlin since 01/01/2021 and are regulary updated.


#### 1) Dataset contain information


ANGELEGT_AM – Record date = record date for each crime

TATZEIT_ANFANG_DATUM – Crime stealing date = date when crime happen

TATZEIT_ANFANG_STUNDE – Stealing hour – hour when crime happen

TATZEIT_ENDE_DATUM – Report stealing date = date when crime was report to police

TATZEIT_ENDE_STUNDE – Report stealing hour = hour when crime was report to police

LOR – Berlin code area = 8 or less digit number for Berlin area identification

SCHADENSHOEHE  = Bike value (€)

VERSUCH  = Unsuccesful_attempt
- Yes = crime doesn’t happen
- No – crime happen
- Unknown

ART_DES_FAHRRADS – Bike type

DELIKT – Crime type 
- Ahrraddiebstahl = Thieft
- Keller- und Bodeneinbruch = Break-in

ERFASSUNGSGRUND = Crime reason four category:
- Sonstiger schwerer Diebstahl von Fahrrädern = Aggravated theft
- Einfacher Diebstahl von Fahrrädern = Thieft
- Sonstiger schwerer Diebstahl in/aus Keller/Boden von Fahrrädern  =  Aggravated theft from basement/floor
- Einfacher Diebstahl aus Keller/Boden von Fahrrädern" = Theft from basement/floor

Aggrevated theft = theft with break-in, theft with robbery (aggressor has to use force against person or property)


#### 2) LOR dataset


LOR dataset is available in a csv file [link](https://github.com/MSI17819/Berlin_bike_theft_prediction/blob/main/Berlin_LOR_code.csv)

Berlin code area = LOR number

Administrative district = Berlin administrative district name

District – Berlin district name

Quarter – Berlin quater name

Street name – Berlin street name

#### 3) Dataset for analysis


The dataset is available in a csv file [link](https://github.com/MSI17819/Berlin_bike_theft_prediction/blob/main/Berlin_bike_thief_file_for_analysis.csv)

The dataset contains pre-processed data into a usable form.
The data set will be used in the next step of the analysis.

## Technology stack


### Computing platform


- [Miniconda environment](https://docs.conda.io/en/latest/miniconda.html)
- [Jupyter Notebook](https://jupyter.org/)
- [PyCharm](https://www.jetbrains.com/pycharm/)

### Packages for data pre-processing


- [Numpy](https://numpy.org/)
- [Pandas](https://numpy.org/)

### Machine Learning library


- [Scikit-learn](https://scikit-learn.org/stable/)

### Data visualisation library


- [Matplotlib](https://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org/)

## Project status

Project is: *in progress*

## Room for Improvement


In the future project can be improved by:
- adding more data to dataset e.g. district longitude, latitude data
- adding data about district density population
- expand dataset not only bike thief but other crimes

## Acknowledgements


## Contact


Created by *123michal86@gmail.com* - feel free to contact me!
