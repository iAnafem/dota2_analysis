## Task description.

I decided to do some analysis of the very popular computer game Dota2. </br>
(You can see Dota2 description here https://en.wikipedia.org/wiki/Dota_2)

### Stage 1. Data search and data exploration.

To obtain data for analysis I used a quite popular among analytics and data scientists 
website:  https://www.kaggle.com/

I chose this dataset: https://www.kaggle.com/devinanzelmo/dota-2-matches </br>
From the link above you can explore the general information about all the datasets, represented 
on that page. 
For the analysis we will need the next ones (click Download button from each link to store files):
- match.csv https://www.kaggle.com/devinanzelmo/dota-2-matches?select=match.csv
- players.csv https://www.kaggle.com/devinanzelmo/dota-2-matches?select=players.csv
- hero_names.csv https://www.kaggle.com/devinanzelmo/dota-2-matches?select=hero_names.csv

You need to sign in to Kaggle. You can do it via Google account or any other Social accounts.
(IMPORTANT: If you don't want to sign in to Kaggle, please, contact me, and I will add csv files to repository)

 
I intentionally did not provide the detail information about these datasets, 
because all the information including fields description with its types is represented
on the links above (Kaggle magic!). I don't see any sense to duplicate this information here.


To explore Stages 2 and 3 you need: 
1. Clone this repository:</br>
```clone
git clone https://github.com/iAnafem/dota2_analysis.git && cd dota2_analysis
```
2. Download the datasets specified above and place them inside the directory of cloned repository. </br> The 
3. Unzip match and players datasets. On Ubuntu you can do this by launch the next commands
from the terminal:
```console
sudo apt-get install unzip
unzip match.csv.zip -d .
unzip players.csv.zip -d .
rm match.csv.zip
rm players.csv.zip
```

The final files tree should look like this:
```
dota2_analysis/
|   .gitignore
|   hero_names.csv
|   main.ipynb
|   match.csv
|   players.csv
│   README.md
```
4. Run jupyter notebook, open main.ipynb notebook and run the whole notebook. 
You need to install jupyter, if you don't have it: https://jupyter.org/install
```console
jupyter notebook
```
Have I nice day!