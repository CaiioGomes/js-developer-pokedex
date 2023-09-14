<!DOCTYPE html>
<html lang="pt-BR">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pokédex</title>
    <link rel="stylesheet" href="style.css">
* {
    font-family: 'roboto', sans-serif;
    box-sizing: border-box;
}
body{
    background-color: #fff;
}
h1{
    text-align: center;
    text-size: 2rem;
}
.content {
    padding: 1rem;
    background-color: #fff;
}
ol.pokemons {
    display: grid;
    grid-template-columns: 1fr 1fr;
    list-style: none;
    padding: 0;
    margin: 0;
}
ol .fogo{
    display: flex;
    flex-direction: column;
    margin: .5rem;
    padding: 1rem;
    border-radius: 1rem;
    background-color: #F42a28;
    color: #fff;
}
ol .planta{
    display: flex;
    flex-direction: column;
    margin: .5rem;
    padding: 1rem;
    border-radius: 1rem;
    background-color: #49d0b0;
    color: #fff;
}
ol .agua{
    display: flex;
    flex-direction: column;
    margin: .5rem;
    padding: 1rem;
    border-radius: 1rem;
    background-color:  #019c9f;
    color: #fff;
}
ol .eletrico{
    display: flex;
    flex-direction: column;
    margin: .5rem;
    padding: 1rem;
    border-radius: 1rem;
    background-color: #d2d601;
    color: #fff;
}

.pokemons .detail img{
    max-width: 100%;
    height: 100px;
}
.pokemons .number {
    color: black;
    text-align: right;
    opacity: '1';
    font-size: 1.5rem;
}
.pokemons .name{
    text-align: left;
    color: black;
    font-size: 1.5rem;
}*
</head>

<body>
    <section class="content">
    <h1>Pokédex</h1>

    <ol class="pokemons">
        <li class="fogo">
            <span class="number">#001</span>
            <span class="name">Charmander</span>
            <img src="https://www.pkparaiso.com/imagenes/pokedex/pokemon/004.png" alt="Charmander">
        </li>
        <li class="fogo">  
            <span class="number">#002</span>
            <span class="name">Charmeleon</span>
            <img src="https://www.pkparaiso.com/imagenes/pokedex/pokemon/005.png" alt="Charmeleon">
        </li>
        <li class="fogo"> 
            <span class="number">#003</span>
            <span class="name">Charizard</span>
            <img src="https://www.pkparaiso.com/imagenes/pokedex/pokemon/006.png" alt="Charizard">
        </li>
        <li class="planta">
            <span class="number">#004</span>
            <span class="name">Bulbasaur</span>
        <img src="https://www.pkparaiso.com/imagenes/pokedex/pokemon/001.png" alt="Bulbasaur">
        </li>
        <li class="planta">
            <span class="number">#005</span>
            <span class="name">Ivysaur</span>
        <img src="https://www.pkparaiso.com/imagenes/pokedex/pokemon/002.png" alt="Ivysaur">
    </li>
        <li class="planta">
            <span class="number">#006</span>
            <span class="name">Venusaur</span>
        <img src="https://www.pkparaiso.com/imagenes/pokedex/pokemon/003.png" alt="Venusaur">
    </li>
        <li class="agua">
            <span class="number">#007</span>
            <span class="name">Squirtle</span>
        <img src="https://www.pkparaiso.com/imagenes/pokedex/pokemon/007.png" alt="Squirtle">
    </li> 
    <li class="agua">
        <span class="number">#008</span>
        <span class="name">Wartortle</span>
        <img src="https://www.pkparaiso.com/imagenes/pokedex/pokemon/008.png" alt="Wartortle">
    </li>
        <li class="agua">
            <span class="number">#009</span>
            <span class="name">Blastoise</span>
        <img src="https://www.pkparaiso.com/imagenes/pokedex/pokemon/009.png" alt="Blastoise">
    </li>
        <li class="eletrico">
            <span class="number">#010</span>
            <span class="name">Pikachu</span>
        <img src="https://www.pkparaiso.com/imagenes/pokedex/pokemon/025.png" alt="Pikachu">
    </li>
        <li class="eletrico">
            <span class="number">#011</span>
            <span class="name">Raichu</span>
        <img src="https://www.pkparaiso.com/imagenes/pokedex/pokemon/026.png" alt="Raichu">
    </li>
</ol>
</section>
<script src="script.js"></script>
</body>

</html>
