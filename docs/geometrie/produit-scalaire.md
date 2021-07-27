## Rappels et définitions

??? info "Rappels sur les vecteurs"
    La norme d'un vecteur $\vec{u}$ entre deux points $A$ et $B$, tel que $\vec{u} = \vec{AB}$ se note $\|\vec{u}\|$, il s'agit de la distance entre les deux points. $\|\vec{u}\| = \sqrt{(x_{B} - x_{A})^2 + (y_{B} - y_{A})^2}$.

**Définition** : soient $\vec{u}$ et $\vec{v}$ deux vecteur du plan $P$. Le **produit scalaire de $\vec{u}$ et $\vec{v}$**, noté $\vec{u} \centerdot \vec{v}$ (prononcé "u scalaire v") est un réel ayant pour valeur :

$$
\vec{u} \centerdot \vec{v} = \|\vec{u}\| \times \|\vec{v}\| \times \cos(\vec{u}, \vec{v})
$$

??? info "Exemple"
    Déterminer le produit scalaire entre les vecteurs $\vec{u}(2, 3)$ et $\vec{v}(-1, 4)$.

    Calcul des normes :

    $\|\vec{u}\| = \sqrt{2^2 + 3^2} = \sqrt{13}$ et $\|\vec{v}\| = \sqrt{(-1)^2 + 4^2} = \sqrt{17}$.

    Calcul de $\cos(\vec{u}, \vec{v})$ :

    $$

    Calcul du produit scalaire :

    $\vec{u} \centerdot \vec{v} = \|\vec{u}\| \times \|\vec{v}\| \times \cos(\vec{u}, \vec{v}) = \sqrt{13} \times \sqrt{17} \times \cos()$

**Remarque** : un produit scalaire nul implique un "angle droit" entre les deux vecteurs, on dit qu'ils sont **orthogonaux**. On dit aussi que le vecteur nul $\vec{0}$ est orthogonal à tout autre vecteur. La preuve :

Soient $\vec{u}$ et $\vec{v}$ deux vecteurs du plan.

$\vec{u} \centerdot \vec{v} = 0 \Leftrightarrow \|\vec{u}\| \times \|\vec{v}\| \times \cos(\vec{u}, \vec{v}) = 0$, or un produit de facteurs est nul ssi **au moins un** des facteurs est nul.



---

???+ info "Sources"
    * [https://www.maths-et-tiques.fr/telech/ProduitScal.pdf](https://www.maths-et-tiques.fr/telech/ProduitScal.pdf)
    * [https://fr.wikipedia.org/wiki/Norme_(math%C3%A9matiques)](https://fr.wikipedia.org/wiki/Norme_(math%C3%A9matiques))
    * Moi et mon cahier

--8<-- "includes/abbreviations.md"
