<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vehcrack</title>
    
    
</head>
<body>
    
    <img src="image/binaireap.jpg" alt="" id="arriereplan">
    <h2 id="vehcrack">Vehcrack</h2>
    
    <ul id="menu-accordeon">
        <li><a href="#">Lien menu 1</a>
           <ul>
              <li><a href="#">lien sous menu 1</a></li>
              <li><a href="#">lien sous menu 1</a></li>
              <li><a href="#">lien sous menu 1</a></li>
              <li><a href="#">lien sous menu 1</a></li>
           </ul>
        </li>
         <li><a href="#">Lien menu 2</a>
           <ul>
              <li><a href="#">Lien sous menu 2</a></li>
              <li><a href="#">Lien sous menu 2</a></li>
              <li><a href="#">Lien sous menu 2</a></li>
              <li><a href="#">Lien sous menu 2</a></li>
           </ul>
        </li>
        <li><a href="#">Lien menu 3</a>
           <ul>
              <li><a href="#">Lien sous menu 3</a></li>
              <li><a href="#">Lien sous menu 3</a></li>
              <li><a href="#">Lien sous menu 3</a></li>
              <li><a href="#">Lien sous menu 3</a></li>
           </ul>
        </li>
     </ul>
    
        


</header>
    <style>
            #search{
                border-radius: 30px;
                position: absolute;
                left: 600px;
                top: 67px;
                font-size: 18px;
                background-color: rgb(233, 12, 12);
            }

            #arriereplan{
                height: 100vh;
                background-size: cover;
                border: none;
                width: 100%;
                
            }
            #logo{
                position: absolute;
                top: 20px;
                left: 20px;
                border-radius: 30px;
                height: 120px;
            }

            #vehcrack{
                position: absolute;
                top: 26px;
                left: 160px;
                font-size: 40px;
                color: whitesmoke;
            }

            #menutelechargement{
                position: absolute;
                top: 40px;
                left: 1260px;
            }

            #Titre{
                position: absolute;
                top: 685px;
                left: 1510px;
                color: red;
            }
            
            #p1{
                position: absolute;
                top: 693px;
                left: 1260px;
                color: red;
            }

            #button{
                position: absolute;
                left: 840px;
                top: 70px;
                background-color: red;
                height: 23px;
                width: 91px;
                font-size: 18px;
            }

            

            #menu-accordeon {
  padding: 10;
  margin: 0;
  list-style:none;
  text-align: center;
  width: 180px;
  position: absolute;
  top: 40px;
  left: 1320px;
}
#menu-accordeon ul {
  padding:0;
  margin: 0px;
  list-style:none;
  text-align: center;
}
#menu-accordeon li {
   background-color:#729EBF; 
   background-image:-webkit-linear-gradient(top, #729EBF 0%, #333A40 100%);
   background-image: linear-gradient(to bottom, #729EBF 0%, #333A40 100%);
   border-radius: 6px;
   margin-bottom:2px;
   box-shadow: 3px 3px 3px #999;
   border:solid 1px #333A40;
   
   
   
   
}
#menu-accordeon li li {
   max-height:0;
   overflow: hidden;
   transition: all .5s;
   border-radius:0;
   background: #444;
   box-shadow: none;
   border:none;
   margin:0
}
#menu-accordeon a {
  display:block;
  text-decoration: none;
  color: #fff;
  padding: 8px 0;
  font-family: verdana;
  font-size:1.2em
}
#menu-accordeon ul li a, #menu-accordeon li:hover li a {
  font-size:1em
}
#menu-accordeon li:hover {
   background: #729EBF
}
#menu-accordeon li li:hover {
   background: #999;
}
#menu-accordeon ul li:last-child {
   border-radius: 0 0 6px 6px;
   border:none;
}
#menu-accordeon li:hover li {
  max-height: 15em;
}

            
            

    


    

            
            
        
        </style> 
        <style>
            
        </style>   
        

    
        

        <h1>
    <section class="top-page"><nav><header class="header">
            <img src="image/1650392281245.png" alt="" id="logo">
        
                <div class="landing-page">
                    
                    
 
 

    </ul>
    </nav>
        
        </div>
    <form><section class="letexte">
    <h2></h2>
    <header class="texte1">
        
        
        
        <input type="search" id="search" value="" onchange="ouvirpage()" placeholder="Rechercher..." >
        <input type="button" id="button" onclick="ouvirpage()" value="Chercher">
       <script>
        function ouvirpage(){
            var a = document.getElementById("search").value;

            if(a === "application" ){
                window.open("/index2.html");
            }

            if(a === "téléchargement"){
                window.open("/index4.html");
            }
            
            
        
        
            
              else{
                alert("Nous avons rien trouvé");
            }     
        }    

        
            
            
        
        
            
            

            
        
                
              
            
               
                 
            
        



       </script>
    
    
     </form>
         

 
        
        

<p id="p1">Random num =><h1 class="Titre" id="Titre">0</h1></p>

<script type="text/javascript">
 
  

  Titre.innerHTML = Math.floor(Math.random() * 99) + 1;

  



</script>

            


 
</h1>
</section>
    </section>
   

    
           
</body>
</html>
