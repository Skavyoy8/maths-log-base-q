# Logarithme décimal & logarithme de base q — entraînement

Application web d’entraînement pour le DS de maths (bac pro / BTS CIEL) portant sur le
**logarithme décimal** et le **logarithme de base q**.

Formule centrale : `log_q(b) = log(b) / log(q)`.

## Utilisation

Ouvrir la page en ligne, ou télécharger `index.html` et l’ouvrir par double-clic.
Un seul fichier, aucune installation, fonctionne hors ligne.
Calculatrice nécessaire à partir de l’étape 3 (touche `LOG`, exemples pour TI-83).

## Les 6 étapes

1. Rappel : le log décimal, c’est la base 10
2. Le logarithme de base q : `log_q(b) = x` signifie `q^x = b` (sans calculatrice)
3. La formule de changement de base : `log_q(b) = log(b) / log(q)`
4. Les propriétés : `log_q(q) = 1`, `log_q(1) = 0`, `log_q(q^n) = n`, `log_q(a×b) = log_q(a) + log_q(b)`
5. Résoudre `q^x = b`, en isolant la puissance avant d’appliquer le log
6. Problème type DS : `U(t) = 48 × 0,75^t`, seuil 12 V

Chaque étape : un encadré de cours de 3 lignes, puis 6 exercices affichés **un par un**.
Mauvaise réponse → un indice ; après deux erreurs, un bouton affiche la solution détaillée et
débloque la suite. Les exercices réussis restent affichés avec leur correction rédigée comme
sur une copie.

38 exercices : 28 saisies numériques et 10 QCM.

## Vérification

Les 29 réponses numériques ont été calculées en Python, puis re-extraites du HTML et
recomparées à un recalcul indépendant. Les 36 exercices ont été parcourus dans le navigateur.
