# 4. Lookups et tables

Les lookups permettent de vérifier qu’une valeur ou un tuple appartient à une table autorisée. Ils sont utiles pour les opérations de range check, les tables de constantes et les relations non exprimées efficacement par un gate simple.

Une table est placée dans des colonnes fixed ou dédiées, puis le circuit contraint une valeur advice à retrouver une ligne correspondante. La relation d’appartenance devient ainsi vérifiable dans le système de contraintes.

Les lookups augmentent la puissance d’expression, mais consomment des colonnes et des lignes. Le concepteur doit mesurer leur coût dans le domaine choisi.

La table doit être complète pour le domaine accepté : une plage insuffisante crée un échec légitime, une plage trop large augmente les ressources.

Suite : [Preuve, transcript et vérification](05-preuve-transcript-verification.md).
