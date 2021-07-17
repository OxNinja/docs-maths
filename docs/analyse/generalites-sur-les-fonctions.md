# Généralités sur les fonctions

## Domaine de définition

Le **domaine de définition** d'une fonction $f$ est l'ensemble des réels $x$ où $f(x)$ existe.

On trouve principalement deux conditions à remplir pour qu'une fonction existe :

???+ info inline end "Exemple"
    La fonction $f(x) = \sqrt{3x}$ est définie dans $\mathbb{R}^+$ ($[0; +\infty[$).

* Pas de dénominateur nul
* Pas de racine carrée d'un nombre négatif

## Sens de variation

Soit $f$ une fonction définie sur un intervalle $I$ de $\mathbb{R}$. On dit que :

* $f$ est **croissante** sur $I$ ssi $\forall (a, b) \in \mathbb{R}^2$, si $a \ge b$ alors $f(a) \ge f(b)$
* $f$ est **strictement croissante** sur $I$ ssi $\forall (a, b) \in \mathbb{R}^2$, si $a > b$ alors $f(a) > f(b)$
* $f$ est **décroissante** sur $I$ ssi $\forall (a, b) \in \mathbb{R}^2$, si $a \le b$ alors $f(a) \le f(b)$
* $f$ est **strictement décroissante** sur $I$ ssi $\forall (a, b) \in \mathbb{R}^2$, si $a < b$ alors $f(a) < f(b)$
* $f$ est **constante** sur $I$ ssi $\forall (a, b) \in \mathbb{R}^2$, $f(a) = f(b)$
* $f$ est **monotone** sur $I$ ssi ou bien $f$ est croissante sur $I$, ou bien $f$ est décroissante sur $I$
* $f$ est **strictement monotone** sur $I$ ssi ou bien $f$ est strictement croissante sur $I$, ou bien $f$ est strictement décroissante sur $I$

Par extension, soient $f$ et $g$ deux fonctions définies sur un intervalle $I$ de $\mathbb{R}$. Si :

* $f$ et $g$ sont croissantes sur $I$, alors $f + g$ est **croissante** sur $I$
* $f$ et $g$ sont strictement croissantes sur $I$, alors $f + g$ est **strictement croissante** sur $I$
* $f$ et $g$ sont décroissantes sur $I$, alors $f + g$ est **croissante** sur $I$
* $f$ et $g$ sont strictement décroissantes sur $I$, alors $f + g$ est **strictement décroissante** sur $I$

De même, si :

* $f$ et $g$ sont croissantes **et positives** sur $I$, alors $f \times g$ est **croissante** sur $I$
* $f$ et $g$ sont  strictement croissantes **et strictement positives** sur $I$, alors $f \times g$ est **strictement croissante** sur $I$
* $f$ et $g$ sont décroissantes **et positives** sur $I$, alors $f \times g$ est **décroissante** sur $I$
* $f$ et $g$ sont strictement décroissantes **et strictement positives** sur $I$, alors $f \times g$ est **strictement décroissante** sur $I$

Aussi, la fonction inverse $\frac{1}{x}$ *inverse* le sens de variation. Si :

* $f$ est **strictement positive** et **strictement croissante** sur $I$, alors $\frac{1}{f}$ est **strictement décroissante** sur $I$.
* $f$ est **strictement positive** et **strictement décroissante** sur $I$, alors $\frac{1}{f}$ est **strictement croissante** sur $I$.
* $f$ est **strictement négative** et **strictement croissante** sur $I$, alors $\frac{1}{f}$ est **strictement décroissante** sur $I$.
* $f$ est **strictement négative** et **strictement décroissante** sur $I$, alors $\frac{1}{f}$ est **strictement croissante** sur $I$.

Oui il y a beaucoup de propriétés. Mais au moins le plus gros est dit.

## Extrema

## Parité

## Positions relatives

## Composée de fonctions

---

???+ info "Sources"
    * [https://www.maths-france.fr/Terminale/TerminaleS/Cours/04-fonctions.pdf](https://www.maths-france.fr/Terminale/TerminaleS/Cours/04-fonctions.pdf)
    * Moi et mon cahier

--8<-- "includes/abbreviations.md"
