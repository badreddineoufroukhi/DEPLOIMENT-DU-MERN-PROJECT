# DEPLOIMENT DU MERN PROJECT

## I. Les plateformes qu’on peut utiliser

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

1. Inactivité et Mise en Veille

- **Problème** : Si le CRM reste inactif pendant 15 minutes, Render met l'application en veille, ce qui arrête temporairement le serveur.

- **Impact** : Lorsqu'un utilisateur tente de se reconnecter après la mise en veille, un temps de démarrage (jusqu'à 1 minute) est nécessaire pour redémarrer l'application.

2. Quotas d'Utilisation

- **Heures de fonctionnement** : 750 heures par mois, ce qui permet un fonctionnement continu jusqu'à épuisement du quota.

- **Bande passante** : Limites sur la quantité de données envoyées, mais suffisantes pour un petit projet.

3. Base de Données - MongoDB Atlas

Le CRM utilise MongoDB Atlas comme base de données pour stocker les informations des utilisateurs et des interactions.
- MongoDB Atlas offre un plan gratuit avec 512 Mo de stockage. Ce plan est parfait pour des petits projets, comme un CRM, et permet de gérer tes données dans le cloud.
- Tu peux connecter ta base de données MongoDB Atlas à ton backend Node.js déployé sur Render, ce qui fait fonctionner ton CRM avec une base de données en ligne.
![image](https://github.com/user-attachments/assets/47b743f6-f4ad-4a3c-8ff4-9c73a798e41a)

