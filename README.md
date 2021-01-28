# Projet BIGDATA
***
Dans ce projet en à eu une dataset sur des communications entre différentes hote, il contient des informations sur chaque session établie  entre deux ordinateurs, et nous en est soncé de répendre au éxigence donner dans le fichier projetBigData.pdf

## Technologies
***
A list of technologies used within the project:
* [Spark](https://archive.apache.org/dist/spark/spark-2.3.0/spark-2.3.0-bin-hadoop2.7.tgz): Version 2.3.0
* [openjdk]: Version 1.8.0_275

# Partie I
## Question 1

***
Voici la commande qui permet de donner pour chaque paramétre sont type
# ![Alt text](./capture/partie1/Q1.PNG?raw=true "Title") 

## Question 2
***
Pour chaque colonne de type catégorie (STRING), calculez le nombre d'occurrences
***
### ordinateur source
# ![Alt text](./capture/partie1/Q2-1.PNG?raw=true "Title") 


***
### Port source
# ![Alt text](./capture/partie1/Q2-2.PNG?raw=true "Title") 
***
### ordinateur destination
# ![Alt text](./capture/partie1/Q2-3.PNG?raw=true "Title") 

***
### Port destination
# ![Alt text](./capture/partie1/Q2-4.PNG?raw=true "Title") 

***
### Protocol
# ![Alt text](./capture/partie1/Q2-5.PNG?raw=true "Title") 

## Question 3
***
Pour les colonnes de type numérique (INTEGER), calculez la moyenne (mean), somme
("sum"), minimum (min), maximum (max).

### La durée
# ![Alt text](./capture/partie1/Q3-1.PNG?raw=true "Title")

***
### Le nombre de paquets
# ![Alt text](./capture/partie1/Q3-2.PNG?raw=true "Title")

***
### Le nombre d'octets
# ![Alt text](./capture/partie1/Q3-3.PNG?raw=true "Title")

## Question 4

Fixer une fenêtre temporelle à 5 minutes pour calculer la question 2 et 3.

***
### ordinateur source
# ![Alt text](./capture/partie1/Q4-1.PNG?raw=true "Title") 


***
### Port source
# ![Alt text](./capture/partie1/Q4-2.PNG?raw=true "Title") 
***
### ordinateur destination
# ![Alt text](./capture/partie1/Q4-3.PNG?raw=true "Title") 

***
### Port destination
# ![Alt text](./capture/partie1/Q4-4.PNG?raw=true "Title") 

***
### Protocol
# ![Alt text](./capture/partie1/Q4-5.PNG?raw=true "Title") 

***
### La durée
# ![Alt text](./capture/partie1/Q4-6.PNG?raw=true "Title")

***
### Le nombre de paquets
# ![Alt text](./capture/partie1/Q4-7.PNG?raw=true "Title")

***
### Le nombre d'octets
# ![Alt text](./capture/partie1/Q4-8.PNG?raw=true "Title")


## Question 5
Pour chaque ordinateur source, calculez le nombre (count), la moyenne, (mean),
somme ("sum"), minimum (min), maximum (max) des restes des colonnes numé-
riques.

***
### La durée
# ![Alt text](./capture/partie1/Q5-1.PNG?raw=true "Title")

***
### Le nombre de paquets
# ![Alt text](./capture/partie1/Q5-2.PNG?raw=true "Title")

***
### Le nombre d'octets
# ![Alt text](./capture/partie1/Q5-3.PNG?raw=true "Title")


## Question 6
Pour chaque ordinateur source, calculez le nombre d'occurrences des restes des colonnes
catégoriques (STRING).

***
### Port source
# ![Alt text](./capture/partie1/Q6-1.PNG?raw=true "Title") 
***
### ordinateur destination
# ![Alt text](./capture/partie1/Q6-2.PNG?raw=true "Title") 

***
### Port destination
# ![Alt text](./capture/partie1/Q6-3.PNG?raw=true "Title") 

***
### Protocol
# ![Alt text](./capture/partie1/Q6-4.PNG?raw=true "Title") 

## Question 8
Fixer une fenêtre temporelle à 5 minutes pour calculer la question 5 et 6.

***
### La durée
# ![Alt text](./capture/partie1/Q8-1.PNG?raw=true "Title")

***
### Le nombre de paquets
# ![Alt text](./capture/partie1/Q8-2.PNG?raw=true "Title")

***
### Le nombre d'octets
# ![Alt text](./capture/partie1/Q8-3.PNG?raw=true "Title")


***
### Port source
# ![Alt text](./capture/partie1/Q8-4.PNG?raw=true "Title") 
***
### ordinateur destination
# ![Alt text](./capture/partie1/Q8-5.PNG?raw=true "Title") 

***
### Port destination
# ![Alt text](./capture/partie1/Q8-6.PNG?raw=true "Title") 

***
### Protocol
# ![Alt text](./capture/partie1/Q8-7.PNG?raw=true "Title") 

# Partie II
***
## Question 1
Calculez le nombre de connexion d'un ordinateur source vers un ordinateur destination.
***
# ![Alt text](./capture/partie2/Q1.PNG?raw=true "Title") 

***
## Question 2
Calculez le nombre d'occurrences des colonnes catégoriques (STRING) pour chaque
connexion d'un ordinateur source vers un ordinateur destination.
***
### Protocol
# ![Alt text](./capture/partie2/Q2.PNG?raw=true "Title")

***
### Port source
# ![Alt text](./capture/partie2/Q2-2.PNG?raw=true "Title")

***
### Port destination
# ![Alt text](./capture/partie2/Q2-3.PNG?raw=true "Title")


# Partie III
***
Ce résultat et pour un seule paramétre donc la premiére itération
# ![Alt text](./capture/partie3/Q1.PNG?raw=true "Title")

# Partie IV
***
Cette partie consiste à faire la Partie III pour une période temporelle xée au préalable.
Exemple d'une taille de fenêtres est de 60 secondes.
***
Ce résultat et pour un seule paramétre donc la premiére itération
# ![Alt text](./capture/partie4/c1.PNG?raw=true "Title")


# Partie V





