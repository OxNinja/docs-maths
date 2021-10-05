# Arithmétique de Peano

## Définition



## Symboles



## Axiomes de Peano

Peano utilise 5 axiomes pour définir l'ensemble des entiers naturels :

1. L'élément appelé zéro et noté $0$ est un entier naturel
2. Tout entier naturel $n$ a un unique successeur, noté $s(n)$ ou $Sn$ qui est un entier naturel
3. Aucun entier naturel n'a $0$ pour successeur
4. Deux entiers naturels ayant le même successeur sont égaux
5. Si un ensemble d'entiers naturels contient $0$ et contient le successeur de chacun de ses éléments, alors cet ensemble est $N$

De ces 5 axiomes en découlent 8 définitions dans son arithmétique :

1. $\forall x \lnot (Sx = 0)$
2. $\forall x (x = 0 \lor \exists y (x = Sy))$
3. $\forall x \forall y (Sx = Sy \Rightarrow x = y)$
4. $\forall x (x + 0 = x)$
5. $\forall x \forall y (x + Sy = S(x + y))$
6. $\forall x (x \cdot 0 = 0)$
7. $\forall x \forall y (x \cdot Sy = (x \cdot y) + x)$
8. Pour toute formule $\phi (x, x_{1}, \cdots, x_{n})$ à $n + 1$ variables libres, $\forall x_{1} \cdots \forall x_{n} ((\phi (0, x_{1}, \cdots, x_{n}) \land (\forall x (\phi (x, x_{1}, \cdots, x_{n}) \Rightarrow \phi (Sx, x_{1}, \cdots, x_{n})))) \Rightarrow \forall x \phi (x, x_{1}, \cdots, x_{n}))$

???+ info "Sources"
    * [https://www.youtube.com/watch?v=oKprCgIKWxo](https://www.youtube.com/watch?v=oKprCgIKWxo)
    * [https://fr.wikipedia.org/wiki/Axiomes_de_Peano#Arithm%C3%A9tique_de_Peano](https://fr.wikipedia.org/wiki/Axiomes_de_Peano#Arithm%C3%A9tique_de_Peano)
    * Moi et mon cahier

--8<-- "includes/abbreviations.md"
