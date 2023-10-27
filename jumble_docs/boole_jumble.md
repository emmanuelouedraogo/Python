# L'algèbre de boole

L'algèbre de Boole est basée sur deux valeurs logiques : vrai (1) et faux (0). Les opérateurs booléens permettent de combiner ces valeurs logiques pour obtenir de nouvelles valeurs logiques.

Les principaux opérateurs booléens sont :

* **Et** (∧) : la valeur de la fonction est vrai si et seulement si les deux valeurs d'entrée sont vraies.
* **Ou** (∨) : la valeur de la fonction est vrai si au moins une des deux valeurs d'entrée est vraie.
* **Non** (¬) : la valeur de la fonction est inverse à la valeur d'entrée.

L'algèbre de Boole est utilisée dans de nombreux domaines, notamment l'informatique, l'électronique et la logique formelle.

**Exemples**

* La fonction booléenne `a ∧ b` est vraie si et seulement si les deux variables `a` et `b` sont vraies.
* La fonction booléenne `a ∨ b` est vraie si au moins l'une des deux variables `a` et `b` est vraie.
* La fonction booléenne `¬a` est vraie si la variable `a` est fausse.

**Applications**

L'algèbre de Boole est utilisée dans de nombreux domaines, notamment :

* **Informatique** : l'algèbre de Boole est utilisée pour représenter les circuits électroniques et les fonctions logiques.
* **Électronique** : l'algèbre de Boole est utilisée pour concevoir des circuits électroniques.
* **Logique formelle** : l'algèbre de Boole est utilisée pour modéliser des raisonnements logiques.

**Conclusion**

L'algèbre de Boole est une branche des mathématiques qui est utilisée dans de nombreux domaines. Elle permet de représenter des raisonnements logiques et de concevoir des circuits électroniques.

**Vocabulaire**

* **Variable booléenne** : une variable qui peut prendre deux valeurs, vrai ou faux.
* **Opérateur booléen** : une opération qui prend deux ou plusieurs variables booléennes en entrée et renvoie une variable booléenne en sortie.
* **Fonction booléenne** : une expression qui utilise des variables booléennes et des opérateurs booléens.

**Historique**

L'algèbre de Boole a été inventée par George Boole en 	. Boole était un mathématicien anglais qui s'intéressait à la logique. Il a développé une nouvelle approche de la logique qui était basée sur l'algèbre.

L'algèbre de Boole a été rapidement adoptée par les ingénieurs et les informaticiens. Elle est aujourd'hui une partie essentielle de ces disciplines.


# De quoi parle-t-on exactement ?

Un peu comme on fait une addition entre 2 nombres, on peut faire une addition entre octets pour obtenir un résultat. Les opérateurs sont des opérations qui vont être effectuées sur les octets pour obtenir un résultat.

## Opérateur AND

AND  = ET en français. Le résultat sera VRAI si la valeur A **ET** la valeur B sont vraies.

| Valeur A | Valeur B | Résultat |
| -------- | -------- | --------- |
| 0        | 0        | 0         |
| 1        | 0        | 0         |
| 0        | 1        | 0         |
| 1        | 1        | 1         |

## Opérateur OR

OR  = OU en français. Le résultat sera VRAI si la valeur A **OU** la valeur B sont vraies.

| Valeur A | Valeur B | Résultat |
| -------- | -------- | --------- |
| 0        | 0        | 0         |
| 1        | 0        | 1         |
| 0        | 1        | 1         |
| 1        | 1        | 1         |

## Opérateur XOR

XOR = OU eXclusif Le résultat sera VRAI si la valeur A est vraie **OU** si la valeur B est vraie, mais **pas les 2 en même temps**.

| Valeur A | Valeur B | Résultat |
| -------- | -------- | --------- |
| 0        | 0        | 0         |
| 1        | 0        | 1         |
| 0        | 1        | 1         |
| 1        | 1        | 0         |

## Opérateur NAND

NAND = Non ET Le résultat sera exactement l**‘inverse du AND**.

| Valeur A | Valeur B | Résultat |
| -------- | -------- | --------- |
| 0        | 0        | 1         |
| 1        | 0        | 1         |
| 0        | 1        | 1         |
| 1        | 1        | 0         |

## Opérateur NOR

NOR = Non OU Le résultat sera exactement l’**inverse du OR**.

| Valeur A | Valeur B | Résultat |
| -------- | -------- | --------- |
| 0        | 0        | 1         |
| 1        | 0        | 0         |
| 0        | 1        | 0         |
| 1        | 1        | 0         |

## Opérateur NOT

NOT = Non Le résultat sera exactement l’**inverse de la valeur**

| Valeur | Résultat |
| ------ | --------- |
| 0      | 1         |
| 1      | 0         |
