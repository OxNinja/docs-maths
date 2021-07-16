???+ warning "Attention"
    Travail en cours, des modifications sont très susceptibles d'arriver.

## Définition

### Théorème

* On admet l'existance d'un ensemble de nombres appelé **nombres complexes** : $\mathbb{C}$, contenant $\mathbb{R}$ l'ensemble de tous les réels.
* $\mathbb{C}$ est muni de deux opérations élémentaires, l'addition et la multiplication.
* $\mathbb{C}$ comporte un nombre noté $i$, le nombre imaginaire, tel que $i^2 = -1$.
* Tout élement $z$ de $\mathbb{C}$ possède une **écriture unique** sous la forme $z = a + ib,\:(a ,b) \in \mathbb{R}^2$

???+ info inline end "Exemples de nombres complexes"
    * $3x$
    * $\sqrt{15}$
    * $2i$
    * $x + 2i$
    * $\frac{\sqrt{x + 2}}{3} - 3i$

!!! warning "Remarque"
    Dans $\mathbb{C}$ on définit des opérations comme dans $\mathbb{R}$, mais pas de relation d'ordre comme $x > y$. Il est alors faux de noter $z \geq z'$ si $z$ et $z'$ sont deux nombres complexes non réels.

### Vocabulaire

* Dans la notation d'un nombre complexe, on trouve deux parties distinctes, la partie réelle et la partie imaginaire. Prennons $z = a + ib$, ici $a$ est **la partie réelle** et $b$ **la partie imaginaire**.
* La **forme algébrique** du nombre complexe $z$ s'écrit sous la forme $z = a + ib$
* Si la partie réelle d'un nombre complexe est nulle, donc $a = 0$, on dit qu'il s'agit d'un nombre imaginaire pur.

???+ info "Propriété"
    On dit que deux nombres complexes $z$ et $z'$ sont égaux **si et seulement si** leurs parties réelles et imaginaires sont égales :

    $$
    \begin{cases}
    z = a + ib\\
    z' = x + iy
    \end{cases}
    $$

    $$
    z = z' \Leftrightarrow \begin{cases}
    a = x\\
    b = y
    \end{cases}
    $$

    On note aussi qu'un nombre complexe est nul **si et seulement si** sa partie réelle  et sa partie imaginaire sont nulles.

## Représentation géométrique

## Forme trigonométrique

## Le conjugué

???+ info inline end "Exemple"
    Pour $z = 3 + 4i$, $\overline{z} = 3 - 4i$
    Pour $z = \sqrt{3} - \frac{3}{4}i$, $\overline{z} = \sqrt{3} + \frac{3}{4}i$

On note $\overline{z} = a - ib$ le conjugué de $z = a + ib$.

???+ info "Propriétés"
    $\forall (z, z') \in\mathbb{C}^2, n \in \mathbb{N}$:

    * $\overline{z + z'} = \overline{z} + \overline{z'}$
    * $\overline{zz'} = \overline{z} . \overline{z'}$
    * $\overline{\frac{z}{z'}} = \frac{\overline{z}}{\overline{z'}}, z' \ne 0$
    * $\overline{z^n} = \overline{z}^n$

## Équation du second degré

Pour les équations du second degré nous étions bloqués en cas de discriminant négatif. En effet la fonction racine carrée étant définie sur $[0 ; +\infty[$, un discriminant réel négatif rend alors l'expression $\frac{- b \pm \sqrt{\Delta}}{2a}$ impossible à résoudre dans $\mathbb{R}$.

Cependant, dans $\mathbb{C}$ il est tout à fait envisagable de résoudre une ESD avec un discriminant négatif.

Nous avons alors comme solutions de l'équation $az^2 + bz +c = 0$, avec toujours $\Delta = b^2 - 4ac$ :

* Si $\Delta > 0$ :

$z_{1} = \frac{-b + \sqrt{\Delta}}{2a}$ et $z_{2} = \frac{-b - \sqrt{\Delta}}{2a}$

* Si $\Delta = 0$ :

$z_{0} = \frac{-b}{2a}$

* Si $\Delta < 0$ :

$z_{1} = \frac{-b + i\sqrt{-\Delta}}{2a}$ et $z_{2} = \frac{-b - i\sqrt{-\Delta}}{2a}$

??? info "Exemple"
    Résolvons l'équation $f(z) = 0$ dans $\mathbb{C}$ :

    $$
    \begin{equation}
        f(z) = 2z^2 - 3z + 6
    \end{equation}
    $$

    Il s'agit d'une ESD, nous allons déterminer la ou les solutions possibles dans $\mathbb{C}$ de $f(z)$.

    Calcul du discriminant :

    $$
    \Delta = b^2 - 4ac = (-3)^2 - 4(2 \times 6) = -39
    $$

    Nous trouvons un discriminant négatif. L'équation $f(z) = 0$ comprend deux solutions conjuguées dans $\mathbb{C}$ :

    $z_{1} = \frac{-b + i\sqrt{-\Delta}}{2a}$ et $z_{2} = \frac{-b - i\sqrt{-\Delta}}{2a}$

    $$
    z_{1} = \frac{-(-3) - i\sqrt{-(-39)}}{2 \times 2} = \frac{3 - i\sqrt{39}}{4}
    $$

    On a alors :

    $$
    z_{2} = \frac{3 + i\sqrt{39}}{4}
    $$

    Au final :

    $$
    S = \{\frac{3 - i\sqrt{39}}{4} ; \frac{3 + i\sqrt{39}}{4}\}
    $$

---

???+ info "Sources"
    * [https://www.maths-cours.fr/cours/nombres-complexes-geometrie/](https://www.maths-cours.fr/cours/nombres-complexes-geometrie/)
    * Moi et mon cahier

--8<-- "includes/abbreviations.md"

