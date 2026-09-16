# 2. Colonnes, régions et layouter

Les colonnes advice portent généralement les témoins, les colonnes instance portent les entrées publiques et les colonnes fixed portent des constantes. Leur séparation structure les données accessibles aux contraintes.

Le layouter organise les affectations en régions. Une région donne un espace local où les cellules sont positionnées par ligne et colonne, puis les gates relient ces cellules.

AssignedCell conserve la cellule et sa valeur connue lorsqu’elle est disponible. Les copies entre régions doivent respecter les contraintes de permutation prévues par la configuration.

Une bonne conception rend visibles les interfaces d’un composant : entrées, sorties, lignes consommées et contraintes imposées.

Suite : [Selectors, gates et advice](03-selectors-gates-advice.md).
