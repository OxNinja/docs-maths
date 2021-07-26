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

Encore là quelques définitions et propriétés.

Soit $f$ une fonction. On dit que, sur un intervalle $I$, $f$ :

* admet un **maximum** en $x$ (ou encore que $f(x)$ est le maximum de $f$) ssi $\forall y \in I, f(x) \geq f(y)$.
* admet un **minimum** en $x$ (ou encore que $f(x)$ est le minimum de $f$) ssi $\forall y \in I, f(x) \leq f(y)$.

## Parité

### Fonction paire

On dit qu'une **fonction est paire** si elle possède une symétrie axiale par rapport à l'axe des ordonnées. Comme par exemple la fonction $f(x) = x^2$.

On peut simplifier la phrase précédente par : une fonction $f$ est **paire** ssi $f(-x) = f(x)$.

### Fonction impaire

On dit qu'une **fonction est impaire** si elle possède une symétrie centrale par rapport à l'origine du plan. Comme par exemple la fonction $g(x) = \frac{1}{x}$.

On peut simplifier la phrase précédente par : une fonction $g$ est **impaire** ssi $g(-x) = -g(x)$.

## Positions relatives

Lorsque l'on souhaite étudier la position relative entre deux courbes, que ce soit pour comparer deux fonctions ou encore savoir quand deux fonctions ont la même valeur, il suffit **d'étudier la différence des deux fonctions**.

En outre, pour étudier la position relative entre deux fonctions $f$ et $g$, on étudie le signe de $f(x) - g(x)$.

??? info "Exemple"
    Étudier la position relative entre les deux fonctions $f(x) = 4x^2 + 5x$ et $g(x) = -x^2 + 9x$.

    Nous allons étudier $f(x) - g(x)$ :

    $f(x) - g(x) = (4x^2 + 5x) - (-x^2 + 9x) = 5x^2 - 4x$

    Étude de signe de $h(x) = 5x^2 - 4x$ :

    $h(x) = 0 \Leftrightarrow 5x^2 - 4x = 0$

    Résolvons l'ESD $h(x) = 0$ :

    $\Delta = b^2 - 4ac = (-4)^2 - 4\times5\times0 = 16$

    $\Delta > 0$ donc il y a deux racines dans $\mathbb{R}$ :

    $x_{1}$ et $x_{2} = \frac{-b \pm \sqrt{\Delta}}{2a}$.

    $x_{1} = \frac{4 - \sqrt{16}}{10} = 0$ et $x_{2} = \frac{4 + \sqrt{16}}{10} = \frac{4}{5}$

    $h$ s'annule en deux points, $x_{1}$ et $x_{2}$, voici le tableau de signe de $h(x)$ avec les positions relatives de $f$ et $g$ :

    | $x$                               | $-\infty$ | 0 |            | $\frac{4}{5}$ | $+\infty$ |
    |-----------------------------------|-----------|---|------------|---------------|-----------|
    | $h(x)$                            | +         | 0 | -          | 0             | +         |
    | Position de $f$ par rapport à $g$ | au dessus |   | en dessous |               | au dessus |

## Composée de fonctions

Soient $f$ et $g$ deux fonctions, la **composée de $f$ et $g$** notée $f \circ g$ est définie comme suit :

Soient $D_{f}$ et $D_{g}$, respectivement les ensembles de définition de $f$ et $g$, avec $D_{f} \subset D_{g}$.

$$
f \circ g(x) = f(g(x)), \forall x \in D_{f}, f \in D_{g}
$$

??? info "Exemple"
    Déterminer $f \circ g$ pour $f(x) = 3x^2$ et $g(x) = \sqrt{\frac{1}{x}}$.

    Nous savons que $f \circ g = f(g(x))$ donc,

    $f \circ g = f(g(x)) = f(\sqrt{\frac{1}{x}}) = 3(\sqrt{\frac{1}{x}})^2$

Voilà c'est tout pour les composées.

---

???+ info "Sources"
    * [https://www.maths-france.fr/Terminale/TerminaleS/Cours/04-fonctions.pdf](https://www.maths-france.fr/Terminale/TerminaleS/Cours/04-fonctions.pdf)
    * Moi et mon cahier

--8<-- "includes/abbreviations.md"
