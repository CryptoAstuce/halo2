# 5. Preuve, transcript et vérification

La génération de preuve transforme un circuit satisfait et ses instances en un objet que le vérificateur peut contrôler. Halo2 utilise des engagements et des challenges dérivés par un transcript Fiat-Shamir.

Le transcript rend les challenges déterministes à partir des messages déjà engagés. Le prover et le verifier doivent absorber les mêmes éléments dans le même ordre.

La clé de vérification dépend de la configuration du circuit et de ses paramètres. Une preuve n’est pas portable vers une configuration différente sans respecter le protocole prévu.

Le verifier contrôle les engagements, les évaluations et les ouvertures nécessaires pour établir que les contraintes sont satisfaites sans connaître les witnesses privés.

Suite : [Paramètres, sérialisation et limites](06-parametres-serialization-limites.md).
