# 05 — Agents, migrations et limites

Un agent on-chain doit séparer stratégie, validation, simulation, signature et diffusion.
Les valeurs fournies par l’utilisateur doivent être contrôlées avant tout appel d’outil.
L’enregistrement et le Builder Code identifient l’origine sans certifier la stratégie.
Les migrations OnchainKit, MiniKit ou fournisseurs de portefeuille changent les hypothèses de session.
Le comportement de repli doit refuser une chaîne ou un fournisseur non reconnu.
Ce parcours couvre réseau, comptes, paiements, paymasters, ERC-8021 et agents.
Il décrit les guides du dépôt sans déployer de contrat ni envoyer de transaction.
Aucune installation, compilation ou exécution n’a été effectuée ; les références amont restent normatives.
