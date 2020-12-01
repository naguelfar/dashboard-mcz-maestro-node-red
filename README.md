# Dashboard monitoring poêle MCZ
Dashboard d'indicateurs, de suivi températures et de la durée de marche / arret.
Récupération des informations du poêle MCZ (Loop) via leur API Maestro en utilisant Node RED et les websockets

## Configuration
- Raspberry pi
  - accès réseau maison sur RJ45
  - accès wifi configuré sur le wifi du pôele (généralement 192.168.120.100)
- Node Red + palette "node-red-dashboard"

## Disclaimer
- le script est fourni en l'état et nécessite peut-être des adaptations à votre API (sur l'ordre des éléments récupérés)
- le script fourni aussi un exemple pour écrire / modifier la configuration (par défaut désactiver). __ATTENTION__ à ce que vous faites, vous êtes responsable de son utilisation et des dysfonctionnement que vous pourriez engendrer en modifiant la configuration de votre poêle. Dans le doute contentez vous de récupérer seulement les informations, c'est sans danger.
- le code est largement perfectible / optimisable (utilisation de switch par exemple) n'hésitez pas à partager vos modifications.

## Crédit
Librement inspiré du travail d'Anthony https://github.com/Anthony-55/maestro
