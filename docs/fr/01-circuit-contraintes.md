# 1. Circuit et système de contraintes

Halo2 modélise un circuit comme une implémentation du trait Circuit. La méthode configure décrit les colonnes, contraintes et relations ; synthesize assigne ensuite les valeurs dans un layouter.

Le ConstraintSystem collecte les expressions polynomiales que le prover et le verifier devront satisfaire. Une contrainte exprime une relation, pas une exécution impérative.

Les valeurs privées sont des witnesses ; les instances sont des valeurs publiques fournies au vérificateur. La séparation doit rester explicite pour éviter de rendre public un secret par erreur.

Le paramètre k détermine la taille de domaine disponible et influence directement les ressources de preuve.

Suite : [Colonnes, régions et layouter](02-colonnes-regions-layouter.md).
