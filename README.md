<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Connexion</title>
    <link rel="stylesheet" href="style.css">

</head>
<body>
 

    <ul class="menu">
        <img class="logo" src="afpa.png" width="100px">

           <div id="mySidenav" class="sidenav">
            <a id="closeBtn" href="#" class="close">&times;</a>
            <ul>
              <li><a href="#">A propos</a></li>
              <li><a href="#">Nos services</a></li>
              <li><a href="#">Témoignages</a></li>
              <li><a href="#">Contact</a></li>
            </ul>
        </div>
          
        <a href="#" id="openBtn">
            <span class="burger-icon">
              <span></span>
              <span></span>
              <span></span>
            </span>
        </a>

        <script>
            var sidenav = document.getElementById("mySidenav");
            var openBtn = document.getElementById("openBtn");
            var closeBtn = document.getElementById("closeBtn");

            openBtn.onclick = openNav;
            closeBtn.onclick = closeNav;

            
            function openNav() {
            sidenav.classList.add("active");
            }

           
            function closeNav() {
            sidenav.classList.remove("active");
            }
        </script>

        <a href="#">Accueil</a>  
    </ul>
            
    <section class="pseudo">
        <form action=" " method="POST">
            <p class="error">
                  
            </p>
            <label> Entrez votre pseudo </label>

            <input  type="text" name="name" placeholder="" >

            <button class="style_btn" name="button">Soumettre</button>
        </form>
    </section>
    
</body>
</html>
