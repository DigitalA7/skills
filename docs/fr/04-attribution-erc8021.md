# 04 — Attribution ERC-8021

Les Builder Codes ajoutent un suffixe d’attribution aux données de transaction.
Le suffixe doit conserver intact le calldata interprété par le contrat.
Viem, wagmi, ethers et portefeuilles injectés demandent des points d’intégration différents.
Une dépendance peut avoir déjà ajouté l’attribution avant le code applicatif.
La double application produit une donnée finale inattendue.
La revue doit comparer longueur, suffixe et décodage avant diffusion.
L’attribution ne remplace ni signature, ni autorisation, ni contrôle d’accès.
Elle doit rester visible dans les transactions construites par un agent.

Suite : [agents et migrations](05-agents-migrations.md).
