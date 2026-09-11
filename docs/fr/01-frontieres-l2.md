# 01 — Configurer les frontières du L2

Les références `build-on-base` centralisent RPC, chaînes et explorateurs.
Base mainnet porte l’identifiant 8453 et Base Sepolia 84532.
Un portefeuille doit confirmer la chaîne réellement sélectionnée avant signature.
Les adresses de contrats ne sont valides que dans leur environnement déclaré.
Un reçu L2 ne représente pas toujours la même notion de finalité qu’un règlement L1.
Dépôts et retraits traversent des mécanismes et délais distincts.
L’application doit nommer l’état observé plutôt que promettre une finalité prématurée.
Une configuration typée et unique évite les mélanges silencieux de réseaux.

Suite : [comptes et permissions](02-comptes-permissions.md).
