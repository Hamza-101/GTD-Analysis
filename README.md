# GTD-Analysis
A data science centered, semester project on Global Terrorism Database(GTD).

# Overview


## Project Phases:
1. Ideation
2. Exploratory Data Analysis
3. ML Model Design or Selection
4. Model Deployment


# Datasets

## Primary Dataset:
[Global Terroism Dataset](https://www.start.umd.edu/gtd/)™ (GTD) is an open-source database including information on terrorist events around the world from 1970 through 2020
(with annual updates planned for the future). Unlike many other event databases, the GTD includes systematic data on domestic as well as international terrorist incidents that have occurred during this time period and now includes more than 200,000 cases.

#### Data collection methodology(cookbook): https://www.start.umd.edu/gtd/downloads/Codebook.pdf

#### Download Dataset: https://www.start.umd.edu/gtd/contact/download
> Fill in the form and get access on email.

### Dataset Features
1) Unique Event ID
1) Date 
3) Country | State/Province | City
4) Target | Target Type
5) Type of Attack(s)
6) Longitude and Latitude Location
7) Vitim(s) Name
8) Weapon Used
   
> Many other features, total around ~135, it would be too wordy to list them all here. Read the cookbook, too long for me lol, exploring the dataset files would make you understand it better.


## Secondary Dataset:
Another dataset, [OnWar.com](https://onwar.com/chronology/index.html) was used for analysis of wars and their time periods aound the world. We further incorporated our findings into our "" case study.



# Exploratory Data Analysis
## Case Studies(Subject to change and add justification):
1) Total Attacks over the year (Use some unique plots)
2) Total Attacks by country (Heat map)
3) Total Attacks by country (Top 10)
4) Cities with Most deaths (Top 10)
5) Cities with Most Attacks (Top 10)
6) Types of Terror Attacks (Numbers) Exlposives, Firearms, Flamables, Biological, Chemical, Knives/Swords(Find a category), )
7) Types of Terror Attacks (Continent/country)
8) Targets Hit (Military + Police vs Civilians)
9) Targets Hit (Healtcare, Religious, Security Forces, Education and Residential)
10) Attacks by group
11) Number of Attacks by Religious vs Unaffiliated vs Random
12) Terrorist groups by country
13) Top 5 terrorist group and their attacks (Map) [Card of info]
14) War overlap with terrorist attacks (Matplotlib animation)
15) Killings over 1000, attacks + Reasoning, Actions taken
16) Suicide Attacks



# Model
(To be decided)



# File Details
AnalysisNotebook.ipynb > Exploratory Data Analysis portion

AllTerroristGroups.csv > All group names in the dataset and number of attacks



# Technologies Used
### Python 3.11
### Jupyter Notebook
### Gradio
### Azure
