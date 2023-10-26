<h1>Big Data: Fondements et Architectures de stockage</h1>
<br>
<h6>Enset Mohammedia - Master SDIA</h6>
<h6>El hyani Asmae</h6>
<br>
<h3>TP2 Simple Exercices sur MapReduce</h3>
<h5>Exemple 1</h5>
<h5>Partie 1</h5>
<p>Un Job Map Reduce permettant, à partir d’un
fichier texte (ventes.txt) en entré, contenant les ventes d’une entreprise dans
les différentes villes, de déterminer le total des ventes par ville. La structure
du fichier ventes.txt est de la forme suivante :
date ville produit prix</p>
<h6>Creation de fichier texte (ventes.txt) </h6>
<img src="img.png">
<p>Ajouter le fichie sur hadoop avec la commande (hdfs dfs -put ventes.txt /)</p>
<h6>Mapper Class</h6>
<pre>
</pre>
<h6>Reduce Class</h6>
<pre>
</pre>
<h6>Job Class</h6>
<pre>
</pre>
<h6>Run application</h6>
<img src="img_1.png">

<h5>Partie 2</h5>
<p>un deuxième job permettant de calculer le prix total des ventes
des produits par ville pour une année donnée.</p>
<h6>Mapper Class</h6>
<pre>
</pre>
<h6>Reduce Class</h6>
<pre>
</pre>
<h6>Job Class</h6>
<pre>
</pre>
<h6>Run application</h6>
<img src="img_2.png">
<img src="img_3.png">
