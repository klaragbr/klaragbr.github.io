# klaragbr.github.io*{
    font-family: 'verdana', 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}

body {
    background-color: rgb(228, 230, 161);
    margin: 0;
}

nav ul{
    margin: 0;
    padding: 0;
    display:flex;
    flex-direction: row;
    justify-content: space-around;
}

.nav-link{
display: block;
width: 100%;
height: 40px;
text-align: center;
padding-top: 1em;
transition: background-color 0.5s;
transition: color 0.5s}

.nav-link{
color: rgb(32, 134, 202);
}

.nav-link:hover {
    color: cornsilk;
    background-color: rgb(53, 81, 156);
}

ul li.nav-link {
    list-style-type: none;
}

main {
    max-width: 80%;
    padding-top: 10px;
    margin: auto;
}

.oferta {
    width: 100%;
    display: flex;
    justify-content: space-around;
    height: 200px;
}

.obraz {
    width: 30%;
    background: url("http://placekitten.com/200/100");
`   background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
}

.obraz img {
max-width: 100%;
}

.info {
    width: 70%;
    margin-left: 2em;
}
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>janusz xd</title>
        <link rel="stylesheet" href="main.css"/>
    </head>    
    <body>
        <nav>
            <ul>
                <li class="nav-link">Home</li>
                <li class="nav-link">Kontakt</li>
                <li class="nav-link">Top3</li>
                <li class="nav-link">bakterie</li>
            </ul>
        </nav>
        <main>
            <img src="http://placekitten.com/250/250"/>
           <div class="oferta">
               <div class="obraz">
                   
               </div>
               <div class="info">
                   <h3>koteł 1</h3>
                   <p>
                       polecanko spanko życie
                   </p>
               </div>
           </div><br>
           <div class="oferta">
            <div class="obraz">
               
            </div>
            <div class="info">
                <h3>koteł 2</h3>
                <p>
                    polecanko spanko życie
                </p>
            </div>
        </div><br>
        <div class="oferta">
            <div class="obraz">
               
            </div>
            <div class="info">
                <h3>koteł 3</h3>
                <p>
                    polecanko spanko życie
                </p>
            </div>
        </div><br>
        <div class="oferta">
            <div class="obraz">
                
            </div>
            <div class="info">
                <h3>koteł 4</h3>
                <p>
                    polecanko spanko życie
                </p>
            </div>
        </div>
        </main>
    </body>
</html>
