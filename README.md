# Analyse-de-sentiment
Traitement automatique du langage naturel.
La base de données Internet Movie Database (IMDb) est considérée le "Hello World" du traitement automatique du langage naturel. Les données d'entrée sont des critiques de film rédigées en anglais par les spectateurs. La critique est labellisée 0 si elle est négative, 1 si elle est positive. On parle alors d'analyse de sentiments. L'objectif de ce travail est d'utiliser cette base de données pour acquérir certains fondamentaux du traitement automatique du langage naturel. Pour cela, il va falloir tout d'abord construire une présentation de type Powerpoint se déroulant selon le plan suivant :

Qu'est-ce-que le traitement automatique du langage naturel ? (une diapositive)
Quelles sont ses applications ? (une diapositive)
Qu'est-ce-que l'analyse de sentiments ? (une diapositive)
Décrire la base de données IMDb (une diaposivite).
La base de données IMDb peut se charger selon deux manières :
Avec les données d'entrée stockées sous forme textuelle ;
Avec les données d'entrée stockées sous forme de suite de nombres entiers, chaque nombre entier encodant un mot. C'est cette version que nous allons utiliser dans un premier temps avec la ligne TensorFlow/Keras suivante : _(train_samples, train_labels), (test_samples, test_labels) = imdb.load_data(num_words=10000). _Décrire dans la présentation ce principe d'encodage de mots par des nombres entiers.
Cette séquence de nombres entiers peut ensuite être encodée à son tour en utilisant l'encodage One-Hot. Décrire dans la présentation ce principe.
​

Entrainer ensuite dans un Jupyter Notebook un ou plusieurs modèle(s) de Machine Learning de votre choix en utilisant la librairie scikit-learn sur les données IMDb que vous aurez encodées au format One-Hot.
