# SQL-ChatGPT

##Créer une table

Pour créer une table de données en SQL, tu dois utiliser la commande CREATE TABLE. Voici un exemple de syntaxe :

'''
CREATE TABLE nom_de_la_table (
   colonne1 nom_de_domaine1 contraintes,
   colonne2 nom_de_domaine2 contraintes,
   colonne3 nom_de_domaine3 contraintes,
   ...
);
'''

Le nom de la table et le nom de chaque colonne doivent être spécifiés. Tu peux également spécifier le type de données (par exemple, INT, VARCHAR, DATE) de chaque colonne avec le nom de domaine. Enfin, tu peux ajouter des contraintes comme NOT NULL pour spécifier que la colonne ne peut pas être vide.

Par exemple, voici comment créer une table appelée personnes avec des colonnes 'id', 'nom' et 'âge' :

'''
CREATE TABLE personnes (
   id INT NOT NULL,
   nom VARCHAR(255) NOT NULL,
   age INT NOT NULL
);
'''
Cela créera une table avec trois colonnes : id sera un entier non null, nom sera une chaîne de caractères de longueur maximale 255 non null, et age sera un entier non null.
