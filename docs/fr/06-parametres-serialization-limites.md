# 6. Paramètres, sérialisation et limites

Les paramètres déterminent la taille du domaine, les capacités de permutation et les ressources nécessaires à la preuve. Le choix de k doit couvrir le circuit tout en restant compatible avec les limites de mémoire et de temps.

Les clés et preuves sérialisées doivent suivre des formats canoniques et être validées à la lecture. Une sérialisation ambiguë peut casser l’interopérabilité ou modifier le transcript.

Halo2 prouve les contraintes qui ont été déclarées. Il ne vérifie pas automatiquement que ces contraintes représentent l’intention métier, que les entrées sont bien normalisées ou que les limites de sécurité externes sont respectées.

Périmètre : ce parcours traduit les modules circuit, plonk, transcript, poly et dev du dépôt. Aucune installation, compilation ou exécution de test n’a été effectuée. Consulter les suites officielles pour une validation concrète.

Retour : [sommaire du parcours](README.md).
