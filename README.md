### BACKEND

## Install project dependancies

npm install

## Run API

npm run run:dev

================ FR ====================

L'api est accessible sur le port `5678` en local, c'est à dire `http://localhost:5678`

## Utilisateurs par défaut:

## Administrateur :

```
utilisateur : admin@test.tld
mot de passe : admin
```

## Employé :

```
utilisateur : employee@test.tld
mot de passe : employee
```

================ EN ====================

The API is locally available on port `5678`, go to `http://localhost:5678`

## Default user :

### Admin :

```
utilisateur : admin@company.tld
mot de passe : admin
```

### Employee :

```
utilisateur : employee@company.tld
mot de passe : employee
```

### FRONTEND

## L'architecture du projet :

Ce projet, dit frontend, est connecté à un service API backend que vous devez aussi lancer en local (voir plus haut).

## Install project dependancies

```
$ npm install
```

## Run front with Live server

Installez live-server pour lancer un serveur local :

```
$ npm install -g live-server
```

Lancez l'application :

```
$ live-server
```

Puis allez à l'adresse : `http://127.0.0.1:8080/`

## Comment lancer un seul test ?

Installez jest-cli :

```
$npm i -g jest-cli
$jest src/__tests__/your_test_file.js
```

## Lancer les tests en local avec Jest

```
$ npm run test
```

## Comment voir la couverture de test ?

`http://127.0.0.1:8080/coverage/lcov-report/`

## Comptes et utilisateurs :

Vous pouvez vous connecter en utilisant les comptes:

### administrateur :

```
utilisateur : admin@test.tld
mot de passe : admin
```

### employé :

```
utilisateur : employee@test.tld
mot de passe : employee
```
