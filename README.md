<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CodeHelp da Dhaba</title>
    <link rel="shortcut icon" href="icon.jpeg" type="image/x-icon">
    <link rel="stylesheet" href="work7.css">
</head>
<style>
    *{
        margin: 0%;
        padding: 0%;
    }
    .container{
        background-color: #8BC6EC;
        background-image: linear-gradient(135deg, #8BC6EC 0%, #9599E2 100%);
        border:#9599E2 4px;

        height:100%;
width:100%;
          }
          .heading{
            font-size: 60px;
            color: #c4c5c7;
          }
       .item{
        text-decoration: none;
        display: flex;
        justify-content: space-between;
        gap:38px;
        font-size: 28px;
        padding: 30px;
       }
       .items{
        display: flex;
        justify-content: space-between;
       }
       .navigation{
        min-height: 6px;
        border:2px;
        border-style: ridge;
        border-radius: 2px;
        background-image: radial-gradient( circle farthest-corner at 10% 20%,  rgba(38,51,97,1) 0%, rgba(65,143,222,1) 79% );
        
       }
       .imggulab{
        transition: all 2s ease-in 0s;
        box-shadow: 0px 0px 15px black;
        border-radius: 13px;
        width: 190px;
        height:260px;
        margin:15px;

       }
       .imggulab:hover{
        transform: scale(1.1);
       }
       .imgbarfi{
        transition: all 2s ease-in 0s;
        box-shadow: 0px 0px 15px black;
        border-radius: 13px;
        width: 190px;
        height:260px;
        margin:15px;
    
       }
       .imgbarfi:hover{
        transform: scale(1.1);
       }
       .imggol{
        transition: all 2s ease-in 0s;
        box-shadow: 0px 0px 15px black;
        border-radius: 13px;
        width: 190px;
        height:260px;
        margin:15px;
    
       }
       .imggol:hover{
        transform: scale(1.1);
       }
       .box{
        width:70%;
        margin:auto;
        display: flex;
        flex-direction: column;
        box-shadow: 0px 0px 30px black;
        align-items: center;
       }
       .main{
        display: flex;
       }
       .main1{
        display: flex;
       }
       .main2{
        display: flex;
       }
       .leftbox h1{
        font-size: 30px;
       }
       #footer p{
font-size: 25px;
background-image: radial-gradient( circle farthest-corner at 10% 20%,  rgba(38,51,97,1) 0%, rgba(65,143,222,1) 79% );
border: 1px;
margin:auto;
color: aliceblue;
text-align: center;
       }
  
</style>

  
<body>
    <div class="container">
        <nav class="navigation">
<ul class="items">
    <li><p class="heading">Codehelp da Dhabba</p></li>
    <li class="item">
        <div><a href="#">Home</a></div>
        <div><a href="tel:8708425219">Contact Us</a></div>
        <div><a href="barfi.jpeg">About</a></div>
    </li>
</ul>
</nav>
<div class="box">
<div class="main">
<section class="leftbox">
<h1>Gulab Jamun</h1>
<br>
<h3>Ingredients :</h3>
<br>
<li>bread</li>
<li>Oil</li>
<li>Milk</li>
<li>Sugar</li><br>
<h2>Recipe</h2>
<ol><li>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Animi, labore!</li>
<li>lorem ipsum, dolor sit amet consectetur adipisicing elit.</li>
<li>lorem ipsum dolor sit amet consectetur, adipisicing elit. Dolore, aperiam?</li>
<li>lorem ipsum, dolor sit amet consectetur adipisicing elit. Dignissimos!</li>
</ol>
</section>
<section class="rightbox">
<img src="gulab.jpeg" alt="Gulabjamun" class="imggulab">
</section></div>
<br><br>
<br><br>
<div class="main1">
<section class="leftbox">
    <h1>Barfi</h1>
    <br>
    <h3>Ingredients :</h3>
    <br>
    <li>Milk</li>
    <li>Ghee</li>
    <li>Sugar</li><br>
    <h2>Recipe</h2>
    <ol><li>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Animi, labore!</li>
    <li>lorem ipsum, dolor sit amet consectetur adipisicing elit.</li>
    <li>lorem ipsum dolor sit amet consectetur, adipisicing elit. Dolore, aperiam?</li>
    <li>lorem ipsum, dolor sit amet consectetur adipisicing elit. Dignissimos!</li>
    </ol>
</section>
    <section class="rightbox">
    <img src="barfi.jpeg" alt="Barfi" class="imgbarfi">
    </section>
</div>
<br><br>
<br><br>
<div class="main2">
<section class="leftbox">
    <h1>Gol Gappe</h1>
    <br>
    <h3>Ingredients :</h3>
    <br>
    <li>Flour</li>
    <li>Oil</li>
    <li>Salt</li>
    <li>Species</li><br>
    <h2>Recipe</h2>
    <ol>
        <li>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Animi, labore!</li>
        <li>lorem ipsum, dolor sit amet consectetur adipisicing elit.</li>
        <li>lorem ipsum dolor sit amet consectetur, adipisicing elit. Dolore, aperiam?</li>
        <li>lorem ipsum, dolor sit amet consectetur adipisicing elit. Dignissimos!</li>
    </ol>
</section>
    <section class="rightbox">
    <img src="gol.jpeg" alt="gol" class="imggol">
    </section>
</div>

</div>
<footer id="footer">
    <p> Copyright &#x24B8;CodeHelp da Dhaba Pvt.Ltd 2023 All Rights Reserved </p>
</footer>
    </div>
</body>
</html>
