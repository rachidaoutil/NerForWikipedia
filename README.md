# NerForWikipedia
Ner models applied on a multiple english articles in Wikipedia

Notre travail pour améliorer les performances de NER en fournissant une ressource de formation facilement mise à jour apparaît dans le
dans le contexte de recherches récentes sur l'avancement du NER et l'utilisation de Wikipédia comme ressource informatique. Contrairement à la plupart des publications sur les NER, nous considérons le corpus de formation comme une variable expérimentale, ce qui a conduit au développement d'outils d'analyse et de comparaison des corpus de formation.
d'outils d'analyse et de comparaison des corpus de formation, ce qui a également permis de comprendre les faibles performances des corpus de référence lorsqu'ils sont évalués les uns par rapport aux autres.
Nous avons constaté que notre approche de base pour transformer les liens Wikipedia en annotations NE, nos résultats expérimentaux démontrent la viabilité de la dérivation automatique d'énormes corpus d'annotations d'entités nommées.
corpus d'annotation d'entités nommées à partir de Wikipédia.


Objectifs :
-	extraction d'entités dans Wikipédia

Data-sets choisies :
WikiANN (parfois appelé PAN-X) est un jeu de données multilingue de reconnaissance d'entités nommées constitué d'articles de Wikipédia annotés avec des balises LOC (localisation), PER (personne) et ORG (organisation) au format IOB2. Cette version correspond aux divisions équilibrées train, dev et test de Rahimi et al. (2019), qui prend en charge 176 des 282 langues du corpus original WikiANN.liens des data-sets :

Homepage:  https://github.com/afshinrahimi/mmner

Dataset:  https://github.com/huggingface/datasets/blob/master/datasets/wikiann/wikiann.py

