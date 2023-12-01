# Docker

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- la création d'une image docker  ✔️
- l'éxécution d'un container  ✔️
- l'orchestration de containers avec docker-compose  ✔️


## 💻 J'utilise

### Un exemple personnel commenté  ✔️
FROM node:lts-alpine

WORKDIR /app

COPY package.json package.json
RUN npm install

COPY public public
COPY src src

CMD npm run dev

### Utilisation dans un projet ❌ 

[lien github](...)

Description :

### Utilisation en production si applicable❌ 

[lien du projet](...)

Description :

### Utilisation en environement professionnel ✔️

Description : Pour mon entreprise j'ai du créer un contener d'un serveur NodeJs afin de l'installer et le faire tourner sur Naas

## 🌐 J'utilise des ressources

### Titre

- lien
- description

## 🚧 Je franchis les obstacles

### Point de blocage ❌ / ✔️

Description:

Plan d'action : (à valider par le formateur)

- action 1 ❌ / ✔️
- action 2 ❌ / ✔️
- ...

Résolution :

## 📽️ J'en fais la démonstration

- J'ai ecrit un [tutoriel](...) ❌ / ✔️
- J'ai fait une [présentation](...) ❌ / ✔️
