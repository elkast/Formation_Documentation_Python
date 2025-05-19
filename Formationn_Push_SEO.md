Semaine 1 : Python & Flask Fondamentaux

Jour 1 : Python Basics (Variables, Boucles, Fonctions)

Python Basics

Parler de python pour les debutant parait complexe mais vous verrez que cela est tres simple a comprendre voici les elemnts a comprendre

Variables : Stockent des données (ex: x = 10).
Types de données : int, float, str, bool, list, dict, etc.
Opérateurs : +, -, *, /, ==, !=, etc., pour calculs et comparaisons.
Conditions : if, elif, else pour exécuter du code sous conditions.
Boucles : for (itération sur séquences) et while (tant qu’une condition est vraie).
Fonctions : Blocs réutilisables définis par def nom_fonction():.
Listes : Collections modifiables [1, 2, 3].
Dictionnaires : Paires clé-valeur {"clé": "valeur"}.
Modules : Fichiers Python réutilisables (import module).
Expliquons cela de manniere claire :

1. Variables : La boîte de stockage

Explication :
Une variable, c’est comme une boîte étiquetée où vous rangez une valeur.
👉 Exemple :

patient = "Marie Dupont" # Une boîte "patient" avec le nom "Marie Dupont"

age = 30 # Une boîte "age" avec le nombre 30

Exercice :
Créez une variable medecin avec la valeur "Dr. Smith".

medecin = "Dr. Smith"

print(medecin) # Affiche "Dr. Smith"

2. Types de données : La nature du contenu

int (nombre entier) : 3, -10 → Comme un nombre de patients.
float (nombre à virgule) : 3.14, 0.99 → Comme le poids d’un patient (70.5 kg).
str (texte) : "Bonjour" → Toujours entre guillemets.
bool (vrai/faux) : True, False → Comme "Est-ce que le patient a payé ?".
list (liste) : ["aspirine", "paracétamol"] → Comme une liste de médicaments.
dict (dictionnaire) : {"nom": "Marie", "age": 30} → Comme une fiche patient.
Devinez le type :

python

prix_consultation = 25.99 # Type ? → float

est_present = True # Type ? → bool

medicaments = ["ibuprofène"] # Type ? → list

3. Opérateurs : Les outils pour manipuler

+ - * / : Calculs simples.
total = 3 + 2 # → 5
== (égal), != (pas égal) : Comparaisons.
python

Copy

Download

age == 30 # → True si age vaut 30

Exercice :
Calculez le total de 2 consultations à 30€ chacune.

python

Copy

Download

total = 30 * 2

print(total) # → 60

4. Conditions : Décisions du quotidien

Explication :
Comme un panneau "Si route mouillée, ralentir".

python

Copy

Download

if age >= 18:

print("Majeur")

else:

print("Mineur")

Exercice :
Si un patient a plus de 60 ans, affichez "Senior".

python

Copy

Download

age = 65

if age > 60:

print("Senior")

5. Boucles : Répéter une tâche

for : Comme dire "Pour chaque patient dans la liste, appelez-le".
python

Copy

Download

for patient in ["Marie", "Jean"]:

print("Appeler", patient)

while : "Tant que le patient ne répond pas, rappeler".
python

Copy

Download

rappels = 0

while rappels < 3:

print("Rappel", rappels)

rappels += 1

Exercice :
Affichez les numéros 1 à 3 avec une boucle for.

python

Copy

Download

for i in [1, 2, 3]:

print(i)

6. Fonctions : Recettes toutes faites

Explication :
Une fonction, c’est comme une recette de cuisine réutilisable.

python

Copy

Download

def calculer_prix(nb_consultations, prix_unitaire):

return nb_consultations * prix_unitaire

Exercice :
Créez une fonction dire_bonjour(nom) qui affiche "Bonjour [nom]".

python

Copy

Download

def dire_bonjour(nom):

print("Bonjour", nom)

dire_bonjour("Marie") # → "Bonjour Marie"

7. Listes : La liste de courses

Explication :
Une liste, c’est comme un tiroir avec des cases numérotées.

python

Copy

Download

patients = ["Marie", "Jean", "Sophie"]

print(patients[0]) # → "Marie" (la 1ère case)

Exercice :
Ajoutez "Paul" à la liste et affichez la 3ème case.

python

Copy

Download

patients.append("Paul")

print(patients[2]) # → "Sophie"

8. Dictionnaires : La fiche patient

Explication :
Un dictionnaire, c’est comme un formulaire avec des champs (nom, âge...).

python

Copy

Download

fiche = {"nom": "Marie", "age": 30}

print(fiche["nom"]) # → "Marie"

Exercice :
Créez un dictionnaire rdv avec "date" et "medecin".

python

Copy

Download

rdv = {"date": "2023-10-01", "medecin": "Dr. Smith"}