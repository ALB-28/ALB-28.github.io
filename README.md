<!DOCTYPE html>
<html>      
<head>
    <style>
.boutonmenuprincipal {
background-color: rgba(24, 24, 24, 0.808);
color: rgb(255, 255, 255);
border: solid 5px rgb(150, 140, 85);
cursor: pointer;
padding:20px;
margin-top:0px;
font-size: 30px;
}
.boutonmenuprincipal:hover {
background-color: rgba(24, 24, 24, 0.808);
}
.dropdown {
position: relative;
display: inline-block;
}
.dropdown-child {
display: none;
background-color: rgba(24, 24, 24, 0.808);
min-width: 50px;
}
.dropdown-child a {
color: white;
padding: 20px;
text-decoration: none;
display: block;
}
.dropdown:hover .dropdown-child {
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
border: solid 2px rgb(150, 140, 85);
padding: 5px;
background-color: rgba(0, 0, 0, 0.233);
border-radius: 10px;
margin-left: auto;
margin-right: auto;
width:6em;
}

.produit{
  border: solid 5px rgb(150, 140, 85);
  display: inline-block;
  width: 1000px;
  height: 1050px;
  padding: 20px;
  margin-left: 300px;
  margin-right:300px;
}
.pnom{
  border: solid 3px rgb(150,140,85);
  width: 170px;
  height:30px;
  padding: 3px;
  margin: 5px;
  display:inline-flex;
  justify-content: center;
  margin-left: 74px;
  margin-right: 74px;
  margin-bottom: 10px;
  margin-top: 10px;
  
}
.rectangle{
border: solid 5px rgb(150, 140, 85);
display:inline-block ;
justify-content: center;
margin-left: 200px;
margin-right: 200px;
padding: 0px;
width: auto;
}
.ligne{
border:solid 5px rgb(150,140,85);
display: inline;
justify-items: center;
width: auto;
height: auto;
padding:auto;
}
img.fd1,
img.fd2,
img.fd3 {
  border: solid 5px rgb(255, 255, 255);
  width: 170px;
  height:250px;
  padding: 3px;
  margin: 5px;
  display:inline-flex;
  justify-content: center;
  margin-left: 72px;
  margin-right: 72px;
  margin-bottom: 5px;
  margin-top: 15px;
}
</style>
    <h1 class=nom style="color:rgb(255, 255, 255);"  font-weight=bold  align = "center"> ALB-28  </h1>
    <div class="dropdown">
        <button class="boutonmenuprincipal">&nbsp;&nbsp;Menu&nbsp;&nbsp;</button>
        <div class="dropdown-child">
        <a href="modelesite.html">Nos poduits</a>
        <a href="test2.html">Se connecter</a>
        <a href="test1.html">S'inscrire</a>
        <a href="test1.htmls">Nous contacter</a>
        </div>
    </div>
    <meta charset="utf-8">
</head>
<body background="flo.jpg">
<h1 class="encadrer" style="color:rgb(150, 140, 85)"  font-weight=bold   align = "center">Nos produits</h1>
<br><br>
<div class="produit">
<img class="fd1" src="p1.jfif" id="p1">
<img class="fd2" src="p2.jfif" id="p2">
<img class="fd3" src="p3.jfif" id="p3">
<h3 style="color: rgb(255,255,255)" class="pnom">Produit 1</h3>
<h3 style="color: rgb(255,255,255)" class="pnom">Produit 2</h3>
<h3 style="color: rgb(255,255,255)" class="pnom">Produit 3</h3>

<img class="fd1" src="p1.jfif" id="p1">
<img class="fd2" src="p2.jfif" id="p2">
<img class="fd3" src="p3.jfif" id="p3">
<h3 style="color: rgb(255,255,255)" class="pnom">Produit 1</h3>
<h3 style="color: rgb(255,255,255)" class="pnom">Produit 2</h3>
<h3 style="color: rgb(255,255,255)" class="pnom">Produit 3</h3>

<img class="fd1" src="p1.jfif" id="p1">
<img class="fd2" src="p2.jfif" id="p2">
<img class="fd3" src="p3.jfif" id="p3">
<h3 style="color: rgb(255,255,255)" class="pnom">Produit 1</h3>
<h3 style="color: rgb(255,255,255)" class="pnom">Produit 2</h3>
<h3 style="color: rgb(255,255,255)" class="pnom">Produit 3</h3>
</div>
<br><br><br><br><br><br><br><br><br><br><br><br><br><br>
<br><br><br><br><br><br><br><br><br><br><br><br><br><br>
<br><br><br><br><br><br>

</body>
</html>



