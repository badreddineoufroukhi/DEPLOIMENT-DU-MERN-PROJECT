# DEPLOIMENT DU MERN PROJECT

## Table des matières

1. [Les plateformes qu’on peut utiliser](#I-Les-plateformes-qu)
2. [Java Core Interview Questions - Coding Standards](#Java-Core-Interview-Questions---Coding-Standards)
3. [Java Exception Handling Interview Questions](#Java-Exception-Handling-Interview-Questions)
4. [OOP Concepts Interview Questions](#OOP-Concepts-Interview-Questions)
5. [Java Core Serialization Interview Questions](#Java-Core-Serialization-Interview-Questions)
6. [Questions d'entretien Java sur les Threads](#Questions-entretien-Java-sur-les-Threads)
7. [Questions d'entretien Java sur le Framework de Collections](#Questions-entretien-Java-sur-le-Framework-de-Collections)

---

## I. Les plateformes qu'on peut utiliser

### 1. Frontend (React)
- **Vercel ou Netlify** : Facile et rapide, ces plateformes s'occupent de tout et sont très simples à utiliser.
- **Render** : Permet d'héberger à la fois le backend et le frontend.

### 2. Backend (Node.js + Express + MongoDB)
- **Render** : Facile à utiliser, supporte MongoDB Atlas.
- **Railway.app** : Similaire à Render, avec une bonne gestion des bases de données.
- **DigitalOcean** : VPS offrant plus de contrôle sur le déploiement.
- **AWS / GCP / Azure** : Solutions complexes mais très puissantes pour un déploiement évolutif.

### 3. Base de données (MongoDB)
- **MongoDB Atlas** : La solution la plus simple pour héberger MongoDB dans le cloud.
- **Hébergement sur un VPS** : Héberger MongoDB sur DigitalOcean, AWS, GCP, ou Azure pour plus de contrôle et de flexibilité.

---

## II. La meilleure plateforme

### 🚀 Render  
-  **Gratuit** pour les petits projets.  
-  Gère **Backend** (Node.js) + **Frontend** (React) + **MongoDB Atlas**.  
-  **Facile à configurer** (déploiement avec GitHub).  
![image](https://github.com/user-attachments/assets/fd01dc04-47c3-49f0-b850-e29cf37fd661)
### 🚀 Problème de la version gratuite 

#### 1. Inactivité et Mise en Veille

- **Problème** : Si le CRM reste inactif pendant 15 minutes, Render met l'application en veille, ce qui arrête temporairement le serveur.

- **Impact** : Lorsqu'un utilisateur tente de se reconnecter après la mise en veille, un temps de démarrage (jusqu'à 1 minute) est nécessaire pour redémarrer l'application.

#### 2. Quotas d'Utilisation

- **Heures de fonctionnement** : 750 heures par mois, ce qui permet un fonctionnement continu jusqu'à épuisement du quota.

- **Bande passante** : Limites sur la quantité de données envoyées, mais suffisantes pour un petit projet.

#### 3. Base de Données - MongoDB Atlas

- Le CRM utilise MongoDB Atlas comme base de données pour stocker les informations des utilisateurs et des interactions.
- MongoDB Atlas offre un plan gratuit avec 512 Mo de stockage. Ce plan est parfait pour des petits projets, comme un CRM, et permet de gérer tes données dans le cloud.
- Tu peux connecter ta base de données MongoDB Atlas à ton backend Node.js déployé sur Render, ce qui fait fonctionner ton CRM avec une base de données en ligne.

![image](https://github.com/user-attachments/assets/e925500a-0219-490f-8805-3bec88f6f654)

---

## III. Implémentation

### 🚀 MONGODB ATLAS (https://www.mongodb.com/atlas):
•	Pour débuter avec la version gratuite de MongoDB Atlas (FREE) :

![image](https://github.com/user-attachments/assets/dac1e9f7-d79d-4274-a434-aafa64d6b86c)

•	Remplir le formulaire d'inscription ou utiliser un compte Google directement :

![image](https://github.com/user-attachments/assets/028fd44a-6481-4d21-8454-8a2c0866c71a)

•	Accepter les politiques de MongoDB :

![image](https://github.com/user-attachments/assets/eca09e05-86d5-4d97-8873-1d55de62fc0e)

•	Remplir les informations générales sur mon objectif et mon projet d'utilisation de MongoDB Atlas :

![image](https://github.com/user-attachments/assets/0ca22e26-4539-4987-8f23-7a6571b2db24)

•	Précisez le type de déploiement que vous souhaitez utiliser ainsi que le nom du cluster qui sera défini après sa création :

![image](https://github.com/user-attachments/assets/159c4771-596e-40af-b32f-b9c427d6905e)
![image](https://github.com/user-attachments/assets/b09be390-35d1-4b37-9a58-a17b8f4929d3)

•	Préciser les informations sensibles de l'utilisateur :

![image](https://github.com/user-attachments/assets/3a2f6dfe-e933-4e79-a8c5-3eee7043eee6)

•	Créer l'utilisateur avant de passer à la deuxième partie :

![image](https://github.com/user-attachments/assets/327c0a07-c0f1-42d4-9f7d-d150154aab5d)
![image](https://github.com/user-attachments/assets/7ee2234d-b975-4a3b-8129-5c1c921741a6)

•	Cela permet de lier MongoDB Compass à MongoDB Atlas

![image](https://github.com/user-attachments/assets/98db26d7-90d5-4f50-b990-5e2637677c7d)

•	Si vous avez déjà installé Compass localement

![image](https://github.com/user-attachments/assets/dfe795de-a7ba-46eb-94e8-d68236cb0fef)

•	Autrement, vous avez la possibilité de l'installer :

![image](https://github.com/user-attachments/assets/62b01eeb-1eca-440a-ae9a-cbd12f59c148)

•	Ce lien permet de connecter MongoDB Atlas à MongoDB Compass, notamment du côté backend du projet :

![image](https://github.com/user-attachments/assets/d92e7c77-9d14-4695-af98-7b920a6513ff)
![image](https://github.com/user-attachments/assets/3b39da7a-b45f-437d-b21c-64a020dafa1d)

•	Commencer à créer la base de données :

![image](https://github.com/user-attachments/assets/7364ddf3-78f3-4eb2-9fe7-458dabbc6cd8)
![image](https://github.com/user-attachments/assets/49af7541-bbc2-4354-b70b-bc5761a50fed)

•	Vous pouvez effectuer les modifications directement en ligne ou bien localement :

![image](https://github.com/user-attachments/assets/4a84a651-43d9-4c3d-b5d8-ac880b24853c)
![image](https://github.com/user-attachments/assets/93bce558-ea82-4a4e-bb85-a0f4c98136f5)

### 🚀 Créer un dépôt GitHub pour le projet afin de pouvoir gérer le code source et faciliter la collaboration :

![image](https://github.com/user-attachments/assets/23fb127e-c869-4dd5-9a88-d3aab9e5ac06)
![image](https://github.com/user-attachments/assets/48bcc45a-12b1-4288-96b6-705e2bcee53b)
![image](https://github.com/user-attachments/assets/995aebe7-dbc5-40c4-8a8e-e25e1825a825)
![image](https://github.com/user-attachments/assets/83a55a72-c3a3-4858-928f-2acc199e30ae)
![image](https://github.com/user-attachments/assets/9e7aeae1-3acc-4d6a-b627-4f5ee33e8b67)
![image](https://github.com/user-attachments/assets/0c352602-16cf-4f70-bd38-af28d001ca39)
![image](https://github.com/user-attachments/assets/fa6701d2-d080-4092-95f8-33373d4d777a)
![image](https://github.com/user-attachments/assets/b7b96c68-c2af-486b-bee9-b7b1cf7daf48)

### 🚀 RENDER

![image](https://github.com/user-attachments/assets/71c72dea-2e4d-4662-a150-e303eec351cc)

#### • Web Service (Backend)

![image](https://github.com/user-attachments/assets/d3341b6c-0d6b-4a89-ab79-2708a48854aa)
![image](https://github.com/user-attachments/assets/27f14b7e-e2a4-4bbc-afb4-6da3da9f2fbf)
![image](https://github.com/user-attachments/assets/6dc4000c-dbae-446f-b77d-49bf4d0cb546)

##### Compléter le formulaire des commandes et fournir les informations relatives au dépôt GitHub :

![image](https://github.com/user-attachments/assets/c42e331f-11ed-4abe-9d5b-fd9853804056)
![image](https://github.com/user-attachments/assets/c35a40c0-1c59-4622-8b7c-9054dc4ebd2a)
![image](https://github.com/user-attachments/assets/2cee3893-10ef-4a7d-9b35-ea9ee6c8b1d5)
![image](https://github.com/user-attachments/assets/785c5553-1058-4311-8499-cb44fe908e95)
![image](https://github.com/user-attachments/assets/da10e44b-c110-41a6-ab10-9ad4fcfdfe29)
![image](https://github.com/user-attachments/assets/549a3eeb-5b7d-4432-a37a-434de75dcada)

##### RESULTAT :

![image](https://github.com/user-attachments/assets/03fdd7ba-25ba-4835-b8dd-8f55ef300048)

##### L'URL fait référence au serveur hébergé sur la plateforme Render, accessible via HTTPS.

![image](https://github.com/user-attachments/assets/baf01e81-eef7-40bc-a7f6-eea26450d733)

==> On va changer http://localhost:5000 par L’URL dans le REPÔT FRONT  

#### •	Static Site (FRONTEND) :  

![image](https://github.com/user-attachments/assets/b8d3464f-8dfb-4c4e-b725-a5f61f5d2034)
![image](https://github.com/user-attachments/assets/48e6458d-ad62-4866-bdcd-0df5dba1b911)

##### Compléter le formulaire des commandes et fournir les informations relatives au dépôt GitHub :

![image](https://github.com/user-attachments/assets/9cfa26e5-4fc9-4fab-b80c-7b7ed9cc2af1)
![image](https://github.com/user-attachments/assets/dc3429d2-8a4d-46df-ad89-2ad7d732514d)
![image](https://github.com/user-attachments/assets/28a0e7df-1ec9-4f42-9e22-ce75b28e30e3)
![image](https://github.com/user-attachments/assets/55e9a2dc-4313-41ba-bfc3-a44433145a3a)

##### RESULTAT :

![image](https://github.com/user-attachments/assets/17af83a3-e897-4c98-8d6d-ab18852a9824)

##### Voici le lien qui vous permettra d'accéder directement au projet :

![image](https://github.com/user-attachments/assets/f0d19f34-ce82-4680-8668-0304ea51b12c)

##### Les règles de redirection et de réécriture permettent de contrôler l'acheminement des requêtes sur votre site web. Par exemple, si un utilisateur accède à une ancienne URL, vous pouvez le rediriger vers une nouvelle page. Les paramètres d'URL capturent des parties du chemin (comme des catégories ou identifiants), et les jokers permettent de rediriger plusieurs pages sous un même chemin. Ces règles sont utiles pour gérer les changements d'URL sans casser les liens existants.

![image](https://github.com/user-attachments/assets/dd697fea-51f2-439a-af9b-7d7791e60050)
