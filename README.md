# Réseau social d'entreprise

## Commencer

`git clone git@github.com:gylgyl2000/GillesChassignet_7_01072021.git`

### Frontend :

```
cd frontend
npm install 
npm run serve
```

### Backend :

```
cd backend
npm install
npm start
```

### Database :

Assurez-vous que `MySQL` est installé globalement

```
cd backend
```

Vous devrez vérifier que le nom d'utilisateur et le mot de passe dans le fichier **config**/*database.json* correspondent à vos informations d'identification MySQL locales.

```
npx sequelize-cli db:create
npx sequelize-cli db:migrate
```

Ensuite, ouvrez sur n'importe quel navigateur Web : http://localhost:8080/

## API documentation

https://documenter.getpostman.com/view/13023621/TVt2e4h6

## Quel est ce projet ?

J'ai créé un réseau social d'entreprise, pour une entreprise fictive. Pour ce projet, j'ai utilisé les technologies ci-dessous :
- Pour le serveur : Node.js et le framework Express
- Pour la base de données : le langage MySQL et Sequelize ORM
- Pour le front-end : Vue.js (Vue Router, Vuex), Sass, Bootsrap et BootsrapVue

## Qu'ai-je appris ?

Ce projet m'a permis d'appliquer toutes mes connaissances backend et frontend au développement d'une application complète à partir de zéro.

