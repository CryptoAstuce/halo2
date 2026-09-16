# 3. Selectors, gates et advice

Un gate est une expression activée sur certaines lignes par un selector. Le selector évite d’appliquer une relation à des cellules qui ne représentent pas le même type de calcul.

Les conseils advice sont assignés par le circuit, mais leur cohérence est contrôlée par les équations. Une valeur témoin fausse ne peut pas produire une preuve valide si les contraintes la relient correctement aux sorties.

Les composants réutilisables encapsulent des opérations comme l’addition, la copie contrainte ou la décomposition en bits. Leur documentation doit préciser les hypothèses de champ et de plage.

Une contrainte oubliée est plus dangereuse qu’une contrainte trop coûteuse : elle peut laisser passer un témoin qui ne représente pas le calcul attendu.

Suite : [Lookups et tables](04-lookups-tables.md).
