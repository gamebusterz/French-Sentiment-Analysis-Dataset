# French-Sentiment-Analysis-Dataset
A collection of over 1.5 Million tweets data translated to French, with their sentiment.  

The data has two columns, _polarity_ and _status_   

| polarity | status |
|----------|--------|
|0|- Awww, c'est un bummer. Tu devrais avoir david carr du troisième jour pour le faire. ;ré|
|0|J'ai plongé plusieurs fois pour la balle. A réussi à économiser 50% le reste sort de limites|
|4|Êtes-vous prêt pour votre mojo makeover? Demandez-moi des détails|
|4|Joyeux 38ème anniversaire à mon livre de tous les temps !!! Tupac amaru shakur|  

The __@__ and __#__ (usernames and hashtags) have been removed from the data.  
The polarity __0__ denotes a Negative sentiment and __4__ denotes a Positive segment. 

## Usage  
The files have been split,so to use the dataset, you'll have to combine them first by running: 
`cat x* > tweets.csv` after downloading all these files to a directory.
