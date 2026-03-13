# TP 5 — Gestion de l'état et structuration des composants React
 
## 📚 Cours
Développement Front-End moderne avec React
 
---
 
## Contexte
 
Ce TP s'inscrit dans le cadre du cours Développement Front-End moderne avec React. Il constitue la cinquième mise en pratique des concepts de React, en abordant la création de formulaires, le partage de données entre composants et la gestion d'un état global avec le contexte React.
le but est de maîtriser les formulaires contrôlés et non-contrôlés, de comprendre le principe de Lifting State Up  pour partager un état entre composants, et d'utiliser useContext pour gérer des informations globales dans l'application.
 
---
 
## Objectifs
 
#### - Créer des formulaires contrôlés avec useState
#### - Créer des formulaires non-contrôlés avec useRef
#### - Partager des données entre un composant parent et un enfant
#### - Utiliser le contexte React (useContext) pour gérer un état global
#### - Structurer une application React de manière claire et maintenable
 
---
 
## Technologies utilisées
 
- React 18
- JavaScript 
- JSX
- Hooks React (useState, useRef, useContext, createContext)
- CSS personnalisé
 
---
 
## 📁 Structure du projet
 

 
## Installation et lancement
 
#### - Cloner le projet :

git clone [https://github.com/TON_USERNAME/tp-react-debutant.git](https://github.com/nassima-brina/TP-5-D-couvrir-la-gestion-de-l-tat-et-la-structuration-des-composants-React/tree/main)

 
#### - Entrer dans le dossier :
cd tp-react-debutant

#### - Installer les dépendances :
npm install

 
#### - Lancer le serveur de développement :
npm start

#### L'application s'ouvre sur : [http://localhost:3000](http://localhost:3000)
 
---
 
## Composants créés
 
### FormulaireControle.js
#### Formulaire contrôlé avec deux champs (Nom et Email) reliés au state via useState. Affiche les valeurs saisies dans une alerte à la soumission.
 
### FormulaireNonControle.js
#### Formulaire non-contrôlé qui utilise useRef pour accéder directement aux valeurs des champs sans passer par le state.
 
### FormulaireInscription.js
#### Formulaire d'inscription avec trois champs (Nom, Email, Mot de passe) utilisant useState pour chaque champ.
 
### TemperatureInput.js
#### Composant enfant qui reçoit la température et une fonction de modification en props — il ne gère pas l'état lui-même.
 
### TemperatureConvertor.js
#### Composant parent qui contient l'état celsius et le transmet à TemperatureInput. Illustre le principe de Lifting State Up.
 
### TemperatureConvertorFahrenheit.js
#### Convertisseur bidirectionnel Celsius / Fahrenheit avec deux champs synchronisés en temps réel.
 
### UtilisateurContext.js
#### Fichier qui crée le contexte global UtilisateurContext avec createContext.
 
### Profil.js
#### Composant qui consomme le contexte utilisateur avec useContext et affiche le nom de l'utilisateur connecté avec des boutons de connexion et déconnexion.
 
---
 
## Aperçu de l'application

 
#### L'application affiche :
#### - Un formulaire contrôlé (Nom + Email)
#### - Un formulaire non-contrôlé (Nom + Email)
#### - Un formulaire d'inscription (Nom + Email + Mot de passe)
#### - Un convertisseur de température Celsius
#### - Un convertisseur bidirectionnel Celsius / Fahrenheit
#### - Un profil utilisateur avec connexion et déconnexion
 
---
 
## Conclusion
 
#### Ce cinquième TP m'a permis de comprendre et d'appliquer des notions avancées de React :
 
#### - La différence entre formulaires contrôlés (useState) et non-contrôlés (useRef)
#### - Le principe de Lifting State Up pour remonter l'état vers le composant parent
#### - La création et l'utilisation d'un contexte React (createContext, useContext) pour partager des données globales sans passer par les props
#### - La structuration claire d'une application React avec plusieurs composants indépendants.
