# minishell
[Voir le sujet](./subject.pdf)

Projet de niveau 4 de l'école 42.

Création d’un shell qui devra se rapprocher le plus fidélement possible de BASH. Exclure les commandes invalides, executer toutes les commandes valides entrées grace à execve. Gestion des pipes, redirections, signaux, ainsi que des opérateurs logiques `&&`, `||`, des wildcards et des parenthèses.

### Fonctionnalités principales :
- **Opérateurs logiques :** Supporte `&&` et `||` pour l’enchaînement des commandes conditionnelles.
- **Wildcards :** Gestion du caractère `*` pour la correspondance des fichiers.
- **Parenthèses :** Gestion de l’exécution de commandes dans un sous-shell avec `()`.
- **Builtins :** Implémentation des commandes internes classiques telles que `echo`, `cd`, `pwd`, `export`, `unset`, et `env`.


![capture d'écran](./Screenshot.png)
