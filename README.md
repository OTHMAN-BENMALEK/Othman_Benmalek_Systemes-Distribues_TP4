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

Ajout du component dashboard :

![4-1)Ajout du dashboard](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribues_TP4/assets/159661363/c2a2d453-8c44-43fb-a1e2-32f8a8a8ba79)

Résultat :

![4-2)Résultat](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribues_TP4/assets/159661363/47843b6a-25bc-432d-b200-4749266006b8)

L'ajout de app-errors pour gérer les erreurs . Dans ce test ,nous avons arrété le json-server pour qu'on puisse voir l'erreur :

![5)Ajouter app-errors , et arreter json server et voir le resultat](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribues_TP4/assets/159661363/aa7acd46-d40f-4598-9eee-be04f6b8f1dc)

Rendre la connexion un peu lent pour voir le spinner de chargement des produits : 

![6)slow connection so we can see the spinned](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribues_TP4/assets/159661363/a1967435-5b10-4bbc-819f-7306331297f1)


### Part 4

Ajout du component login:

![1)Ajout du component login ](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribues_TP4/assets/159661363/5fc90d6f-29d2-433c-968f-af57b82116f9)


Ajout de auth service pour gérer le login avec l'utilisation de btoa pour encoder le mot de pass et atob pour décoder le mot de passe :

![1-1)Ajout de auth service pour gérer le login](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribues_TP4/assets/159661363/e096d50b-c10a-4cea-8d25-d7cdb2f6a51a)

Essai de s'authentifier avec des  mauvais credentiels:

![1-2)Essai de s'authentifier avec des  mauvais credentiels ](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribues_TP4/assets/159661363/648ef673-1524-45fa-9927-57f1c26acaeb)

Ajoutons les guards , et essayons quand un user essaie de ajouter un nouveau produit:

![2)Ajoutons les guards , et essayons quand un user essaie de ajouter un nouveau produit](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribues_TP4/assets/159661363/2b7cbad7-c069-4011-9f4a-d6c1cb623a3f)

Derniere vue d'admin:

![3-1)Derniere vue d'admin](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribues_TP4/assets/159661363/7b40b0e0-9461-41a2-8a01-49fafad775ab)

Dernière vue du user1:

![3-2)Dernière vue du user1](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribues_TP4/assets/159661363/51feb5f9-0e91-4845-a616-bdd0cfade506)



## Troisième Partie : Spring Angular
### Back-end

Créer un projet avec la structure suivante et les étudiants et payments:

![1)Créer un projet avec la structure suivante et les étudiants et payments](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribues_TP4/assets/159661363/b5431078-ea82-44a1-8f9e-d395996d0727)

Test des Urls:

![2-1)Test des Url ](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribues_TP4/assets/159661363/ee0d8b5f-b70a-4d86-818f-14b6992e7cd7)

Par code d'étudiant :

![2-2)By students code](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribues_TP4/assets/159661363/fc35bd1e-96b9-42d2-bd75-5cdee1c91ab3)

Les payments :

![2-3)Payments](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribues_TP4/assets/159661363/7975b504-5358-480a-93bc-68278f172e1c)

Ajout du dependance openapi de spring , donne le résultat suivant:

![3)Ajout du dependance openapi de spring , donne le résultat suivant ](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribues_TP4/assets/159661363/832d1904-0944-4ebd-b338-2e7449c3977b)

Changer le status d'un student avec Put:

![3-1)Changer le status d'un student avec Put](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribues_TP4/assets/159661363/072f3a79-7682-4b96-8467-080c581e1b4f)

Enregistrer un nouveau payement et un pdf :

![3-2)Save New Payment + pdf file ](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribues_TP4/assets/159661363/b4e78c4c-b680-46b0-bdb0-b3fee57d8ea3)

Le fichier pdf est stocké :

![3-3)Le fichier pdf est stocké](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribues_TP4/assets/159661363/554b010b-d6e8-4029-966c-19c64a6f99e8)

Visualisation du fichier pdf en utilisant paymentFile:

![3-4)Visualiser le fichier en utilisant paymentFile](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribues_TP4/assets/159661363/8bf4b43d-5b3f-4732-93f0-035e691ead69)

h2 db students:

![4)h2 db students](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribues_TP4/assets/159661363/f22b9199-75ff-4b39-a644-2d29ec2770ef)

payments db:

![4-1)payments db ](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribues_TP4/assets/159661363/5f1ab8c5-accb-4d94-9b1c-8733c7d2326d)


### Front-end

Ajout du projet angular dans notre projet et l'ajout d'angular material :

![0)Ajouter le projet angular dans notre projet et ajouter angular,material ](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribues_TP4/assets/159661363/5414cd11-3a0f-416a-92e9-cc7d4075f388)

Nouvelle interface en utilisant angular et angular material :

![1)New interface using angular and angular material](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribues_TP4/assets/159661363/210cafc2-c963-4f5a-9075-e639616b18cc)

Création du component Login pour effectuer l'authentification :

![2-1)Login](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribues_TP4/assets/159661363/56d671a8-fafe-4582-bfdc-f0a91a602493)

Interface d'authentification :

![2-2)Interface](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribues_TP4/assets/159661363/ad028d0f-e50d-4934-aa5b-3b23105ecdda)

Authentification de l'admin :

![2-3)Admin auth](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribues_TP4/assets/159661363/4301caf3-8236-416d-b198-c1d542d21ec7)

Authentification de User1

![2-4)User1](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribues_TP4/assets/159661363/0b990e79-591f-430c-ab82-be06cc649110)

Nouvelle vue de l'user1 (ne pas afficher le menu import ) :

![2-5)Nouvelle vue de l'user1 (ne pas afficher le menu import )](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribues_TP4/assets/159661363/b1ccb997-25ca-4f8b-92ef-5ce4e10ec1b8)

Récupération des payments à partir du back-end :

![3)Récupérer les payments à partir du back-end](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribues_TP4/assets/159661363/921ab505-cf28-49b2-a00a-a22974c5ce07)

Affichage dans payments.component.html en utilisant angular material

![3-1)Les afficher dans html en utilisant angular material](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribues_TP4/assets/159661363/30eee818-8f31-4966-aad4-1984bd30718d)

Résultat :

![3-2)Résultat](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribues_TP4/assets/159661363/fba57559-cbc1-4672-bf16-424cfa6ed0a0)

Interface finale après MatPaginator et MatSort :

![4)Interface finale après MatPaginator et MatSort ](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribues_TP4/assets/159661363/21ed62d8-318e-4d36-af53-cf2b5a140b6c)


