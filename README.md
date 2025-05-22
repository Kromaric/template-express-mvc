# 🛠️ Express MVC Template

Un template de base pour démarrer rapidement un projet Node.js avec Express et une architecture MVC (Model - View - Controller).

## 🚀 Fonctionnalités

- Structure MVC claire
- Express configuré
- Middleware de base
- Organisation modulaire du code
- Prêt pour le développement RESTful API

## 🗂️ Arborescence du projet

├── controllers/ 
├── models/ 
├── functions/ 
├── routes/ 
├── views/ 
├── tests/ 



## ⚙️ Installation

```bash
# Clone le projet
git clone https://github.com/Kromaric/template-express-mvc.git

# Va dans le dossier
cd template-express-mvc

# Installe les dépendances
npm install

# Créer la base de données
npx sequelize-cli db:create
Appliquer les migrations
npx sequelize-cli db:migrate

# Lancer le projet
npm start
npm run start       # Démarrer l'app
npm run dev         # Démarrer avec nodemon
