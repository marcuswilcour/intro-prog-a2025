# Exercice : Validité des noms de variables Java

Voici une liste de noms de variables. Indiquez pour chacun s'il est valide ou non selon les règles de Java.

1. `tauxDeReussite`     ✅  <!-- Passe -->
2. `$montantTotal`      🤔  <!-- Oui, mais... non -->
3. `@valeur`            ❌  <!-- Commence par un caractère invalide -->
4. `class`              ❌  <!-- Terme réservé -->
5. `nom étudiant`       ❌  <!-- Espace dans le nom, n'utilise pas le camelCase, l'accent est problématique -->
6. `_compteur`          ✅  <!-- Passe -->
7. `nombreEtudiants`    ✅  <!-- Passe -->
8. `1erEtudiant`        ❌  <!-- Commence par un numéro -->
9. `taux-de-reussite`   ❌  <!-- Utilise le kebab-case plutôt que le camelCase -->
10. `valeur1`           ✅  <!-- Passe, mais le nom n'est pas très explicatif -->
