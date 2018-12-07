# UoVwebsite

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>U-OV website</title>
    <link rel="stylesheet" href="styles.css" />
</head>
<body>
   <header> <img class="uov" src="images/uovlogo.png" alt="Logo U-OV"></header>
   
    <div>
        <h1> Lezen tijdens het reizen</h1>
        <h2> 99 verhalen </h2>
    
        <img class="heart" src="images/heart.png" alt="heart">
        <a class="opgeslagen" href="opgeslagen.html">Opgeslagen</a>
        
        <a class="verrasme" href="website.html">Verras me</a>
        
        <label for="zoeken"> Zoeken 
            <input id="zoeken" type="text">
        </label>
    </div>
    
    <form class="filter" action="POST">
        <select name="verhalen" id="verhalen">
           <option value="Alle verhalen">Alles</option>
            <option value="Boos">Boos (22) </option>
            <option value="Blij">Blij (18) </option>
            <option value="Verdriet">Verdriet (19) </option>
            <option value="Verliefd">Verliefd (19) </option>
            <option value="Angst">Angst (11) </option>   
        </select>   
    </form>
    
    <form class="sorteer" action="POST">
        <select name="sorteer" id="populair">
            <option value="Populair">Populair</option>
            <option value="A-Z">A-Z</option>
            <option value="Nieuw - oud">Nieuw -Oud</option>
        </select>
    </form>
    
    
    <article>    
        
        <h3>Paranoia</h3>
        <p class="tekst">
        <img class ="paranoia" src="images/paranoia.jpg" alt="paranoia">
        <br/>
        Ik sluip de bus uit. Kop in de kraag. Ik maak me klein en duw m’n zoon vooruit. Hij slaapt. Eindelijk. Zijn gejengel trok veel te veel aandacht. De mensen lopen over het stationsplein. Het voelt alsof er een grote, knipperende pijl boven m’n hoofd hangt: HIER LOOPT HIJ! Gelukkig is het kloteweer en kijken...
        </p>
        <a class="leesverder" href="paranoia">Lees verder</a>
        
    </article>
    
    
    
    
    
    
</body>
</html>
