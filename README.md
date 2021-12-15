# Binder
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/lindabouallegue/Analyse_Numerique/main)
<h1>TPs</h1>
- <a href="https://github.com/lindabouallegue/Analyse_Numerique/blob/main/TP1/TP1_E.ipynb">TP1</a></br>
- <a href="https://github.com/lindabouallegue/Analyse_Numerique/blob/main/TP2/TP2_E.ipynb">TP2</a></br>
- <a href="https://github.com/lindabouallegue/Analyse_Numerique/blob/main/TP3/TP3.ipynb">TP3</a>
<hr>

<img src="Gif/Animation.gif" />
<hr>
<h1 >TP1 Résolution de l'équation linéaire </h1>
<h2>Objectifs</h2>
<p>Comparaison entre les trois méthodes pour donner une valeur approchée de de alpha pour f(x)=0 qui sont :</p>
<h4>-La méthode de la dichotomie </h4>
<h4>-La méthode du point fixe </h4>
<h4>-La méthode de Newton </h4>
<h3>Exercice 1 </h3>
<h3>Exercice 2</h3>
<h3>Exercice 3</h3>
<h3>Exercice 4</h3>
<h2 style="color:#FF0000";>Conclusions</h2>
<h3>La méthode de la dichotomie</h3>
<p>+ L'erreur ne dépend pas de la fonction f</p>
<p>- la méthode de la dichotomie est lente</p>
<h3>La méthode du point fixe</h3>
<p>- La méthode est lente</p>
<p>+ Plus l'ordre de convergence est grand plus la méthode est rapide </p>
<h3>La méthode de Newton</h3>
<p>+ La méthode de Newton est plus rapide que la méthode de la dichotomie</p>

<h1 >TP2 Interpolation Numérique </h1>
<h2>Objectifs:</h2>
<p> Dans ce TP nous avons étudié les deux méthodes de l'intérpolation polynomiale qui sont :</p>
<p>- Méthode de Lagrange </p>
<p>- Méthode de Newton</p>
<h2>Définitions :</h2>
<p><b>Méthode de Lagrange : </b> </p>
<p>permet de trouver les points stationnaires (maximum, minimum…) d'une fonction dérivable d'une ou plusieurs variables, sous contraintes.</p>
<p><b>Méthode de Newton </b></p>
<p>ne méthode d'interpolation polynomiale permettant d'obtenir le polynôme de Lagrange comme combinaison linéaire de polynômes de la « base newtonienne ».</p>
<h3>Exercice 1</h3>
<h3>Exercice 2</h3>
<h3>Exercice 3</h3>
<h2>Conclusion</h2>
<p> La méthode de Newton est plus pratique puisque en ajoutant un nouveau point on ne doit pas refaire tout le calcul, nous conservons ce qu'on a obtenu et on termine notre travail. </p>  

<h1 >TP3 Mini projet </h1>
<h2>Objectifs:</h2>
<p> Dans ce TP nous avons étudié les quatre méthodes de l'intégration numérique qui sont :</p>
<p>- Méthode des Trapézes</p>
<p>- Méthode de Simpson</p>
<p>- Méthode des Rectangles</p>
<p>- Méthode de Milieu</p>
<h2>Définitions :</h2>
<p>L'intégration numérique est un chapitre important de l'analyse numérique et un outil indispensable en physique numérique. On intègre numériquement dans deux cas principaux :

- on ne peut pas intégrer analytiquement,
- l'intégrande est fourni non pas sous la forme d'une fonction mais de tableaux de mesures, cas d'ailleurs le plus fréquent dans la vraie vie.
Les méthodes numériques d'intégration d'une fonction sont nombreuses et les techniques très diverses. Des très simples, comme la méthode des rectangles aux très complexes comme certaines variétés de la méthode de Monte-Carlo.</p>
<h3>Méthode des Trapézes</h3>
<p>La méthode d'intégration approchée, dite des trapèzes, décrite ci-après, introduite par Newton & Cotes est plus précise que la méthode élémentaire, dite des rectangles, correspondant aux sommes de Cauchy-Riemann, consistant à remplacer la fonction initiale par une approximation en escalier. Graphiquement, sur l'intervalle [xi, xi+1], on remplace l'arc de courbe par le segment [MiNi+1], donc l'aire sous la courbe, par le « rectangle » xi Mi Ni+1 xi+1 :</p>
<br>
<div><span style="float:left;"><img src="/TP3/1.gif"width="300" 
     height="400" /></span><span style="float:right;"><img src="/TP3/2.gif"width="300" 
     height="400" /></span></div>
<br>
<h3>Méthode de Simpson</h3>
<p>En analyse numérique, la méthode de Simpson, du nom de Thomas Simpson, est une technique de calcul numérique d'une intégrale, c'est-à-dire le calcul approché de :</p>
<img src="/TP3/3.svg"/>
<h3>Méthode des Rectangles</h3>
<p>Dans cette méthode, on calcule l’intégrale numérique en réalisant une somme de surfaces de rectangles. Le domaine d’intégration est découpé en intervalles et on fait comme si la fonction restait constante sur chaque intervalle.
    <img src="/TP3/4.png"/>

</p>
<h3>Méthode de Milieu</h3>
<p>
La méthode du point milieu permet d’améliorer sensiblement la vitesse de convergence par rapport
aux rectangles à gauche ou à droite. L’idée est ici de couper à nouveau [a, b] en intervalles de
même longeur.
  <br>
<center><img src="/TP3/4.svg" width="300" 
             height="400" /></center>
</p>
<h2>Conclusion</h2>
<p> Plus que le nombre de subdivisions augmentent , les valeurs sont plus proches des valeurs exactes.</p>
<h2>Demo</h2>
<img src="Gif/Animation3.gif" />




