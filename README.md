<!DOCTYPE html>
<html>
<head background="nd1.jpg" style="color:black">
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
        width: 6em;
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

