<!DOCTYPE html>
<html>      
<head>
<style>
  .boutonmenu {
background-color: rgba(24, 24, 24, 0.808);
color: rgb(255, 255, 255);
border: solid 5px rgb(150, 140, 85);
cursor: pointer;
padding:20px;
margin-top:0px;
font-size: 30px;
}
.boutonmenu:hover {
background-color: rgba(24, 24, 24, 0.808);
}
.deroule {
position:fixed;
display: inline-block;
}
.deroule-child {
display: none;
background-color: rgba(24, 24, 24, 0.808);
min-width: 50px;
}
.deroule-child a {
color: white;
padding: 20px;
display: block;
text-decoration: none;
}
.deroule:hover .deroule-child {
display: block;
}
.bordure2{
border: solid 5px rgb(150, 140, 85);
background-color: #201d1d;
font-size: 40px;
padding: 5px;
margin-left: 25px;
}
.nom{ 
border: solid 5px rgb(150, 140, 85);
background-color: rgba(24, 24, 24, 0.808);
padding:5px;
position:unset;
}
.encadrer{
border: solid 2px rgb(255, 255, 255);
padding: 5px;
background-color: rgba(0, 0, 0, 0.233);
border-radius: 10px;
margin-left: auto;
margin-right: auto;
width:6em;
}
.produit{
  border:  5px rgb(150, 140, 85);
  display: inline-flix;
  width: 1400px;
  height: 1050px;
  padding: 0px;
  margin-left: 70px;
  margin-right:70px;
}
.pnom{
  border: solid 3px rgba(255, 255, 255, 0.521);
  width: 300px;
  height:400px;
  padding: 15px;
  margin: 5px;
  display:inline-flex;
  flex-flow: column;
  justify-content: center;
  margin-left: 0px;
  margin-right: 5px;
  margin-bottom: 10px;
  margin-top: 0px;
}
.rectangle{
  border:  solid 5px rgb(150, 140, 85);
  background-color: rgba(24, 24, 24, 0.808);
  display: inline-flex;
  width: 1470px;
  height: 5px;
  padding: 20px;
  margin-top:0px;
  margin-left: 153px;
}
.ligne{
  font-size: x-large;
  margin-right: 30px;
  margin-bottom: 10px;
}
/* on crée les box pour les images de produits*/
img.fd1,
img.fd2,
img.fd3 {
  border: solid 5px wheat;
  width: 170px;
  height:250px;
  padding: 3px;
  margin: 5px;
  display:inline-flex;
  justify-content: center;
  margin-left: 60px;
  margin-right: 72px;
  margin-bottom: 0px;
  margin-top: 15px;
}
.produit1{
  border:  5px rgb(150, 140, 85);
  display: inline-flix;
  width: 1100px;
  height: 1050px;
  padding: 20px;
  margin-left: 220px;
  margin-right:100px;
}
.text{
  margin-left:200px;
  margin-right:200px;
}
.conec{
  background-color: rgb(0, 0, 0);
  border: solid 1px rgb(150, 140, 85);
}
.Acc{
  border:  5px rgb(150, 140, 85);
  display: inline-flix;
  width: 1100px;
  height: 1050px;
  padding: 20px;
  margin-left: 315px;
  margin-right:100px;
}
</style>
    <h1 class=nom style="color:rgb(255, 255, 255);"  font-weight=bold  align = "center"> ALB-28  </h1>
    <meta charset="utf-8">
    <link rel="stylesheet" href="page.css">
</head>
<body background="bn1.jpg">
  <div class="deroule">
    <button class="boutonmenu">&nbsp;&nbsp;Menu&nbsp;&nbsp;</button>
    <div class="deroule-child">
    <a href="modelesite.html">Accueil</a>
    <a href="type1.html">Jeux de cartes</a>
    <a href="type2.html">Jeux de plateau</a>
    <a href="type3.html">Figurines</a>
    <a href="test2.html">Se connecter</a>
    <a href="test1.html">S'inscrire</a>
    <a href="nouscont.html">Nous contacter</a>
    </div>
</div>
<!-- 
<div class="rectangle">
  <p class="ligne" style="color: white;">test 1</p>
  <p class="ligne" style="color: white;">test 1</p>
</div>
-->



<h1 class="encadrer" style="color:rgb(255, 255, 255)"  font-weight=bold   align = "center">Accueil</h1>
<br><br>

<h2 class="text" style="color: rgb(168, 156, 92);"> Bienvenue chez ALB-28,</h2>
<h2 class="text" style="color: rgb(168, 156, 92);">
Depuis notre création en 1992 nous n'avons cessé 
de proposer à nos utilisateurs les meilleurs produits. Retrouvez sans attendre nos jeux de cartes de qualité imbattable 
ou encore nos magnifiques figurines. N'hesitez pas à consulter notre toute nouvelle collection de jeu de société.
</h2>
<div class="Acc">
  
  <div class="pnom">
    <a align=center href="type1.html">
    <img hr class="fd2" src="cartes/2.jpg" id="p2">

    <h2 style="color: rgb(255,255,255)">Nos jeux de cartes</h2>
    </a>
  </div>


  <div class="pnom">
    <a align=center href="type2.html">
    <img hr class="fd2" src="plateau/1.jpg" id="p2">

    <h2 style="color: rgb(255,255,255)">Nos jeux de plateau</h2>
    </a>
  </div>

  <div class="pnom">
    <a align=center href="type3.html">
    <img hr class="fd2" src="figurines/5.jpg" id="p2">

    <h2 style="color: rgb(255,255,255)">Nos figurines</h2>
    </a>
  </div>

</div>
<br><br><br><br>

</body>
</html>
