# Devoir 12 : Algorithmique de base
## Objectifs :
- **Maîtriser la création de méthodes utiles**. Pour cela, il est indispensable de toujours bien distinguer et de comprendre :
  - **ce que la méthode doit faire comme travail** (cela définira son cahier des charges et permettra de définir un nom de méthode adéquat avec un verbe d'action)
  - **les informations à disposition** pour réaliser son travail (cela permettra de définir les paramètres de la méthode)
  - **la nature de la réponse attendue** que la méthode devra fournir (cela permettra de définir son type de retour)
- **Produire des méthodes robustes** (il faut y penser d'avance et faire en sorte que nos méthodes n'explosent pas lorsque des cas particuliers se posent).
- **Entraînement à de l'algorithmique simple** (certaines suites d'opérations (algorithmes) se retrouvent partout en programmation, le temps est désormais venu de rafraîchir ce qui a été vu au module 319 et de maîtriser ces algorithmes de base constamment utilisés et réutilisés en programmation).
- Réflexion préparatoire à l'exercice qui suivra en classe.
- **Bonne préparation à la E1 à venir**.

## Durée :
Environ 30'

## Contexte général :
Vous recevez un projet avec deux classes :
- la classe **`Humain`** qui est fournie et qui représente un humain possédant un `nom` et un `age`.
- la classe **`Foule`** qui est fournie mais quasiment vide ou presque. C'est sur elle que vous allez devoir travailler et réflechir afin de lui donner le savoir-faire attendu.

## Mission :
**`TRÈS IMPORTANT`** : **Notez vos questions et difficultés rencontrées** au fur et à mesure !  
*C'est le seul moyen efficace d'avancer. Ça vous sera utile pour ne pas les oublier, pour demander au collègue et/ou au prof et/ou en coaching.*

Pour chacune des fonctionnalités décrites ci-dessous, déclarez la méthode correspondante (mais **SANS LA CODER**, mettez-y simplement un `return null` ou un `return 0` sans plus)

Réfléchissez bien aux 3 choses mentionnées dans les objectifs ci-dessus afin de :  
  1. donner un nom adéquat à votre méthode.
  2. ne pas vous tromper avec ses paramètres.
  3. correctement définir son type de retour.

## Indications fournies :
A vous de traduire les fonctionnalités ci-dessous en méthodes Java correspondantes dans la classe **`Foule`**.
1. On doit pouvoir créer une foule en précisant la taille maximum de celle-ci (=le nombre maximum de personne qu'on pourra un jour y mettre).
2. On doit aussi pouvoir créer une foule sans avoir a spécifier la taille de celle-ci (pas connue au moment de la création)
3. On doit pouvoir ajouter un humain dans la foule.
4. On doit pouvoir supprimer un humain de la foule.
5. On doit pouvoir compter le nombre d'humains présents dans une foule.
6. On doit pouvoir compter le nombre d'humains ayant un certain nom connu sont présents dans une foule.
7. Puisqu'on peut mettre un objet plusieurs fois dans un tableau, on doit aussi pouvoir compter combien de fois un certain humain se trouve dans une foule (vive les réplicants 😅).
8. Puisqu'on peut mettre un objet plusieurs fois dans un tableau, on doit pouvoir chercher la première position où un certain humain se trouve dans une foule.
9. On doit pouvoir chercher la dernière position où un certain humain se trouve dans une foule.
10. On doit pouvoir chercher le premier humain dans une foule ayant un nom connu.
11. On doit pouvoir chercher le dernier humain dans une foule ayant un nom connu.
12. On doit pouvoir interroger une foule pour en ressortir le plus petit age de celle-ci.
13. On doit pouvoir interroger une foule pour en ressortir le plus grand age de celle-ci.
14. On doit pouvoir interroger une foule pour en ressortir l'âge moyen de celle-ci.
15. On doit pouvoir demander à une foule de nous donner sa liste de l'ensemble des humains qu'elle contient. Cette liste pourra bien entendu contenir des `null`.
16. On doit pouvoir demander à une foule de nous donner **une copie** de la liste de l'ensemble des humains qu'elle contient. Cette liste pourra bien entendu contenir des `null`.
17. On doit pouvoir demander à une foule de nous donner une liste de l'ensemble des humains qu'elle contient. Cette liste doit être une liste "sans trous", c-à-d sans `null` dans celle-ci. En conséquence, cette liste aura une taille d'exactement le nombre d'humains qu'elle contient 😊
18. On doit pouvoir demander à une foule de nous donner l'ensemble des noms qu'elle contient sans doublons (= ne contenant pas deux fois le même nom).
## RESTITUTION :
1. Rendre ce devoir normalement par `push` GitHub
