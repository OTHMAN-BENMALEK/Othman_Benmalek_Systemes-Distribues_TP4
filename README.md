# Othman_Benmalek_Systemes-Distribues_TP4

## Première Partie
### Demo1
Premierement , nous avons installé NodeJs :

![0-1)Installing Nodejs](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribues_TP4/assets/159661363/5d716df9-4c1f-40d0-bd16-f5eea7d2d09d)

Après , création du premier projet Angular :

![0-2)Création du premier projet angular ](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribues_TP4/assets/159661363/e10d5ffd-f626-4383-a2a0-aa4649ed2465)

Résultat après la première commande 'ng serve' :

![0-3)ng serve the first app ](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribues_TP4/assets/159661363/570dc8a5-5548-4fd1-89f4-c594a50453d1)

Modification du fichier angular.json , pour pouvoir utiliser Bootstrap dans notre projet :

![1)pour utiliser bootstrap ](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribues_TP4/assets/159661363/3831647d-2da7-4d0a-b0de-f41ab84a2e39)

Ajout de deux boutons dans app.component.html et résultat :

![2)Ajout de deux boutons](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribues_TP4/assets/159661363/7bedf1bc-b202-424a-ab3c-1b5aa6f6a3e0)

Ajout de deux routes pour pouvoir les utiliser dans les autres components :

![3)Ajout de deux routes ](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribues_TP4/assets/159661363/42c361d5-8c68-424d-b914-2bee37741652)


Création de 4 produits dans products.component.ts 

![4-1)Création de 4 produits dans Products component ts](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribues_TP4/assets/159661363/cea9c680-6348-44dc-8803-50c5d7b0d0f0)


Modification de products.html pour afficher les produits :

![4-2)Modification de products html pour afficher les produits ](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribues_TP4/assets/159661363/6ce3ca37-c668-4845-ae67-690cf271486c)

La dernière interface après modification de design :

![last](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribues_TP4/assets/159661363/6cbf85dd-8dbe-4db6-81f9-1e7567d7d3b6)


## Deuxième Partie
### Part 1

Ajout des produits et handleCheckProduct function :

![1)Ajout des produits et check function ](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribues_TP4/assets/159661363/fbd3eaad-5897-438d-8e7c-7f63d75c12b0)

Résultat :

![1-1)Résultat](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribues_TP4/assets/159661363/58ad14cd-7d64-4672-8adc-d89273f6ef14)

Installation de Json server et creation de la DB json :

![2)Installation de Json server et creation de la DB json ](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribues_TP4/assets/159661363/a79d5829-e1e3-436c-85ec-bf582fb117aa)

Après le lancement du json-server sur le port 8088 , lorsqu'on ajoute /products , on reçoie le résultat suivant :

![2-1)local host resultat](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribues_TP4/assets/159661363/28e1ac37-a400-4ce0-94bc-d100b8a6803a)

Ajout des functions pour handle check et handle Delete pour faire des modifications dans le backend et le front end:

![3-1)Ajout des functions pour handle check et handle Delete pour faire des modifications dans le backend et le front end ](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribues_TP4/assets/159661363/f238b37c-69d5-4835-a95d-3be4e01841d6)

Message de confirmation lors de la suppression:

![3-2)Message de confirmation lors de la suppression](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribues_TP4/assets/159661363/a13860b5-35ff-4bf3-8b30-824dcfcc5ea0)

Après confirmation :

![3-3)Après confirmation ](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribues_TP4/assets/159661363/c32f53ac-c0be-48c7-b423-dac8c92f361a)

La recherche d'un produit :

![4)Searching a Product](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribues_TP4/assets/159661363/30431257-9e02-4238-9acb-b0686b6e39ee)


### Part 2

Modification de la fonctino getProducts pour qu'elle puisse prendre la réponse à partir de l'URL : 

![1-1)modifiying getProducts function to retrieve response from URL](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribues_TP4/assets/159661363/6ed15916-83cc-492c-bdff-fedcf2b42728)

Modification de getProducts pour recevoir le x-total-count pour savoir le nombre de pages (totalPages) :

![1-2)after modifications products component ts](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribues_TP4/assets/159661363/53308d37-3bad-4491-bec1-63bf4fe27b73)

On reçois sur la console le nombre de x-total-count : 

![1-3)On console](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribues_TP4/assets/159661363/1061aacb-3f0e-4299-ae9b-da47862eb7f0)

Utilisation de totalPages pour faire la pagination :

![2-1)Pagination ](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribues_TP4/assets/159661363/0557320c-7aa2-4395-8b7f-249d64fb7e6b)

Résultat de Pagination :

![2-2)Résultat de Pagination](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribues_TP4/assets/159661363/350fe84e-97d5-4667-a0ac-5f94d32dac12)

Ajout d'un nouvelle component editProduct et function update pour pouvoir modifier un produit :

![3-1)Ajout d'un nouvelle component editProduct et function update](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribues_TP4/assets/159661363/c7bcdf4a-9cae-49eb-b941-8317509d8045)

Après ajout de bouton et icone dans editProduct.html , on reçoit le résultat suivant :

![3-2)interface](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribues_TP4/assets/159661363/767cfbf2-0055-4b98-9ae3-50fe180ddae0)

lorsqu'on click sur l'edit d'un produit , on se retrouve dans le formulaire de modification et update :

![3-3)pour éditer](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribues_TP4/assets/159661363/52bd0d12-e3c4-4454-9478-cfaaa296572c)


### Part 3



### Part 4


## Troisième Partie : Spring Angular
### Back-end



### Front-end
