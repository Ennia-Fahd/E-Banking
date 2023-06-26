![NewCustomer](https://github.com/Ennia-Fahd/E-Banking/assets/92646945/31d41703-f0b7-478f-b184-82bfa5fd26c8)# E-Banking
1- Architecture : 

![architecture](https://github.com/Ennia-Fahd/E-Banking/assets/92646945/ee8362fb-1f27-4758-92bf-60ce58ab721d)

L'architecture d'un projet Digital Banking avec Spring et Angular implique une interaction entre les différentes couches. Le frontend Angular communique avec le backend Java via des requêtes HTTP pour accéder aux fonctionnalités et aux données métier. Le backend utilise des entités, des repositories et des services pour gérer la logique métier et interagir avec la base de données. Les DTOs et les mappers facilitent l'échange de données entre le backend et le frontend. En résumé, le frontend envoie des requêtes au backend, qui les traite en utilisant ses services et repositories, puis renvoie une réponse au frontend. Cette architecture permet une séparation claire des responsabilités et facilite le développement d'une application bancaire numérique.

2- Les interfaces de l'application :

--> Interface Customers :

![Customers](https://github.com/Ennia-Fahd/E-Banking/assets/92646945/193796fc-8001-49fe-a213-b810ab6c041f)

--> Interface Save Customer :

![NewCustomer](https://github.com/Ennia-Fahd/E-Banking/assets/92646945/4c9a556a-20a7-45e3-b8aa-2ca961e166ca)

--> Interface Account :

![AccountCustomer](https://github.com/Ennia-Fahd/E-Banking/assets/92646945/1600d821-d043-4b9a-9373-ef0455853799)

--> Interface Operations :

![Operations](https://github.com/Ennia-Fahd/E-Banking/assets/92646945/1b59e993-4dda-457b-ace1-370829eafe4e)
![Operations2](https://github.com/Ennia-Fahd/E-Banking/assets/92646945/bf82e5a8-8b61-487d-8c37-194343d4ffa7)

Serveur BACKEND 

1-Structure du projet :
![structureprojetbackend](https://github.com/Ennia-Fahd/E-Banking/assets/92646945/bc4f34b9-5cd2-4e92-95f6-762dd5528bdf)

-Entities (Entités) : Les entités représentent les objets métier de l'application et sont utilisées pour représenter les tables de la base de données. Elles contiennent des attributs et des relations qui décrivent les données de l'application.

-Repositories (Répertoires) : Les repositories sont utilisés pour l'accès aux données. Ils fournissent des méthodes permettant d'effectuer des opérations CRUD (Create, Read, Update, Delete) sur les entités, facilitant ainsi l'interaction avec la base de données.

-DTOs (Data Transfer Objects) : Les DTOs sont utilisés pour transférer des données entre les différentes couches de l'application. Ils permettent de structurer et de transférer uniquement les données nécessaires, améliorant ainsi les performances et la sécurité.

-Mappers (Mappateurs) : Les mappers sont utilisés pour convertir les objets entre différentes représentations, par exemple entre les entités et les DTOs. Ils facilitent la transformation des données en effectuant des opérations de mapping appropriées.

-Web : La couche Web fournit des composants tels que les RestControllers qui exposent les fonctionnalités de l'application via des API REST. Elle gère les requêtes HTTP entrantes et renvoie les réponses appropriées.

-Service : La couche de service contient la logique métier de l'application. Elle traite les opérations complexes, effectue des validations, coordonne l'interaction entre les différentes entités et gère les transactions.

-Exception : Les exceptions sont utilisées pour gérer les erreurs et les situations exceptionnelles dans l'application. Elles permettent de gérer les cas d'échec, d'erreur de validation ou toute autre situation qui nécessite une gestion particulière.

2- Composants :

-->Entities : 

![Customer](https://github.com/Ennia-Fahd/E-Banking/assets/92646945/8dc16693-291e-481e-8272-87b77296bcc8)
![BankAcocuntEntity](https://github.com/Ennia-Fahd/E-Banking/assets/92646945/177c42cb-be9d-4b00-bd6b-fbca6751b375)
![SavingAccount](https://github.com/Ennia-Fahd/E-Banking/assets/92646945/f94d4a53-0496-4eef-b4a0-262c617399cb)
![CurrentAccount](https://github.com/Ennia-Fahd/E-Banking/assets/92646945/6a26b648-94fc-4970-b67f-9b2df5d2a526)
![AccountOperationEntity](https://github.com/Ennia-Fahd/E-Banking/assets/92646945/e3688f16-484e-4648-bb2c-cb8ecba18b0d)

-->Enumérations :

![OperationType](https://github.com/Ennia-Fahd/E-Banking/assets/92646945/72034e64-c43e-46a6-a65f-2c0b5babac5d)
![AccountStatut](https://github.com/Ennia-Fahd/E-Banking/assets/92646945/bbb4b34a-2b12-4165-9ff0-0cfc7869fac1)

-->Repositories :

![CustomerRep](https://github.com/Ennia-Fahd/E-Banking/assets/92646945/4b636553-3f77-4c9a-829e-eb5dd8ebf0c0)
![BankAccountRep](https://github.com/Ennia-Fahd/E-Banking/assets/92646945/d6ee0161-3589-48e2-b160-a2c936f88358)
![AccountOperationRep](https://github.com/Ennia-Fahd/E-Banking/assets/92646945/8c81c981-f478-4637-bd75-59090f721741)





























